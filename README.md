**Terraform AWS Projects Repository**

Overview

This repository contains a collection of Terraform configurations for automating the creation of AWS infrastructure. Each project demonstrates different aspects of Infrastructure as Code (IaC) using Terraform and AWS services. The configurations are modular, reusable, and designed for deployment in real-world scenarios.

Project 1: Basic EC2 Instance and S3 Bucket

    Description: Creates an EC2 instance and an S3 bucket to demonstrate basic AWS resource provisioning.
    Key Features:
        Parameterized with variables for AMI, instance type, and S3 bucket name.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-1

Project 2: VPC with Public Subnet and Flask App

    Description: Deploys a VPC, a public subnet, and an EC2 instance hosting a Python Flask application.
    Key Features:
        Sets up networking resources like a VPC, subnet, and internet gateway.
        Uses provisioners to deploy and run a Flask application.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-2

Project 3: VPC with Public and Private Subnets

    Description: Configures a VPC with both public and private subnets, an internet gateway, and an EC2 instance running a Python Flask app. Fully variabilized.
    Key Features:
        Advanced networking with public and private subnets.
        Security groups for SSH, HTTP, and HTTPS traffic.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-3
