# 4640-in-class-wk10
Allison Chen, Jean Venter and Joanne Xie

![web](/server-img.png)

### Terraform cmds used in this lab:
```
terraform init
terraform fmt
terraform validate
terraform apply
```
![ip](/ip.png)

### Ansible cmds used in this lab:
test inventory
```
ansible-inventory -i inventory/aws_ec2.yml --graph
```
![test](/test.png)
```
ansible all -i inventory/aws_ec2.yml --list-hosts
```
![hosts](/hosts.png)
run playbook
```
ansible-playbook -i inventory/aws_ec2.yml playbook.yml
```
![playbook](/playbook.png)
idempotence
```
ansible-playbook -i inventory/aws_ec2.yml playbook.yml
```
![idempotence](/idempotence.png)
