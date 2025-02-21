# ACIT-4640-Lab7
Raymond Nguyen
Aaron Dimatulac

We first have to generate an ssh key so we could connect to aws with terraform:  
`ssh-keygen -t ed25519 -f ~/.ssh/aws`  


We then ran terraform with:  
`terraform init` to initialize the directory  
`terraform plan` to create tf plan file  
`terraform apply plan` to run terraform to build our 2 ec2 instances  

We then ran ansible with:  
`ansible -i inventory/hosts.yml playbook.yml`  
![image](https://github.com/user-attachments/assets/d42a5a6f-8a9e-4c4a-96a1-3fd86ed28763)  
