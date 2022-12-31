# AWS-Config-Repo

This repository contains configuration files for Amazon AWS.

---

## ec2-ubuntu-nodejs-codedeploy-sg.yml

This YAML template launches the _UBUNTU EC2 instances with Node JS and AWS CodeDeploy Agent_ installed. The detailed configuration is as follows:

- **EC2 instance (t2.micro):** An EC2 instance with AMI - Ubuntu Server 20.04 LTS (HVM), SSD Volume Type. The following softwares are pre-installed into the instance:

  - Node JS
  - PM2
  - CodeDeploy Agent

- **Security Groups:** The following security groups are created:
  - SSH EC2 security group
  - HTTP/HTTPS EC2 security group
  - Custom TCP post 3000 EC2 security group

### **Parameters Required**

- The EC2 keypair name

---

## ec2-ubuntu-nodejs-sg.yml

This YAML template launches the _UBUNTU EC2 instances with Node JS and Git_ installed. The detailed configuration is as follows:

- **EC2 instance (t2.micro):** An EC2 instance with AMI - Ubuntu Server 20.04 LTS (HVM), SSD Volume Type. The following softwares are pre-installed into the instance:

  - Node JS
  - PM2
  - Git

- **Security Groups:** The following security groups are created:
  - SSH EC2 security group
  - HTTP/HTTPS EC2 security group
  - Custom TCP post 3000 EC2 security group

### **Parameters Required**

- Instance Name
- Availability Zone
- The EC2 keypair name

---
