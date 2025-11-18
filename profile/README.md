# KINGDOM TECH  
### Secure Cloud • DevSecOps • Platform Engineering  
**Specializing in FedRAMP High, DoD IL5, and GovCloud workloads**

---

## Who We Are

**Kingdom Tech** is a mission-driven platform engineering company focused on building **secure, automated, audit-ready cloud platforms** for organizations operating in regulated or high-assurance environments.

We design systems that meet the standards of:

- **FedRAMP High**
- **DoD IL4/IL5/IL6**
- **NIST 800-53**
- **Zero Trust Architectures**
- **Modern DevSecOps frameworks**
- **Supply-Chain Security / SLSA**

Our engineering approach combines **security, automation, reliability, and clarity** to deliver platforms that scale in both capability and compliance.

---

# The Kingdom Tech Secure Platform Stack

Kingdom Tech provides a 3-pillar engineering model used to bootstrap or modernize secure cloud platforms:

---

## 1. Secure Image Supply Chain  
**Digest-verified mirroring of vendor images → AWS ECR (GovCloud / IL5)**  
Prevents tag drift, poisoned registries, and mitigates supply-chain compromise.

📌 Repo:  
https://github.com/kingdom-technology/secure-image-mirror

---

## 2. Continuous Security & Compliance Automation  
Nightly and on-demand scanning using:

- AWS **Inspector2**
- **Trivy** (containers & filesystem)
- **OpenSCAP** (CIS Benchmarks)

Outputs are stored in **KMS-encrypted S3** for audit readiness and Continuous Monitoring alignment.

📌 Repo:  
https://github.com/kingdom-technology/security-compliance-pipelines

---

## 3. Hardened Helm Chart Library  
Security-focused Helm chart templates for vendor and internal applications, featuring:

- Least-privilege defaults  
- Non-root containers  
- Read-only filesystems  
- ECR-only image policies  
- Production-ready probes and resources  
- Config separation for staging, prod, and IL5

📌 Repo:  
https://github.com/kingdom-technology/hardened-helm-charts

---

# 🛠 What We Build

### DevSecOps / Cloud Engineering
- Secure CI/CD pipelines  
- GitHub Actions, CircleCI, GitOps workflows  
- Terraform infrastructure (GovCloud, commercial AWS)  
- Deployment automation at scale  

### Kubernetes Platform Engineering
- EKS platform builds (staging → prod → IL5)  
- Hardened Helm charts  
- Multi-tenant / multi-service architecture  
- Observability & audit logging patterns  

### Security & Compliance
- FedRAMP High / IL5 readiness  
- Secure software supply chain (SLSA, OCI)  
- Inspector2, Trivy, OpenSCAP integration  
- Deterministic deployments & artifact verification  
- Continuous Monitoring automation  

---

# Featured Open-Source Projects

| Project | Description | Link |
|--------|-------------|------|
| **Secure Image Mirror** | Deterministic vendor image mirroring with digest verification → AWS ECR. | https://github.com/kingdom-technology/secure-image-mirror |
| **Security & Compliance Pipelines** | Inspector2, Trivy, and OpenSCAP pipelines for automated vulnerability & CIS scanning. | https://github.com/kingdom-technology/security-compliance-pipelines |
| **Hardened Helm Charts** | Secure, IL5-ready Helm patterns for vendor and internal services. | https://github.com/kingdom-technology/hardened-helm-charts |

---

# Our Mission

To build cloud platforms that are:

- **Secure by design**
- **Automated in operation**
- **Compliant with confidence**
- **Scaled through excellence**

And to support organizations with solutions that reflect **integrity, stewardship, and Kingdom-minded leadership**.

---

# Consulting & Engagement

If you’re looking to:

- Harden workloads for GovCloud / IL5  
- Modernize legacy vendor services  
- Build secure CI/CD pipelines  
- Establish a compliant Kubernetes platform  
- Strengthen your supply chain security posture  

Kingdom Tech can help.

Engagement options and business contact are coming soon.  
Until then, feel free to open an issue on any repo.

---

# KINGDOM TECH  
**Secure Platforms. Automated Delivery. Compliant by Default.**
