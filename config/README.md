Happy Garden uses `Ansible` to automate configuration.

## Post-setup
The playbook `post_setup` would config the following tasks once Proxmox is installed on the server:
* Configure `Proxmox`:
    1. Switch to non-enterprise (please seriously consider putting a one-time donation for homelab use).
    2. Perform kernel update.
    3. (Future) Configures Proxmox Groups, User accounts, and Access Control Lists - maybe an overkill for `homelab`.
* Set up key based SSH access and disable password SSH.
* Set IP of happy garden to my laptop.
* Set up zero-tier to have cluster access when I am at a coffee shop :).


## Wish list
* Set up Grafana for monitoring cluster's health.
* Set up Ceph Cluster Storage.
