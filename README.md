<div align="center">

<img src="./assets/banner.svg" width="100%" alt="Faizan Khan — Cloud Architecture & Security Control Plane" />

<br /><br />

<p align="center">
  <a href="https://faizankhank.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-faizankhank.vercel.app-0B1221?style=for-the-badge&logo=vercel&logoColor=38BDF8" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/faizan-khan-khaleel">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:faizankhanex@gmail.com">
    <img src="https://img.shields.io/badge/Email-faizankhanex%40gmail.com-1E293B?style=for-the-badge&logo=gmail&logoColor=38BDF8" alt="Email" />
  </a>
</p>

</div>

---

### How I Build & Secure Cloud Systems

I am a BCA student specializing in **Cloud Architecture & Cybersecurity** in Bengaluru. Instead of stopping at high-level diagrams, I treat every lab and application as a verifiable engineering artifact—pairing infrastructure deployments with identity governance, policy guardrails, and documented verification steps.

- **Infrastructure First, Hardened by Design:** Provisioning segmented Azure virtual networks, restrictive NSGs, SSH key-only Linux hosts, and reverse-proxied workloads.
- **Zero-Trust Identity & Secret Hygiene:** Eliminating hardcoded credentials by enforcing **Microsoft Entra ID**, **Managed Identities**, **Azure Key Vault**, and least-privilege **Azure RBAC**.
- **Policy-as-Code & Automation:** Authoring declarative infrastructure with **Terraform** and validating configurations against security benchmarks using **Checkov** and **Azure Policy**.

---

### Featured Architecture & Engineering Work

#### 1. [Togetherly Azure Platform](https://github.com/Faizankhan-cyber/togetherly-azure-platform) · `Flagship Cloud Engineering`
> Enterprise-grade, versioned Azure deployment hosting the Togetherly Workforce platform with documented architectural milestones and verification evidence.

- **V1 — Application Infrastructure:** Provisioned Ubuntu VM compute, VNet/subnet isolation, NSG perimeter rules, and Nginx reverse proxy hosting.
- **V2 — Identity, Secrets & Governance:** Migrated service authentication to System-Assigned **Managed Identity**, centralized secrets in **Azure Key Vault**, enforced granular **RBAC** role assignments, and applied **Azure Policy** guardrails.
- **Stack:** `Microsoft Azure` · `Entra ID` · `Managed Identity` · `Azure Key Vault` · `Azure RBAC` · `Azure Policy` · `Ubuntu` · `Nginx`

---

#### 2. [Microsoft Entra ID & Azure RBAC Lab](https://github.com/Faizankhan-cyber/microsoft-entra-id-azure-rbac-standalone) · `IaC & IAM Security`
> Declarative identity and access control lab built with Terraform and audited with static policy analysis.

- Automated lifecycle provisioning of Entra ID test identities, security groups, and least-privilege Azure RBAC role bindings.
- Integrated **Checkov** static code analysis to catch misconfigurations and overly permissive IAM rules before deployment.
- **Stack:** `Terraform` · `Microsoft Entra ID` · `Azure RBAC` · `Checkov` · `IAM`

---

#### 3. [BountyVault](https://github.com/Faizankhan-cyber/bountyvault) · [Live App](https://bountyvault-project.vercel.app/) · `Blockchain Escrow (Backend Lead)`
> Decentralized bounty escrow prototype on Algorand Testnet built with Team Block Rookies (Mini SIH 2026 — AlgoBharat Track).

- Engineered the backend API, relational state layer, and **Python ARC4** smart contract escrow lifecycle covering bounty funding, applicant selection, dispute resolution, and **Pera Wallet** transaction signing.
- **Stack:** `Algorand` · `Python ARC4` · `Node.js` · `Express` · `SQLite` · `React` · `TypeScript`

---

#### 4. [ThreatLens](https://github.com/Faizankhan-cyber/ThreatLens) · [Live App](https://threatlens-project.vercel.app/) · `Security Triage Tool`
> AI-assisted digital fraud and phishing triage web application (Internal SIH 2026).

- Enables users to inspect suspicious URLs, SMS/chat messages, emails, QR codes, and phone numbers with structured risk indicators and step-by-step response guidance.
- **Stack:** `React` · `TypeScript` · `Vite` · `Tailwind CSS`

---

<details>
<summary><strong>More Engineering Builds (Togetherly Workforce & Hardened Linux Lab)</strong></summary>
<br />

- **[Togetherly Workforce](https://github.com/Faizankhan-cyber/togetherly-workforce)** ([Live Demo](https://togetherly-tinyfish.vercel.app/)) — Full-stack workforce allocation engine matching engineers to projects using transparent, explainable scoring across skills, experience, and workload (`React`, `TypeScript`, `Supabase`, `Tailwind CSS`).
- **[Secure Linux Web Server on Azure](https://github.com/Faizankhan-cyber/secure-linux-web-server-azure)** — Hardened Ubuntu web server lab applying AZ-900 networking fundamentals: custom VNet, subnet isolation, inbound/outbound NSG filtering, key-based SSH hardening, and Nginx (`Azure VNet`, `NSG`, `Ubuntu`, `SSH`, `Nginx`).

</details>

---

### Core Stack & Tooling

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Cloud & Identity</strong><br /><br />
      <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" /><br />
      <img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Entra ID" /><br />
      <img src="https://img.shields.io/badge/Azure_RBAC_%26_Policy-005A9E?style=flat-square&logo=microsoftazure&logoColor=white" alt="RBAC" /><br />
      <img src="https://img.shields.io/badge/Azure_Key_Vault-1E3A8A?style=flat-square&logo=microsoftazure&logoColor=white" alt="Key Vault" /><br />
      <img src="https://img.shields.io/badge/Ubuntu_Linux_%26_Nginx-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Linux" />
    </td>
    <td width="33%" valign="top">
      <strong>IaC, Security & DevOps</strong><br /><br />
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" /><br />
      <img src="https://img.shields.io/badge/Azure_Bicep-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Bicep" /><br />
      <img src="https://img.shields.io/badge/Checkov_Static_Analysis-111827?style=flat-square&logo=checkmarx&logoColor=white" alt="Checkov" /><br />
      <img src="https://img.shields.io/badge/Zero_Trust_%26_STRIDE-B91C1C?style=flat-square&logo=shield&logoColor=white" alt="Zero Trust" /><br />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
    </td>
    <td width="33%" valign="top">
      <strong>Languages & Web</strong><br /><br />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /><br />
      <img src="https://img.shields.io/badge/Bash_%26_PowerShell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash & PowerShell" /><br />
      <img src="https://img.shields.io/badge/TypeScript_%26_JS-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /><br />
      <img src="https://img.shields.io/badge/React_%26_Node.js-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React & Node" /><br />
      <img src="https://img.shields.io/badge/SQLite_%26_SQL-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQL" />
    </td>
  </tr>
</table>

---

### Certifications & Verified Labs

- **Microsoft Certified: Security, Compliance, and Identity Fundamentals (`SC-900`)** — Active
- **In Progress:** Microsoft Azure Fundamentals (`AZ-900`) & Microsoft Azure Administrator (`AZ-104`)
- **Open Source:** Contributor — GirlScript Summer of Code (`GSSoC 2026`)
- **Labs & Simulations:** TryHackMe Pre-Security · Deloitte Cyber Job Simulation (Forage) · Cisco Introduction to Cybersecurity · Linux System Engineering & Virtualization (CentOS)
