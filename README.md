## 🚀 Featured Project: Multi-Environment AWS Infrastructure with Terraform

Built a **multi-environment AWS infrastructure** using **Terraform**, provisioning separate **Production**, **Development**, and **Staging** environments through reusable Infrastructure as Code (IaC).

### ✨ Key Highlights

* 🌍 Provisioned separate **Production**, **Development**, and **Staging** environments.
* 📦 Used **Terraform modules** to keep the code reusable and maintainable (DRY principle).
* 💻 Deployed **EC2 instances** with environment-specific configurations.
* 🏷️ Implemented best practices for resource tagging and modular infrastructure design.
* 📁 Organized Terraform code for scalability and easier maintenance.
* ☁️ Strengthened hands-on experience with **AWS** and **Infrastructure as Code (IaC)**.

flowchart TB

A[👨‍💻 Developer] --> B[📦 Terraform CLI]
B --> C[📁 Terraform Codebase]
C --> D[📂 Modules<br/>Reusable Infrastructure]

D --> E1[🌍 Dev Environment]
E1 --> F1[☁️ AWS Dev Account / VPC]
F1 --> G1[🖥️ EC2 Instances]

D --> E2[🧪 Staging Environment]
E2 --> F2[☁️ AWS Staging Account / VPC]
F2 --> G2[🖥️ EC2 Instances]

D --> E3[🚀 Production Environment]
E3 --> F3[☁️ AWS Production Account / VPC]
F3 --> G3[🖥️ EC2 Instances]

G1 --> H[📡 Application Running]
G2 --> H
G3 --> H

🔗 **Repository:** https://github.com/sk7652183-rgb/terraform_infra_environment
