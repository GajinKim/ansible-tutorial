```bash
# ping (double check directory)
ansible myhosts -m ping -i inventory.yml --user ubuntu 
```

```bash
# run playbook (double check directory)
ansible-playbook -i inventory.ini playbook.yaml --user ubuntu
```

### Using Ansible with AWS SSM
https://docs.ansible.com/ansible/latest/collections/community/aws/aws_ssm_connection.html

### Getting Started Docs
https://docs.ansible.com/ansible/latest/getting_started/index.html