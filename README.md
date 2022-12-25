# ansible_localdesktop
manage local desktop

# doc: https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-20-04

$ ansible -i ./hosts all -m ping -u root
$ ansible -i ./hosts all -a "df -h" -u root

# https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html#ansible-playbook
# https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html#playbook-syntax

$ ansible-playbook localplaybook.ansible.yml 
$ ansible-playbook -i ./hosts localplaybook.ansible.yml -u root
$ ansible-playbook -i ./hosts localplaybook.ansible.yml 


# Failed to connect to the host via ssh: ssh: connect to host 127.0.0.1 port 22: Connection refused

# Failed to connect to the host via ssh: root@127.0.0.1: Permission denied (publickey,password).

