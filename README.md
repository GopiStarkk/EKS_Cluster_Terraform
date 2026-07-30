# Terraform AWS EKS Platform

## Overview

This repository provisions a production-ready Amazon Elastic Kubernetes Service (Amazon EKS) platform using Terraform.

The solution automates the complete Kubernetes infrastructure lifecycle, including networking, security, IAM, worker nodes, and supporting AWS resources.

---

## Features

- Infrastructure as Code using Terraform
- Custom VPC
- Public & Private Subnets
- NAT Gateway
- Internet Gateway
- Route Tables
- Security Groups
- Amazon EKS Cluster
- Managed Node Groups
- IAM Roles
- IAM Policies
- OIDC Provider
- CloudWatch Logs

---

## Technologies

Terraform

AWS

Amazon EKS

IAM

VPC

CloudWatch

GitHub

Jenkins

Helm

kubectl

AWS CLI

---

## Repository Structure

(terraform/
modules/
docs/
README.md)

---

## Deployment Workflow

terraform init

↓

terraform validate

↓

terraform plan

↓

terraform apply

↓

Amazon EKS Ready

↓

terraform destroy
