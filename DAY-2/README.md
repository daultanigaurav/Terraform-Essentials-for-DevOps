# 📘 Day 2: Providers, Resources, Variables & Outputs

Welcome to **Day 2** of the Terraform Essentials Learning Path!  
Today we dive deeper into Terraform fundamentals — you'll learn how to use **providers**, define **resources**, work with **variables**, and extract **outputs**.

---

## 🎯 Goals for Today

- Understand **providers** and how they connect Terraform to cloud services
- Define and provision **resources** (e.g., AWS instance, Azure RG, etc.)
- Use **input variables** to make configurations reusable and dynamic
- Use **output values** to extract and reuse information from your deployments

---

## 🧠 Topics Covered

| Topic         | Description                                                  |
|---------------|--------------------------------------------------------------|
| 🌐 Providers   | Configure and authenticate with cloud platforms              |
| 📦 Resources   | Define cloud resources in HCL (e.g., AWS EC2, S3, etc.)      |
| 🔧 Variables   | Pass dynamic values into Terraform configs using `tfvars`    |
| 📤 Outputs     | Print and export useful info like IPs, ARNs, etc.            |

---

## 📂 Files Overview

- **main.tf** — Provider + Resource definition
- **variables.tf** — Variable declarations
- **terraform.tfvars** — Actual values assigned to variables
- **outputs.tf** — Output the values post-deployment

---

## 💻 Hands-On Example: AWS Provider + EC2 Instance

This example launches an EC2 instance in AWS using variables and outputs.

---

## ⚙️ Setup

Make sure you have:

- AWS CLI configured with IAM credentials (`aws configure`)
- Terraform CLI installed

---

### ✅ Step-by-step

```bash
terraform init
terraform plan
terraform apply
terraform destroy   # To tear down the infra
