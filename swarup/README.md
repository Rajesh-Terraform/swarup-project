# Simple Terraform AWS Project

This project creates a simple AWS infrastructure using Terraform.

## Architecture

Terraform
   |
   +-- VPC
       |
       +-- Internet Gateway
       |
       +-- Public Subnet
       |
       +-- Route Table
       |
       +-- Security Group
       |
       +-- EC2 Instance
           |
           +-- Nginx Web Server

## Resources Created

- AWS VPC
- Internet Gateway
- Public Subnet
- Route Table
- Security Group
- EC2 Instance
- Nginx web server

## Requirements

- Terraform
- AWS CLI
- AWS account
- AWS credentials configured

## Terraform Commands

Initialize Terraform:

```bash
terraform init