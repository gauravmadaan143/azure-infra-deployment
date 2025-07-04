# Author Gorav Madan 
# Azure Infra Deployment with Terraform, Ansible & Azure DevOps

## 📋 Prerequisites
- Azure Subscription
- Azure DevOps Project with service connection
- SSH/Password access to VM
- Terraform & Ansible knowledge

## 🚀 How to Run the Pipeline

1. Fork and clone the repo
2. Set up Azure DevOps pipeline
3. Configure Service Connection & variables (if needed)
4. Run pipeline from Azure DevOps
5. VM will be provisioned and configured with Nginx

## 🔧 Tech Stack
- Terraform (azurerm)
- Ansible (playbook to install packages)
- Azure DevOps YAML pipeline

## ✅ Output
- Resource Group, VM, VNet, NIC, Public IP created
- Ansible configures VM with NGINX

## 🔁 Idempotency
- Re-running the pipeline won't cause duplicate resources

---
Thanks for reviewing this!
