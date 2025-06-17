# 🌐 Terraform VPC Infrastructure with Load Balanced Applications

This project uses **Terraform** to provision cloud infrastructure on **AWS**, including:
- A **VPC** with public subnets in multiple **Availability Zones**
- Two **EC2 instances** hosting separate applications
- An **Application Load Balancer (ALB)** to distribute incoming traffic between the instances



🚀 Features
🔒 Creates a custom Virtual Private Cloud (VPC) with subnets, routing tables, and internet gateways.

☁️ Launches 2 EC2 instances in separate Availability Zones for high availability.

📡 Sets up an Application Load Balancer (ALB) with a target group that automatically balances incoming traffic across the instances.

🛠 User data scripts automatically install and start simple web applications on the instances.



🧰 Prerequisites
Terraform installed

AWS CLI configured with your credentials (aws configure)

An AWS account



🛠️ Important Terraform Commands
Command	Description

terraform init :	Initializes Terraform configuration and downloads provider plugins

terraform plan :	Creates an execution plan showing what Terraform will do

terraform apply :	Applies the changes required to reach the desired state

terraform destroy :	Destroys all resources defined in the configuration

terraform validate :	Validates the syntax of the configuration files

terraform fmt :	Formats the Terraform configuration files for readability

terraform show :	Shows the current state or plan of infrastructure

terraform output :	Displays the output variables from your Terraform state
