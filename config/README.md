Happy Garden uses `Ansible` to automate configuration.


## Local Ubuntu setup



## Post-setup
The playbook `post_setup` would config the following tasks once Proxmox is installed on the server:
* Switch to non-enterprise Proxmox (please seriously consider putting a one-time donation for homelab use).
* Set up key based SSH access and disable password SSH.
* Set up zero-tier to have cluster access when I am at a coffee shop :).
* Set IP of happy garden to my laptop.


## Wish list
* Set up Grafana for monitoring cluster's health.
* Perform kernel update.
* Configures Proxmox Groups, User accounts, and Access Control Lists - maybe an overkill for `homelab`.