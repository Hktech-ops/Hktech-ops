# Harsh Kathwadia (HK)

**Cloud / DevOps / Platform Engineer - based in Toronto** 

I build production-grade, private-by-default Azure infrastructure using **Terraform** and **GitHub Actions**. My focus is on implementing the **Microsoft Cloud Adoption Framework (CAF)** with a strong emphasis on security, automation, and observability.

### 🌟 Featured Project: [Azure Landing Zone (CI/CD)](https://github.com/Hktech-ops/azure-landing-zone-cicd)
**Enterprise-grade Azure Baseline with Automated Governance & Security Gates**

This is my flagship project demonstrating a complete platform engineering lifecycle.
- **Advanced CI/CD:** Orchestrated a GitHub Actions pipeline with **7 quality gates**, including **Checkov** (Security), **TFLint** (Linter), and **Infracost** (FinOps).
- **Secretless Auth:** Implemented **OpenID Connect (OIDC)** for federated identity, eliminating the need for long-lived GitHub secrets.
- **Zero-Trust Network:** Centralized **Hub-Spoke** architecture utilizing **Azure Firewall (Standard)**, Bastion, and forced tunneling via UDRs.
- **Private-First PaaS:** Secured all data services (SQL, Storage, Key Vault, ACR) via **Private Endpoints** and **Private DNS Zones**.
- **Governance at Scale:** Automated Management Group hierarchy and **Azure Policy** initiatives for region restrictions and diagnostic enforcement.

---

### 🔧 What I Do (Core Competencies)

- **Azure Platform Engineering:** CAF Landing Zones, Management Groups, Policy-as-Code, Entra ID RBAC.
- **Secure Networking:** Hub-Spoke, Azure Firewall, Bastion, NSGs, UDRs, Private Link / Endpoints.
- **Workload Platforms:** AKS, App Service (VNet Integrated), Containerized workloads (Docker).
- **Observability:** Log Analytics Workspace, KQL, Diagnostic Settings, **AMPLS**, Azure Monitor Alerting.
- **IaC & Automation:** Modular Terraform, GitHub Actions (OIDC), Infracost (Cost Analysis), TFLint.

---

### 📂 Other Key Repositories

#### 🛠️ [Azure Labs](https://github.com/Hktech-ops/azure-labs)
*Hands-on operational labs covering production-style administration:*
- VNet Peering & Intersite connectivity.
- Traffic filtering with NSGs/ASGs and forced tunneling.
- Web app deployment patterns and VMSS operations.

#### 🏗️ [Mini Projects](https://github.com/Hktech-ops/mini-projects)
*Architecture patterns & simulations:*
- **[Highly Available & Secure Web Architecture](https://github.com/Hktech-ops/mini-projects/tree/main/Highly%20Available%2C%20Scalable%20%26%20Secure%20Web%20Architecture):** Scale Sets + App Gateway + Firewall + Hub/Spoke.
- **[Cloud Mesh Lab](https://github.com/Hktech-ops/mini-projects/tree/main/Cloud%20Mesh:%20IIS%20and%20Apache%20across%20secure%20VNets):** IIS + Apache deployment across hardened secure VNets.

#### 🚀 [Application Delivery & CI/CD](https://github.com/Hktech-ops/my-spring-boot-app)
*Workload packaging and pipeline patterns:*
- Containerizing Spring Boot & Java apps with **Docker**.
- Build/Deploy pipelines using **Jenkins**, **GitHub Actions**, and **Azure DevOps**.
- Kubernetes manifests and automated deployment workflows.

---

### 🧠 My Engineering Philosophy

- **Private-by-Default:** If it doesn’t need a public IP, it doesn't have one. Period.
- **Identity over Secrets:** Preferring **Managed Identities** and **Entra-only authentication** to eliminate credential sprawl.
- **Observability as a First-Class Citizen:** Centralized logging and diagnostic settings are baked into the Terraform modules, not an afterthought.
- **FinOps Integration:** Cost is an engineering metric. I integrate Infracost into PRs to ensure visibility on spend before deployment.

---

### 📫 Connect with Me
- **LinkedIn:** [harsh-kathwadia](https://www.linkedin.com/in/harsh-kathwadia)
- **Email:** [harsh.hk.ca@gmail.com](mailto:harsh.hk.ca@gmail.com)
- **GitHub:** [Hktech-ops](https://github.com/Hktech-ops)

---
*Open to mid-level Cloud / DevOps / Platform Engineering roles.*
