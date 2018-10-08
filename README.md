# AnsibleEC2

Ansible scripts to set up a basic NodeJS app running on an EC2 instance

## Instructions

To obtain the IP addresses of your EC2 instances:

```
ansible-playbook helloworld.yml -e target=ec2 --list-hosts
```

To run the playbook:

```
ansible-playbook helloworld.yml -e target=[your ip here]
```
