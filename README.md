# Microsoft-AZ-700-Azure-Network-Engineer-Associate

# 🌐 AZ-700: Designing and Implementing Microsoft Azure Networking Solutions

![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat&logo=microsoftazure)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)
![Certification](https://img.shields.io/badge/Certification-AZ--700-blue?style=flat)


# Microsoft-AZ-700-Azure-Network-Engineer-Associate

## 🌐 AZ-700: Designing and Implementing Microsoft Azure Networking Solutions

### 📖 About This Repository
This repository documents my hands-on preparation for the **Microsoft Certified: Azure Network Engineer Associate (AZ-700)** exam. It serves as a comprehensive collection of Infrastructure-as-Code (ARM/Bicep) templates, architectural designs, scripts, and study notes.

---

## 🏆 Featured Project: Enterprise Hybrid Network & Load Balancing
*(Latest Lab - Completed)*

**Scenario:** Designed and implemented a robust **Hub & Spoke** topology simulating a connection between an On-Premise HQ (Istanbul) and Azure Cloud (France Central).

**🏗️ Architecture Highlights:**
* **Hybrid Connectivity:** Established **Site-to-Site VPN (S2S)** with **BGP enabled** for dynamic routing between simulated On-Premise and Azure Hub.
* **Network Topology:** Implemented **VNet Peering** between Hub and Spoke networks with Gateway Transit enabled.
* **High Availability:** Deployed a **Standard Load Balancer (Zone Redundant)** distributing traffic across web servers in different Availability Zones.
* **Security:** Applied Network Security Groups (NSGs) and validated traffic flow.
* **Automation:** Deployed IIS Web Servers via 'Run Command' scripts without manual login.

**📂 [Click here to view the ARM Templates & Topology Diagram](https://github.com/YVZYLDZ11/Microsoft-AZ-700-Azure-Network-Engineer-Associate/tree/Software/LABS/01-Hub-Spoke-Hybrid-Network)**

---

## 🎯 Learning Objectives & Lab Progress

Below is the list of key networking topics and labs. *Checked items (✅) indicate completed hands-on labs.*

### 🔌 Module 1: Design and Implement Core Networking Infrastructure
- [x] Design and Implement Virtual Networks (VNet) ✅
- [x] Configure VNet Peering & Service Chaining (Hub & Spoke) ✅
- [x] Manage IP Addressing (Public/Private) & Subnetting ✅
- [ ] Configure Azure DNS (Public, Private Zones & Resolver)

### 🌉 Module 2: Design and Implement Connectivity Services
- [x] Configure Site-to-Site (S2S) VPN & Point-to-Site (P2S) VPN ✅
- [x] Implement VNet-to-VNet Connectivity ✅
- [ ] Deploy and Manage Azure Virtual WAN (vWAN)
- [ ] Configure ExpressRoute & ExpressRoute Gateway

### ⚖️ Module 3: Design and Implement Application Delivery Services
- [x] Configure Azure Load Balancer (Public & Internal) ✅
- [ ] Implement Azure Application Gateway (WAF) *(Next Step)*
- [ ] Deploy Azure Front Door (Global Load Balancing)
- [ ] Configure Traffic Manager

### 🔒 Module 4: Design and Implement Private Access to Azure Services
- [ ] Configure Azure Private Link & Private Endpoints
- [ ] Implement Service Endpoints
- [ ] Configure VNet Integration for PaaS Services

### 🛡️ Module 5: Secure Network Connectivity to Azure Resources
- [ ] Implement Azure Firewall & Firewall Manager
- [ ] Configure Network Security Groups (NSGs) & ASGs
- [ ] Implement Web Application Firewall (WAF) Policies
- [ ] Monitor Networks with Network Watcher & Traffic Analytics

---

## 🛠️ Tools & Technologies
* **Cloud Platform:** Microsoft Azure
* **Infrastructure as Code:** ARM Templates, Terraform (Learning in progress)
* **Scripting:** PowerShell, Azure CLI
* **Monitoring:** Azure Monitor, Network Watcher

---

### 👨‍💻 Author
**YAVUZ YILDIZ** *Aspiring Cloud Architect | Azure Network Specialist* [LinkedIn Profile](https://www.linkedin.com/in/yavuzyildizyz/)
