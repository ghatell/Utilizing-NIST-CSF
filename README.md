# 🧠 Maturity Assessment – NeoSecure Labs  
**Utilizing NIST Cybersecurity Framework 2.0 (CSF)**

![ChatGPT Image Apr 9, 2025 at 04_52_45 PM](https://github.com/user-attachments/assets/477c555d-fd0c-4989-8f90-43b794b94eb6)

---

## 📘 Introduction

In this project, I conducted a cybersecurity posture assessment for **NeoSecure Labs**, a fictional mid-sized technology research company. Acting as a **Cybersecurity Consultant**, I evaluated their current controls, policies, and security practices against the **NIST Cybersecurity Framework 2.0 (CSF)**.

My goal was to identify deficiencies, align security outcomes to the CSF Core Functions, and provide actionable recommendations that would move NeoSecure from a **Tier 1 (Partial)** to a **Tier 3 (Consistent)** maturity profile.

---

## 🧩 What is NIST CSF 2.0?

The NIST Cybersecurity Framework is a flexible, risk-based approach to managing cybersecurity. Version 2.0 introduces six **Core Functions** that organize desired outcomes and control objectives:

| Function   | Purpose |
|------------|---------|
| **GOVERN** | Establish risk governance, roles, and responsibilities |
| **IDENTIFY** | Understand cybersecurity risk to assets and operations |
| **PROTECT** | Safeguard assets and systems with appropriate controls |
| **DETECT** | Identify cybersecurity events quickly and accurately |
| **RESPOND** | Contain, mitigate, and analyze incidents |
| **RECOVER** | Restore capabilities and communicate post-incident |

---

## 🏢 Assessment Scope: NeoSecure Labs

- Industry: R&D in biotechnology and embedded systems  
- Team: 100 employees, global operations  
- Tech stack: Microsoft 365, Azure Cloud, on-prem research servers  
- No formal CISO or security program in place  
- All cybersecurity responsibility sits with the IT Manager

---
## 📊 Profile Summary

The NIST CSF 2.0 includes a tiered maturity model that helps organizations assess the rigor and consistency of their cybersecurity governance and risk management practices. NeoSecure Labs was evaluated using these tiers to establish both its current and target cybersecurity posture.

![ChatGPT Image Apr 9, 2025 at 04_59_37 PM](https://github.com/user-attachments/assets/0af02d81-be97-4f43-b392-0fb0fdb230b4)

### 🧩 Current Profile – Tier 1: Partial

| Tier | Cybersecurity Risk Governance | Cybersecurity Risk Management |
|------|-------------------------------|-------------------------------|
| **Tier 1: Partial** | Application of the organizational cybersecurity risk strategy is managed in an ad hoc manner. There are no defined policies, and decision-making is reactive rather than strategic. Roles and responsibilities are either undocumented or informally assigned. Leadership involvement in cybersecurity is minimal or absent. | There is limited awareness of cybersecurity risks across the organization. Risk management is conducted irregularly and is not integrated into broader business processes. There are no formal procedures for identifying, assessing, or prioritizing cyber risks. Risk-related data is not shared effectively within the organization. Vendors and third-party risks are largely unaccounted for. |

---

### 🎯 Target Profile – Tier 3: Consistent

| Tier | Cybersecurity Risk Governance | Cybersecurity Risk Management |
|------|-------------------------------|-------------------------------|
| **Tier 3: Consistent** | The organization has documented and formalized cybersecurity governance. Policies, roles, and responsibilities are clearly defined and communicated across departments. Cybersecurity is embedded in decision-making processes at multiple levels. Risk oversight is included in strategic planning, and security objectives are aligned with business outcomes. Governance processes are regularly reviewed and updated. | Cybersecurity risk management practices are defined, implemented, and consistently followed across the organization. Risks are identified and prioritized using a repeatable process. Third-party risks are evaluated through a formal vetting program. Risk metrics are tracked, and findings inform control improvements and investment decisions. There is an established culture of risk awareness and accountability. |

---

> These tier definitions form the basis for NeoSecure Labs' security transformation roadmap. The goal is to evolve from a reactive posture to a

---

## 🧭 CSF Function Breakdown & Findings

### 🧑‍⚖️ GOVERN

| Finding | Status |
|--------|--------|
| No formal cybersecurity strategy or governance structure | ❌ |
| Roles and responsibilities not documented | ❌ |
| Risk tolerance not defined | ❌ |

<details close> 
<summary> <h3> 🗂️ NeoSecure Labs Current Status Report (Click to expand)</h3> </summary>

### 👥 Current NeoSecure Cybersecurity Team

- **IT Manager** – Oversees infrastructure, cloud services, and end-user support.
- **System Administrator** – Handles on-prem and Azure-based server management.
- **Junior Security Analyst** – Responds to user-reported security issues and performs basic log reviews.
- **Consultant (You)** – Recently onboarded to assess security maturity and guide GRC implementation.

---

### 🏛️ Organizational Governance

- The CEO has a clearly defined business vision and expansion goals.
- Cybersecurity responsibilities are loosely assigned to IT without formal documentation.
- No dedicated CISO, no documented cybersecurity strategy, and no oversight board involvement in risk discussions.

---

### 💻 Asset Management

- Assets tracked using an Excel spreadsheet listing serial numbers and models.
- No asset classification based on sensitivity or criticality.
- Primarily SaaS-based operations (Microsoft 365 and Salesforce); some research data resides in Azure Blob storage.
- Laptops are imaged using a Secure Operating Environment (SOE) but without tagging or agent-based tracking.

---

### 🔁 Business Continuity & Disaster Recovery

- Daily backups are performed via Azure Recovery Vault.
- Backups are tested quarterly but results are not documented.
- There is a general IT continuity plan, but no dedicated **cyber-specific** recovery procedures or tabletop testing.

---

### 🛠️ Vulnerability Management

- Tenable Nessus is available but used on an ad-hoc basis.
- No vulnerability management policy exists.
- High-risk findings persist for months due to lack of prioritization framework.
- No remediation tracking or escalation procedures are in place.

---

### ⚖️ Risk Management

- Financial risk is handled by a separate risk team; no collaboration with IT or security.
- No cyber risk register exists.
- No risk appetite or tolerance has been formally defined.
- No use of risk matrices or impact likelihood models.

---

### 🤝 Third Party Risk Management

- Contracts are reviewed by legal and procurement without IT/security input.
- No formal third-party security questionnaires or assessments.
- Vendors are not classified based on risk to the business or data sensitivity.

---

### 🔐 Identity and Access Management

- Microsoft Entra ID (formerly Azure AD) is used for user provisioning.
- No MFA enforced for admins or remote access.
- Admin accounts are shared among senior IT staff; no privileged access management.
- No regular access reviews or offboarding audits.
- VPN is used for remote access, but lacks conditional access policies.

---

### 🌐 Network Security

- Organization uses Fortinet Next Gen firewalls with predefined rules.
- Network diagrams exist but are not reviewed or updated routinely.
- VLAN segmentation exists but lacks policy-driven control.
- No microsegmentation or zero-trust implementation.
- Firewall logs are not actively monitored.

---

### 🏢 Physical Security

- Main office has badge entry and 24/7 camera surveillance.
- Server room access is logged manually.
- Contractors and visitors are not always escorted or logged digitally.
- Research lab has separate physical access control.

---

### 🗃️ Data Security

- No data classification policy or encryption at rest beyond cloud defaults.
- No Data Loss Prevention (DLP) tools deployed.
- USB device usage is unrestricted.
- Critical research data is stored in Azure but not segregated from less sensitive content.

---

### 📜 Policy

- Generic IT policy exists with minimal coverage on security controls.
- No formal **Information Security Policy**, **Acceptable Use Policy**, or **Data Classification Policy**.
- Employees have not acknowledged any cybersecurity policies in writing.

---

### 🔎 Detection & Response

- Microsoft Defender is deployed but used passively.
- No SIEM, SOAR, or central logging solution implemented.
- No documented incident response plan (IRP).
- No escalation or triage procedures exist.
- Incidents are handled ad hoc by IT as support tickets.

---

### 🧠 Security Awareness & Training

- Cybersecurity training is included in onboarding via a static video module.
- No periodic refresher training or phishing simulations.
- Executives and privileged users receive the same training as all other staff.
- Third-party personnel receive no cybersecurity guidance.

</details>

**Recommendation:**  
Establish a formal cybersecurity policy endorsed by leadership. Define governance roles (CISO, security champions, etc.) and integrate risk considerations into strategic planning.

---

### 🧱 IDENTIFY

| Finding | Status |
|--------|--------|
| Assets tracked manually, no classification based on criticality | ❌ |
| Third-party services used without risk vetting | ❌ |
| No formal risk management framework in place | ❌ |

**Recommendation:**  
Implement asset inventory with tagging for sensitivity (e.g., PII, R&D data). Develop a third-party risk management process and align risk identification with NIST 800-30.

---

### 🛡️ PROTECT

| Finding | Status |
|--------|--------|
| No MFA on remote access or administrative accounts | ❌ |
| Shared admin credentials in use | ❌ |
| No data loss prevention (DLP) strategy | ❌ |
| Staff cybersecurity training only at onboarding | ⚠️ |

**Recommendation:**  
Enforce MFA using Azure AD. Deploy PAM (Privileged Access Management). Initiate DLP controls within Microsoft 365. Launch quarterly phishing simulations and exec-level security training.

---

### 🔍 DETECT

| Finding | Status |
|--------|--------|
| No SIEM or log monitoring | ❌ |
| Relying solely on Microsoft Defender alerts | ❌ |
| No defined detection thresholds or incident classification | ❌ |

**Recommendation:**  
Deploy SIEM (e.g., Microsoft Sentinel or Splunk). Establish baselines for normal behavior. Develop detection playbooks linked to MITRE ATT&CK techniques.

---

### 🚨 RESPOND

| Finding | Status |
|--------|--------|
| No incident response plan (IRP) exists | ❌ |
| Response is reactive, uncoordinated | ❌ |
| No legal or regulatory response considerations | ❌ |

**Recommendation:**  
Develop a formal IRP using the SANS 6-step model. Train teams with tabletop exercises. Define escalation points and external communication channels.

---

### 🔁 RECOVER

| Finding | Status |
|--------|--------|
| Daily backups taken but not tested regularly | ⚠️ |
| No documented disaster recovery plan | ❌ |
| No formal post-incident lessons learned review | ❌ |

**Recommendation:**  
Test backups quarterly. Establish a recovery time objective (RTO) and recovery point objective (RPO) per asset class. Conduct post-incident analysis to drive improvement.

---

## 🧩 Frameworks & References

- 🔐 **NIST Cybersecurity Framework 2.0** – https://www.nist.gov/cyberframework
- 📘 **NIST SP 800-53 Rev 5** – Control implementation guidance
- 🔎 **MITRE ATT&CK** – Threat detection mapping
- ⚖️ **ISO/IEC 27001** – Governance and policy alignment

---

## 🧠 Final Thoughts

This project demonstrates the process of applying cybersecurity frameworks to assess real-world environments. By mapping technical and organizational gaps to CSF outcomes and supported control frameworks (like NIST 800-53 and ISO 27001), we can build a **measurable roadmap toward security maturity**.

---

> **Note**: This assessment was conducted in a simulated environment for educational and portfolio development purposes.
