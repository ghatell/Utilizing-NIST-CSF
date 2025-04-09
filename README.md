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
<summary> <h3> 🗂️ NeoSecure Labs - Current Status Report (Click to expand)</h3> </summary>

## 🧾 NeoSecure Labs – Current Cybersecurity Status

| **Category**                        | **Findings**                                                                                                                                                    |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Cybersecurity Team**             | - No dedicated CISO<br>- Security handled by IT Manager, SysAdmin, Junior Analyst<br>- Consultant (You) onboarded for assessment & roadmap planning            |
| **Organizational Governance**      | - No documented cybersecurity roles or strategy<br>- Security not discussed at the leadership level<br>- No executive oversight on risk                         |
| **Asset Management**               | - Assets tracked in Excel<br>- No criticality or sensitivity classification<br>- Laptops imaged via SOE, but no endpoint agents or tagging                      |
| **Business Continuity & DR**       | - Backups via Azure Recovery Vault<br>- No cyber-specific DR tabletop testing<br>- Recovery testing not formally documented                                     |
| **Vulnerability Management**       | - Nessus used ad-hoc<br>- No VM policy or SLA for patching<br>- High vulnerabilities persist with no prioritization matrix                                      |
| **Risk Management**                | - No cyber risk register<br>- Financial risks managed separately<br>- No risk appetite or matrix for IT/security                                                |
| **Third Party Risk Management**    | - Contracts reviewed without IT/security input<br>- No vendor questionnaires or tiering<br>- No third-party tracking or risk scoring                           |
| **Identity & Access Management**   | - No MFA for admin or remote access<br>- Shared admin accounts<br>- No PAM solution<br>- VPN used with basic policies<br>- No access review processes           |
| **Network Security**               | - Fortinet firewalls in place<br>- VLAN segmentation exists<br>- Diagrams outdated and rarely reviewed<br>- No active log monitoring or segmentation policies   |
| **Physical Security**              | - Badge entry and cameras in place<br>- Manual server room access logs<br>- No escort policy for visitors<br>- Research labs have isolated access controls     |
| **Data Security**                  | - No DLP or USB restrictions<br>- No encryption beyond cloud defaults<br>- Critical data co-mingled with general data in Azure                                  |
| **Policies & Governance Docs**     | - One generic IT policy exists<br>- Missing InfoSec, AUP, data classification, and incident response policies<br>- No policy acknowledgment from employees      |
| **Detection & Response**           | - No SIEM or centralized logging<br>- No incident response plan<br>- Defender alerts handled manually by IT<br>- No defined escalation or containment procedures |
| **Security Awareness Training**    | - Onboarding-only video training<br>- No refresher courses<br>- No phishing simulations<br>- No tailored training for execs or third parties                    |


</details>

<details close> 
<summary> <h3> 🎯 NeoSecure Labs – Target Cybersecurity State (Tier 3: Consistent) (Click to expand)</h3> </summary>

| **Category**                        | **Target State (Tier 3 – Consistent Maturity)**                                                                                                                   |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Cybersecurity Team**             | - Security governance led by a designated CISO or Cybersecurity Officer<br>- Security team roles defined (Governance, Blue Team, IAM, Risk)<br>- Regular reporting to leadership |
| **Organizational Governance**      | - Documented cybersecurity strategy approved by leadership<br>- Roles & responsibilities defined across departments<br>- Security included in strategic decisions |
| **Asset Management**               | - Centralized CMDB with agent-based asset discovery<br>- Assets classified by sensitivity & business impact<br>- Real-time asset visibility                        |
| **Business Continuity & DR**       | - Documented cyber-specific DR plan<br>- Quarterly DR testing with results documented<br>- Business-impact-based prioritization of recovery efforts                |
| **Vulnerability Management**       | - Formal VM program with risk-based prioritization (CVSS + asset value)<br>- SLA-backed remediation timelines<br>- Continuous scanning with Tenable or similar     |
| **Risk Management**                | - Cyber risk register maintained and updated quarterly<br>- Organization-wide risk matrix with defined impact/likelihood<br>- Risk appetite defined and tracked   |
| **Third Party Risk Management**    | - Vendors tiered by criticality and assessed annually<br>- TPRM process integrated with procurement<br>- Security clauses included in contracts                    |
| **Identity & Access Management**   | - MFA enforced org-wide (especially for admins)<br>- PAM system implemented (e.g., CyberArk)<br>- Quarterly access reviews and automated offboarding               |
| **Network Security**               | - Microsegmentation applied to critical systems<br>- Real-time monitoring of firewall activity via SIEM<br>- Updated and reviewed network diagrams and access logs |
| **Physical Security**              | - Role-based access to server rooms & labs<br>- Digital entry/exit logging with video audit trail<br>- Contractor escort and clearance validation processes        |
| **Data Security**                  | - DLP in place for endpoint & cloud platforms<br>- Encryption at rest and in transit enforced<br>- Data tagged by classification level and access control enforced |
| **Policies & Governance Docs**     | - Information Security Policy, AUP, DLP, and IRP in place<br>- Employees acknowledge policies annually<br>- Regular policy review/update cycle (e.g., every 12 months) |
| **Detection & Response**           | - SIEM deployed (e.g., Microsoft Sentinel)<br>- Detection rules mapped to MITRE ATT&CK<br>- Documented and tested Incident Response Plan (IRP)<br>- Ticketing and escalation processes defined |
| **Security Awareness Training**    | - Role-based training programs (end-users, execs, IT)<br>- Phishing simulations conducted quarterly<br>- Third-party awareness and compliance requirements enforced |

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
