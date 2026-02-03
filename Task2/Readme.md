# AWS EC2 Creation – Manual & Terraform

## AWS Core Concepts (Short)
- **Region**: Physical AWS location (ap-south-1 – Mumbai)
- **Availability Zone**: Isolated data centers inside a region
- **VPC**: Private network for AWS resources
- **EC2**: Virtual server in AWS
- **AMI**: OS image used to launch EC2
- **Security Group**: Virtual firewall for EC2
- **Key Pair**: Used for secure SSH access

---

## EC2 Creation Using AWS Console (Manual)

### Steps:
1. Logged in to AWS Management Console
2. Navigated to **EC2 → Launch Instance**
3. Selected **Amazon Linux 2 AMI**
4. Chose instance type **t2.micro**
5. Created a new **Key Pair**
6. Configured **Security Group** to allow SSH (port 22)
7. Launched the EC2 instance successfully
8. Verified instance status in EC2 dashboard

---

## EC2 Creation Using Terraform (Step by Step)

### Tools Used:
- AWS
- Terraform

### Resources Created Using Terraform:
- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- Key Pair
- EC2 Instance

### Steps:
1. Installed and configured Terraform
2. Created Terraform configuration files
3. Defined AWS provider and variables
4. Created networking resources (VPC, Subnet, IGW)
5. Created Security Group and Key Pair
6. Provisioned EC2 instance using Terraform
7. Verified EC2 instance in AWS Console

### Terraform Commands Used:
```bash
terraform init
terraform plan
terraform apply
