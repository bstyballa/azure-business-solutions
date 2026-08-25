# 03. Hub-and-Spoke Network Security Architecture

## 📌 Overview
This project implements an enterprise Hub-and-Spoke network security pattern in Azure, routing all inter-subnet and internet traffic through Azure Firewall, Network Security Groups (NSGs), and Private Endpoints.

## 🛠️ Built With & Technologies Used
* **Virtual Network Peering** (Hub-and-Spoke Architecture)
* **Azure Firewall** (Network & Application Firewall Rules)
* **Network Security Groups (NSGs)** (Micro-segmentation)
* **Private Endpoints & Private DNS** (Private Service Connectivity)

## 🎯 Key Implementation Steps
1. **Topology Deployment:** Built a central Hub VNet (housing Azure Firewall) peereed with isolated Spoke VNets (workloads).
2. **Traffic Routing (UDRs):** Configured User-Defined Routes (UDRs) forcing all spoke traffic through the Hub Firewall.
3. **Private Connectivity:** Secured storage resources using Private Endpoints to ensure database and file traffic never traverses the public internet.

---
## 🖼️ Verification & Proof of Concept
*(Upload screenshots of your network topology diagram, Azure Firewall rules, and routing tables)*
