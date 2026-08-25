# 05. DevSecOps CI/CD Pipeline & Infrastructure Validation

## 📌 Overview
This project builds a DevSecOps continuous integration pipeline using GitHub Actions to automate static code security scanning, Bicep/ARM template validation, and Policy-as-Code checks before deployment.

## 🛠️ Built With & Technologies Used
* **GitHub Actions** (CI/CD Automation Workflows)
* **Azure Bicep / ARM Templates** (Infrastructure as Code)
* **Static Analysis Tools** (Checkov / KICS Security Scanning)
* **Azure OIDC Federation** (Secretless GitHub Authentication)

## 🎯 Key Implementation Steps
1. **Workflow Pipeline:** Created GitHub Actions YAML workflows triggered on pull requests to the infrastructure repository.
2. **Static Security Scanning:** Integrated security linters to scan Bicep code for misconfigurations (e.g., open NSG ports, unencrypted storage) prior to deployment.
3. **Policy-as-Code Validation:** Configured pre-deployment checks to ensure infrastructure code meets corporate governance standards before provisioning resources.

---
## 🖼️ Verification & Proof of Concept
*(Upload screenshots of your GitHub Actions pipeline workflow, security scan reports, and successful deployments)*
