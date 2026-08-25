# 02. Enterprise Identity & Access Management (IAM) Project

## 📌 Overview
This project establishes Zero Trust access control within Microsoft Entra ID by implementing Conditional Access, Privileged Identity Management (PIM), and passwordless Workload Identities (Managed Identities).

## 🛠️ Built With & Technologies Used
* **Microsoft Entra ID** (Users, Dynamic Groups, RBAC)
* **Conditional Access** (MFA Enforcement & Risk-Based Access)
* **Privileged Identity Management (PIM)** (Just-In-Time Elevation)
* **Managed Identities** (Azure Resource Authentication)

## 🎯 Key Implementation Steps
1. **Zero Trust Conditional Access:** Constructed policies requiring Multi-Factor Authentication (MFA) and blocking logins outside trusted geographical boundaries.
2. **Privileged Access Governance:** Configured PIM for Administrator roles requiring JIT activation, justification, and approval workflows.
3. **Managed Identities:** Configured System-Assigned Managed Identities for Azure resources to eliminate hardcoded credentials in application code.

---
## 🖼️ Verification & Proof of Concept
*(Upload screenshots of Conditional Access policy logic, PIM role elevation requests, and Managed Identity assignments)*
