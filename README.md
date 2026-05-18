# Harsh Kathwadia (HK)

Cloud / DevOps / Platform Engineer (Azure) — based in Toronto.  
I build secure, private-first Azure infrastructure with Terraform, with governance and observability baked in.

**Open to mid-level Cloud / DevOps / Platform Engineering roles.**  
- LinkedIn: [harsh-kathwadia](https://www.linkedin.com/in/harsh-kathwadia)
- GitHub: [Hktech-ops](https://github.com/Hktech-ops)

## What I do (focus areas)

- **Azure platform engineering:** Landing zones, subscriptions, management groups, policy, RBAC
- **Secure networking:** Hub-spoke, Azure Firewall, Bastion, NSGs, UDRs, private endpoints + private DNS
- **Observability by default:** Log Analytics, diagnostic settings, Azure Monitor Private Link Scope (AMPLS)
- **Delivery & automation:** Terraform modules, CI/CD pipelines, Docker, Kubernetes manifests, scripting

## Featured projects

### 1) Azure Landing Zone (Terraform) — enterprise-style baseline
Repo: [azure-landing-zone](https://github.com/Hktech-ops/azure-landing-zone)

A production-style Azure Landing Zone built with Terraform to demonstrate real platform engineering patterns:
- **Hub/Spoke networking** with **Azure Firewall** (DNAT + centralized egress), **Bastion**, NSGs, UDR forced tunneling
- **Private-first PaaS**: Key Vault, ACR, Storage, SQL using **Private Endpoints + Private DNS**
- **Governance**: management group hierarchy, policy initiatives (allowed locations, required tags, deploy diagnostic settings)
- **Observability**: centralized **Log Analytics**, private ingestion/query, **AMPLS**, and diagnostic settings across resources

### 2) Azure Labs — hands-on operational labs (AZ-104 style + real-world tasks)
Repo: [azure-labs](https://github.com/Hktech-ops/azure-labs)

A structured lab collection covering:
- VM operations and administration
- Web apps and deployment patterns
- Intersite connectivity and peering
- Virtual networking and segmentation
- Traffic filtering with NSGs/ASGs

### 3) Mini Projects — architecture patterns & simulations
Repo: [mini-projects](https://github.com/Hktech-ops/mini-projects)

Selected builds:
- **Highly Available, Scalable & Secure Web Architecture on Azure**  
  (VM Scale Sets + App Gateway + Firewall + hub/spoke + forced tunneling)  
  Link: [Project folder](https://github.com/Hktech-ops/mini-projects/tree/main/Highly%20Available%2C%20Scalable%20%26%20Secure%20Web%20Architecture)

- **Cloud Mesh lab (IIS + Apache across secure VNets)**  
  (bi-directional peering, Bastion, NSG hardening, automated web server installs)  
  Link: [Project folder](https://github.com/Hktech-ops/mini-projects/tree/main/Cloud%20Mesh:%20IIS%20and%20Apache%20across%20secure%20VNets)

- **Static website hosting on Azure Blob Storage** (foundation for CDN/Front Door hardening)  
  Link: [Project folder](https://github.com/Hktech-ops/mini-projects/tree/main/Static%20Website%20hosting%20on%20Blob%20Storage)

## App / CI/CD repos (work in progress, expanding documentation)

- Spring Boot app with containerization + manifests/pipeline files: [my-spring-boot-app](https://github.com/Hktech-ops/my-spring-boot-app)
- Containerized Java app with pipeline files (Docker/Jenkins/spec files): [java-app-containerized](https://github.com/Hktech-ops/java-app-containerized)
- Java app + Jenkins-oriented repo: [java-app-jenkins](https://github.com/Hktech-ops/java-app-jenkins)

## How I approach production infrastructure

- **Private-by-default** (avoid public exposure; use private endpoints + correct DNS)
- **Least privilege** via Entra ID groups + scoped RBAC
- **Central logging** and diagnostic settings as a baseline requirement
- **Cost guardrails** (quotas/retention/centralization) to prevent runaway spend
- Prefer **repeatable Terraform modules** over one-off scripts

## Currently improving

- CI/CD for Terraform (plan/apply gates, environment promotion)
- Stronger alerting & dashboards (KQL queries, actionable SLO-style alerts)
- More “workload realism” (apps consuming Key Vault/Storage privately)

---
If you're hiring for Cloud/DevOps/Platform Engineer roles feel free to reach out at harsh.hk.ca@gmail.com; I'd happy to walk through the landing zone design decisions and trade-offs.