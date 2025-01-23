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

Project 3: VPC with Public and Private Subnets and fully variabilizing the code

    Description: Configures a VPC with both public and private subnets, an internet gateway, and an EC2 instance running a Python Flask app.
    Key Features:
        Advanced networking with public and private subnets.
        Security groups for SSH, HTTP, and HTTPS traffic.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-3

Project 4: Bastion Host with Private Instance

    Description: Configures a VPC with a public Bastion host and a private EC2 instance for secure SSH access.
    Key Features:
       Sets up a VPC with public and private subnets.
       Security groups for Bastion host and private instance.
       Internet Gateway and public route table for external connectivity.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-4

Project 5: Jenkins-Terraform Integration for Automated Infrastructure Deployment

    Description: Automates the deployment and management of AWS infrastructure (VPC, EC2, S3) using Terraform, with CI/CD integration via Jenkins.
    Key Features:
      Configures AWS resources such as VPC, EC2 instances, and S3 buckets using Terraform.
      Uses an S3 backend for state management and DynamoDB for state locking.
      Integrates Terraform with Jenkins for automated provisioning and management of infrastructure.
      Implements a Jenkins pipeline with stages for initialization, planning, and applying infrastructure changes.
    Location: https://github.com/Mohammed-Amer-learner/Terraform-AWS-Projects-Repository/blob/main/terraform%2Baws-project-5
