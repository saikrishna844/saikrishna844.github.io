+++
title = "Projects"
description = "Cloud, Terraform, Azure, AWS, Docker, networking, and DevOps automation projects."
draft = false
ShowReadingTime = false
+++

# 🚀 Featured Projects

## Enterprise Azure Landing Zone Using Terraform

Enterprise Azure infrastructure implemented with reusable Terraform modules and GitHub Actions CI/CD.

**Highlights:** Terraform modules, Azure networking, Azure Bastion, VMs, Log Analytics, Diagnostic Settings, remote state, approval workflows.

- [GitHub Repository](https://github.com/saikrishna844/Azure-Enterprise-Landing-Zone-Using-Terraform)
- [LinkedIn Article](https://www.linkedin.com/pulse/building-enterprise-grade-azure-landing-zone-using-code-sai-krishna-bxv4f/)

## Terraform Multi-Cloud Infrastructure

Independent Azure and AWS deployments using Terraform.

**Azure:** Resource Group, VNet, Subnet, NSG, Public IP, NIC, Linux VM.

**AWS:** VPC, Subnet, Internet Gateway, Route Table, Security Group, EC2, S3.

- [GitHub Repository](https://github.com/saikrishna844/terraform-multi-cloud-basics)
- [Hashnode Article](https://saikrishnavempati.hashnode.dev/terraform-multi-cloud-infrastructure-aws-azure-from-scratch)

## Dockerized Web Application

Node.js application containerized with Docker and Docker Compose.

## WireGuard VPN on Ubuntu

Secure remote-access VPN with key authentication, IP forwarding, UFW rules, and controlled routing.

## Secure Multi-Tenant Enterprise Deployment Platform 

I designed and implemented an Enterprise Multi-Tenant Azure Deployment Platform that enables multiple customers (tenants) to be deployed from a single reusable Terraform codebase while maintaining complete infrastructure isolation.

The platform follows Infrastructure as Code (IaC) best practices with modular Terraform architecture, remote state management, GitHub Actions CI/CD, secure authentication using OpenID Connect (OIDC), Azure governance, monitoring, backup, and production-ready deployment workflows.

This project simulates how enterprise organizations provision and manage Azure infrastructure for multiple business units or customers in a secure, scalable, and automated manner.


## Built Automated Azure Terraform Drift Detection with GitHub Actions and OIDC

Built an enterprise-ready Azure Terraform drift detection solution using GitHub Actions and secure, passwordless OIDC authentication. The automated workflow periodically compares the deployed Azure infrastructure against the desired Terraform configuration to identify unauthorized or unintended changes. It generates Terraform plan reports and clearly highlights detected configuration drift without automatically modifying production resources. This approach improves infrastructure governance, security, auditability, and operational reliability while eliminating long-lived Azure credentials.


- [GitHub Repository](https://github.com/saikrishna844/azure-terraform-drift-detection)   

## AI-Assisted Terraform Governance with MCP, GitHub Copilot & Azure 

Built an AI-assisted Infrastructure as Code workflow by integrating GitHub Copilot with the HashiCorp Terraform MCP Server for Terraform and AzureRM context. Extended the solution with Azure remote state, GitHub OIDC authentication, protected environments, Terraform plan review, and a mandatory human approval gate before deployment. Implemented exact reviewed-plan execution and Terraform drift detection/remediation to demonstrate a governed cloud infrastructure lifecycle.

- [GitHub Repository](https://github.com/saikrishna844/azure-terraform-mcp-ai)

 
