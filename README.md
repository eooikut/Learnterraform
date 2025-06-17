# ☁️ Learn Terraform – AWS EC2 Example

This project demonstrates a basic use case of **Terraform** to provision an **AWS EC2 instance** and configure a **Security Group** using variables and outputs.

---

## 🔧 What it does

- Provisions 1 EC2 instance (t2.micro)
- Creates Security Group allowing ports 22 (SSH) and 80 (HTTP)
- Outputs the public IP address of the instance

---

## 📁 File Structure

Learnterraform/
├── main.tf # EC2 & SG resource definitions
├── variables.tf # Input variables
├── terraform.tfvars # Actual values for variables
├── outputs.tf # Output IP
├── provider.tf # AWS provider config
## 🚀 How to Run

> ✅ Prerequisites: AWS credentials configured, Terraform installed

```bash
terraform init
terraform plan
terraform apply


📎 Author
Nguyen Xuan Hieu – DevOps Learner

GitHub: @eooikut
