# Harsh Kathwadia (HK)

Cloud / DevOps / Platform Engineer (Azure) — based in Toronto.  
I build secure, private-first Azure infrastructure with Terraform, with governance, observability and security baked in.

**Open to mid-level Cloud / DevOps / Platform Engineering roles.**  
- LinkedIn: [harsh-kathwadia](https://www.linkedin.com/in/harsh-kathwadia)
- GitHub: [Hktech-ops](https://github.com/Hktech-ops)

## What I do (focus areas)

- **Azure platform engineering:** Landing zones, subscriptions, management groups, policy, RBAC
- **Secure networking:** Hub-spoke, Azure Firewall, Bastion, NSGs, UDRs, private endpoints + private DNS
- **Workload platform:** AKS, App Service, containerized workloads using Docker
- **Observability:** Log Analytics, diagnostic settings, Azure Monitor Private Link Scope (AMPLS)
- **Delivery & automation:** Terraform modules, CI/CD pipelines (Azure DevOps + Jenkins), Docker builds, Kubernetes manifests, scripting

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

## Application delivery / CI/CD repos

I also maintain hands-on repos focused on application packaging, delivery pipelines, and deployment workflow patterns:

- **Spring Boot app with containerization, manifests, and pipeline files**  
  Repo: [my-spring-boot-app](https://github.com/Hktech-ops/my-spring-boot-app)

- **Containerized Java app with CI/CD-oriented files**  
  Docker, Jenkins, and deployment-related specs  
  Repo: [java-app-containerized](https://github.com/Hktech-ops/java-app-containerized)

- **Java app with Jenkins-focused pipeline workflow**  
  Repo: [java-app-jenkins](https://github.com/Hktech-ops/java-app-jenkins)

These repos reflect my growing DevOps focus around:
- containerizing workloads with **Docker**
- building CI/CD pipelines in **Jenkins** and **Azure DevOps**
- working with deployment manifests and automation patterns
- connecting infrastructure thinking with workload delivery

## How I approach production infrastructure

- **Private-by-default** (avoid public exposure; use private endpoints + correct DNS)
- **Least privilege** via Entra ID groups + scoped RBAC
- **Observability as baseline:** centralized logging, diagnostics, and platform visibility from day one
- **Central logging** and diagnostic settings as a baseline requirement
- **Cost guardrails** (quotas/retention/centralization) to prevent runaway spend
- Prefer **repeatable Terraform modules** over one-off scripts

## Currently improving

- CI/CD for Terraform with plan/apply gates and environment promotion
- End-to-end delivery workflows for apps: build, containerize, and deploy through pipelines
- Stronger alerting and dashboards using KQL and actionable SLO-style signals
- More workload realism, including apps consuming Key Vault and Storage privately
- Deeper AKS and App Service deployment patterns

---
If you're hiring for Cloud / DevOps / Platform Engineer roles, feel free to reach out at **harsh.hk.ca@gmail.com** — I’d be happy to walk through the landing zone design decisions, trade-offs, and delivery patterns behind these projects.
