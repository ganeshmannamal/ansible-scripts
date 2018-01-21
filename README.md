# Ansible Scripts

## Instructions

### Add an inventory file

``` text
[rabbitmq]
xx.xx.xx.xx.xx ansible_user=user ansible_ssh_private_key_file=/path/to/key
```

### Run playbook

`ansible-playbook -i inventory rabbitmq.yml`