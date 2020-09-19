# Configure Happy Garden!

install:
	ansible-playbook -i garden.site playbooks/ubuntu.yml -e 'install=true' --ask-become-pass

stop:
	ansible-playbook -i garden.site playbooks/ubuntu.yml -e 'stop=true' --ask-become-pass
