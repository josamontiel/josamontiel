# Hi, I'm Joseph 👋

**Azure Security Engineer** focused on Microsoft Sentinel, the Defender suite, identity, and security-as-code. I work across enterprise client environments in a managed services model — building detections, automating response, and codifying security controls as infrastructure rather than clicking through portals.

Most of my public work is **security engineering expressed as code**: governance frameworks deployed as Azure Policy, Sentinel environments provisioned with Bicep, and detection content managed through CI/CD pipelines.

### 🔧 What I work with

**Detection & Response** — Microsoft Sentinel, Defender XDR, Defender for Endpoint, KQL, MITRE ATT&CK, SOAR / Logic Apps, threat hunting
**Cloud & IaC** — Azure, Bicep, ARM, Terraform, GitHub Actions CI/CD, policy-as-code, OIDC
**Identity** — Entra ID, Conditional Access, MFA, RBAC, least-privilege design
**Governance** — NIST CSF 2.0, NIST 800-53, CIS Controls, SOC 2, Zero Trust (SP 800-207)
**Scripting** — PowerShell, Bash, KQL

**Certifications:** SC-100 (Cybersecurity Architect Expert) · SC-200 (Security Operations Analyst) · CompTIA CySA+ · Security+ · Security Blue Team BTL1 · SC-900 · AZ-900

<p align="left">
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white" alt="Sentinel" />
  <img src="https://img.shields.io/badge/Bicep-00A4EF?style=flat&logo=microsoft&logoColor=white" alt="Bicep" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/KQL-0078D4?style=flat&logo=microsoft&logoColor=white" alt="KQL" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

### 📌 Selected projects

**[NIST-CSF-Azure-Policy](https://github.com/josamontiel/NIST-CSF-Azure-Policy)** — Governance-as-code
NIST CSF 2.0 implemented as enforceable Azure Policy, one custom policy per CSF function grouped into a parameterized initiative and deployed at subscription scope with Bicep. Uses an audit-first rollout to validate posture before enforcement, and ships a CSF-to-NIST 800-53 crosswalk for control traceability.

**[azure-policy-governance-iac](https://github.com/josamontiel/azure-policy-governance-iac)** — Terraform + CI/CD guardrails
A manually-maintained policy baseline converted into version-controlled Terraform, deployed through a GitHub Actions pipeline with plan-on-PR review, environment-gated apply, and OIDC federated auth (no long-lived secrets). Along the way I found and fixed three redundant policy assignments distorting compliance reporting and a provider case-sensitivity bug.

**[sentinel-bicep-deployment](https://github.com/josamontiel/sentinel-bicep-deployment)** — Sentinel as code
Subscription-scoped Bicep that provisions a complete Microsoft Sentinel environment from a single deployment — Log Analytics workspace with retention and ingestion cost controls, data connectors, Content Hub solutions, and workbooks. Compiles to ARM JSON, resolves Content Hub versions dynamically, and runs a validate → what-if → deploy pipeline for change control.

**[MDE-Multi-Framework-Dashboard](https://github.com/josamontiel/MDE-Multi-Framework-Dashboard)** — Compliance assessment tooling
Maps 347 Microsoft Defender for Endpoint controls across 10 frameworks (NIST 800-53, NIST CSF 2.0, SOC 2, PCI DSS, Zero Trust SP 800-207, and more), with embedded KQL and PowerShell validation for 71 controls, differential gap analysis, and PDF executive reporting.

---

### 📫 Connect

[LinkedIn](https://linkedin.com/in/josamontiel) · [Medium](https://medium.com/@josamontiel)

<img src="https://komarev.com/ghpvc/?username=josamontiel&color=blue&style=flat&label=Profile+views" alt="Profile views" />

*Always experimenting with detection engineering, security automation, and better ways to ship security controls as code.*
