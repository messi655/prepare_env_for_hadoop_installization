- Copy JDK with format jdk.tgz to roles/java/files/
- Install Ansible Playbook on Ansible host
- Make sure from Ansible host can access to remote without pass phrase
- Run command: ansible-playbook -i hosts -s setting.yml