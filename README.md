# ansible-config
test 1


ansible_ssh_private_key_file=/home/ubuntu/.ssh/devops

eval `ssh-agent -s`
ssh-add ./devops.pem
ssh-add -k devops.pem
ssh-add -l

ssh -A ubuntu@public-ip

step 1
check for /var/lib/jenkins/jobs/ansible/builds  
to see builds

sudo mkdir /home/ubuntu/ansible-config-artifact
chmod -R 0777 /home/ubuntu/ansible-config-artifact

install  Copy Artifact

configure 

create site .yml 
create startic assignment


configure atifact

Ansible Galaxy is a repository for Ansible Roles