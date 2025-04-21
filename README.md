🛠️ AWS Infrastructure Provisioning with Terraform

This project provisions a complete infrastructure stack on AWS using Terraform modules — including VPC, EC2 instances, and IAM roles.

 🔍 Features
- Reusable Terraform modules
- Isolated environments (dev/stage/prod)
- Scalable and production-ready design

 ☁️ Resources Provisioned
- Custom VPC with subnets
- EC2 instances with SSH access
- IAM users and roles

## 📁 Project Structure

- `modules/`
  - `vpc/` — Terraform module for custom VPC
  - `ec2/` — EC2 provisioning
  - `iam/` — IAM roles and policies
- `main.tf` — Root configuration
- `outputs.tf` — Output variables
- `provider.tf` — AWS provider config
- `variables.tf` — Input variables
- `README.md`
- `LICENSE`
