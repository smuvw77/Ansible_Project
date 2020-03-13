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


kitchen.yml
export AWS_SSH_KEY_ID="EC2_0308"
export AWS_SSH_KEY="/home/cloud_user/.aws/$AWS_SSH_KEY_ID.pem"

Steps: 
 1. login:  ssh ec2_user@publicip
 2.Crete AWS and get teh Access key and security access key 
 3. create new key pair 
 4. update key pair .aws/cred adn chmod 400 k
 5.run  below commands use same key pair name EC2_0308
 
      export AWS_SSH_KEY_ID="EC2_0308" 
 export AWS_SSH_KEY="/home/cloud_user/.aws/$AWS_SSH_KEY_ID.pem"
 
