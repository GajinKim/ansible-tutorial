```bash
# ping (double check directory)
ansible myhosts -m ping -i inventory.yml --user ubuntu 
```

```bash
# run playbook (double check directory)
ansible-playbook -i inventory.ini playbook.yaml --user ubuntu
```