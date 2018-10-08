# AnsibleEC2

Ansible scripts to set up basic apps running on EC2 instances

## Instructions

To obtain the IP addresses of your EC2 instances:

```
ansible-playbook helloworld.yml -e target=ec2 --list-hosts
```

To run the playbook:

```
ansible-playbook helloworld.yml -e target=[your ip here]
```
