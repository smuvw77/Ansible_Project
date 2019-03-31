# Ansible_Project


Tags:
ansible-playbook playbook_tag.yml

ansible-playbook playbook_tag.yml --tags "packages"

ansible-playbook playbook_tag.yml --skip-tags "packages"




ansible-vault create name.yml
ansible-vault edit name.yml
ansible-vault rekey name.yml
ansible-vault decrypt name.yml

ansible-vault encrypt name.yml - >encrypt for exitign yml file 


ansible-playbook name.yml --ask-vault-pass

ansible-playbook name.yml  --start-at="Install Git" (name of the TASK)

ansible-playbook name.yml  --step (  should be prompted for each task run)
