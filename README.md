# Install ansible and ansible-playbook, before that, python and boto need to be installed
 
ansible-playbook -vvv -i localhost, -e "type=avlaws" sftp-provision.yml

ansible-playbook -vvv -i localhost, -e "type=avlaws" sftp-remove.yml