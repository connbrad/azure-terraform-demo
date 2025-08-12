# Azure Infrastructure Demo with Terraform

## Overview
This project is part of my **30-day Azure Cloud Skill-Building Plan**.  
It demonstrates how to deploy and manage infrastructure in **Microsoft Azure** using **Terraform** (Infrastructure-as-Code).

The goal is to solidify core Azure administration skills while building a public portfolio project that showcases:
- Real-world cloud resource provisioning
- Infrastructure-as-Code workflows
- Version control best practices

---

## Project Objectives
1. Learn and apply **Azure Administrator (AZ-104)** concepts in a practical environment.
2. Build a reproducible Azure environment using **Terraform**.
3. Create professional documentation and diagrams for future reference.
4. Practice GitHub collaboration and commit discipline.

---

## Tools & Technologies
- **Cloud Provider:** Microsoft Azure
- **IaC Tool:** Terraform
- **Version Control:** Git + GitHub
- **Scripting:** Bash/PowerShell
- **Diagramming:** Draw.io / Lucidchart (for architecture diagrams)

---

## Repository Structure
```
azure-vm-terraform-demo/
│
├── README.md                 # Project overview (this file)
├── docs/                     # Documentation and diagrams
│   ├── architecture-diagram.png
│   ├── notes.md
│   └── glossary.md
│
├── terraform/                # Terraform configuration files
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   ├── provider.tf
│   └── backend.tf
│
├── scripts/                   # Deployment & teardown scripts
│   ├── deploy.sh
│   └── destroy.sh
│
└── .gitignore
```

---

## Getting Started

### 1️⃣ Prerequisites
- [Install Terraform](https://developer.hashicorp.com/terraform/downloads)
- [Install Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- [Create a free Azure account](https://azure.microsoft.com/free/) if you don't have one.

### 2️⃣ Clone this Repository
```bash
git clone https://github.com/<your-username>/azure-infra-demo.git
cd azure-infra-demo
```

### 3️⃣ Initialize Terraform
```bash
terraform init
```

---

## Learning Plan Integration
This project is being developed as part of my structured 30-day study plan:
- **Days 1–10:** Azure Fundamentals refresh + Initial Terraform setup
- **Days 11–20:** Deploying core infrastructure (VMs, networking, storage)
- **Days 21–30:** Scaling, security, and automation

---

## License
This repository is licensed under the MIT License – see [LICENSE](https://opensource.org/license/mit) for details.

---

## Author
**Conner Bradley**  
IT Professional | Cloud Learner | Future Azure Expert  
