# Amazon EKS Platform using Terraform

## Project Overview

This repository provisions a production-ready Amazon EKS platform using Terraform.

The infrastructure includes

- VPC
- Public & Private Subnets
- NAT Gateway
- Internet Gateway
- IAM Roles
- Security Groups
- EKS Cluster
- Managed Node Groups
- OIDC Provider
- CloudWatch Logging

---

## Infrastructure Architecture

Internet

↓

Application Load Balancer

↓

Amazon EKS

↓

Worker Nodes

↓

Pods

↓

Amazon ECR

---

## Terraform Workflow

terraform init

↓

terraform validate

↓

terraform plan

↓

terraform apply

↓

terraform destroy
