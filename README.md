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

## 🔎 IDENTIFY – NIST CSF 2.0 Pass/Fail Table

<details close>
<summary><strong>▼ NIST Cybersecurity Framework 2.0 Pass/Fail Logs (Click to expand)</strong></summary>

### 📂 Asset Management

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| ID.AM-01 | Inventory of physical devices | Physical devices and systems are inventoried | 1. Do you maintain an up-to-date inventory or CMDB of all hardware assets?<br>2. Are inventories periodically reviewed and validated? | P | Spreadsheet with laptop serials and models; lacks IP tracking or automation |
| ID.AM-02 | Inventory of software platforms | Software platforms and SaaS apps are inventoried | 1. Do you track software (including SaaS) in your CMDB?<br>2. Are critical applications documented and updated regularly? | P | Horizon Labs critical SaaS noted; laptops imaged consistently |
| ID.AM-03 | Communication flows mapped | Communication and data flows are documented | 1. Are network diagrams up-to-date and reflect business data flows?<br>2. Are data flows between internal and external systems mapped? | P | Diagrams exist for core network; no formal data flow mapping yet |
| ID.AM-04 | External systems catalogued | Third-party systems are catalogued and managed | 1. Are third-party services included in asset inventory?<br>2. Are SaaS systems categorized by sensitivity and risk? | F | No classification for SaaS apps; TPS not under IT oversight |
| ID.AM-05 | Resources prioritized | Assets are prioritized by classification and criticality | 1. Is there an asset classification framework in use?<br>2. Are RTO/RPO metrics used to categorize impact? | F | No classification methodology or criticality labels in place |
| ID.AM-06 | Roles & responsibilities defined | Cybersecurity roles are documented for all stakeholders | 1. Are internal roles for cyber risk clearly defined?<br>2. Are third-party roles (vendors, MSPs) documented in security responsibilities? | F | No roles formally assigned; no cyber policy exists |

---

### 🌐 Business Environment

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| ID.BE-01 | Role in supply chain defined | Organizational role in broader supply chain is understood | 1. Has the org defined its cyber responsibilities in its supply chain?<br>2. Are suppliers categorized by risk/criticality? | F | No documentation or supplier mapping exists |
| ID.BE-02 | Critical infrastructure role identified | Org’s criticality within national/sector infrastructure is known | 1. Is the org considered critical infrastructure (e.g. energy, health)?<br>2. Is this noted in internal policy? | N | Org is not part of CI; not documented in InfoSec policy |
| ID.BE-03 | Mission & objectives informed by risk | Cybersecurity is aligned with business goals | 1. Are security objectives aligned with business objectives?<br>2. Are stakeholders aware of security’s role in business continuity? | P | Business strategy clearly documented; security not fully integrated yet |

### 🏛️ Governance

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| ID.GV-01 | Security policy established | Organizational information security policy is established | 1. Does the organization have an information security policy? | F | No InfoSec policy in place |
| ID.GV-02 | Roles aligned internally & externally | Roles and responsibilities are coordinated with stakeholders | 1. Are internal/external security roles documented and communicated? | F | No defined security roles, including third-party accountability |
| ID.GV-03 | Legal & regulatory cybersecurity requirements | Cybersecurity legal and regulatory responsibilities are documented | 1. Are privacy, legal, and security obligations clearly documented and reviewed? | F | No documentation of legal/regulatory cybersecurity obligations |
| ID.GV-04 | Governance processes address cyber risk | Cyber risk governance is documented and owned by leadership | 1. Does governance include cyber risk management processes?<br>2. Is there board-level oversight? | F | No board oversight or structured cyber risk governance |

---

### 📉 Risk Assessment

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| ID.RA-01 | Vulnerabilities identified | Asset vulnerabilities are identified and documented | 1. Are vulnerability scans conducted and documented? | P | Nessus scans run, but not part of a formal program |
| ID.RA-02 | Threat intelligence consumed | Threat info is received from external threat feeds | 1. Does the org use threat feeds or subscribe to threat intelligence sources? | F | No subscriptions or feeds configured |
| ID.RA-03 | Threats identified | Cyber threats are identified, assessed, and documented | 1. Are threat models or threat actor profiles maintained? | F | No formal threat tracking or modeling performed |
| ID.RA-04 | Business impacts assessed | Business impacts and likelihoods are used for risk decisions | 1. Are risks assessed using impact and likelihood? | F | Only financial risk assessments are conducted |
| ID.RA-05 | Risk = threat + vuln + impact | Risk is determined based on threats, vulnerabilities, and likelihoods | 1. Is risk calculated from likelihood and business impact?<br>2. Are risks prioritized and linked to business function? | F | Risk calculations not in place or documented |

---

### 📈 Risk Management Strategy

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| ID.RM-01 | Risk process established & endorsed | Risk management is owned and reviewed by leadership | 1. Has senior management approved a cyber risk management plan? | F | No formal approval or ownership from execs |
| ID.RM-02 | Risk tolerance documented | Risk appetite is clearly expressed in policy | 1. Has the organization defined and documented its risk tolerance? | F | No cyber risk tolerance or appetite defined |
| ID.RM-03 | Critical infra risk aligned to sector | Risk for critical infrastructure aligns with sector-level tolerance | 1. If CI, is the risk tolerance reviewed against industry or regulatory standards? | N | Not classified as CI, but no reference in policy if that changes |

</details>


**Recommendation:**  
Implement asset inventory with tagging for sensitivity (e.g., PII, R&D data). Develop a third-party risk management process and align risk identification with NIST 800-30.

# 📄 Risk Management Framework (NIST-Inspired)

This project uses a standardized 5x5 risk matrix to identify, score, and prioritize cybersecurity risks. This model is aligned with NIST SP 800-30 and ISO 27005 best practices.

---

## 📊 Risk Scoring Matrix

The risk score is calculated by **multiplying Likelihood x Impact**. Refer to the table below to determine the risk level.

| **Impact** \ **Likelihood** | **1 - Insignificant** | **2 - Minor** | **3 - Significant** | **4 - Major** | **5 - Severe** |
|-----------------------------|------------------------|----------------|----------------------|----------------|----------------|
| **5 - Almost Certain**      | Medium 5               | High 10        | Very High 15         | Extreme 20     | **Extreme 25** 🔴 |
| **4 - Likely**              | Medium 4               | Medium 8       | High 12              | Very High 16   | **Extreme 20** 🔴 |
| **3 - Moderate**            | Low 3                  | Medium 6       | Medium 9             | High 12        | Very High 15 🔴 |
| **2 - Unlikely**            | Very Low 2             | Low 4          | Medium 6             | Medium 8       | High 10 🟠 |
| **1 - Rare**                | Very Low 1             | Very Low 2     | Low 3                | Medium 4       | Medium 5 🟡 |

### 🌟 Risk Rating Key

| **Score** | **Risk Level**        | **Action**                          |
|-----------|-----------------------|-------------------------------------|
| 1–3      | Very Low / Low 🟢   | Acceptable; monitor periodically     |
| 4–8      | Medium 🟡             | Address with defined schedule       |
| 9–15     | High 🟠               | Mitigate with priority              |
| 16–25    | Very High / Extreme 🔴 | Immediate action required           |

---

## 📃 Risk Register

| **Risk ID** | **Risk Description** | **Asset Affected** | **Threat Actor** | **Vulnerability** | **Impact (1–5)** | **Likelihood (1–5)** | **Risk Score** | **Risk Level** | **Mitigation Strategy** | **Status** |
|------------|----------------------|--------------------|------------------|-------------------|--------------------|------------------------|---------------|----------------|--------------------------|-----------|
| RM-001     | Unauthorized access due to shared admin accounts | Active Directory | Insider | No MFA or PAM | 5 | 4 | 20 | **Extreme** 🔴 | Enforce MFA + deploy PAM | Open |
| RM-002     | Data exfiltration via USB | Endpoints | Insider | No DLP or USB restrictions | 4 | 3 | 12 | **High** 🟠 | Deploy DLP; block USB via GPO | Open |
| RM-003     | Exploitable unpatched vulnerabilities | Internal Systems | External attacker | No VM program | 5 | 5 | 25 | **Extreme** 🔴 | Implement VM policy and patch SLAs | In Progress |
| RM-004     | Delayed incident response | Entire org | External / Insider | No IR plan or escalation protocol | 4 | 3 | 12 | **High** 🟠 | Develop & test IR playbook | Open |
| RM-005     | Cloud data exposure | Azure / 365 | External attacker | No data classification or encryption | 5 | 2 | 10 | **High** 🟠 | Apply labels, enforce encryption, log access | Planned |
| RM-006     | Third-party vendor breach | Customer data | Vendor | No TPRM policy or monitoring | 4 | 3 | 12 | **High** 🟠 | Implement TPRM process and review clauses | Planned |
| RM-007     | Inadequate log monitoring | Firewalls / endpoints | APT / Insider | No SIEM or centralized logging | 4 | 4 | 16 | **Very High** 🔴 | Deploy SIEM, configure logging alerts | Open |

---

## 📓 Risk Review Cycle

| **Review Area** | **Frequency** | **Owner** |
|------------------|---------------|-----------|
| Risk Register Review | Quarterly | GRC Analyst |
| Risk Appetite / Tolerance | Annually | CISO / Security Governance |
| Mitigation Effectiveness | Bi-annually | Risk Owners / Control Leads |
| Vendor Risk Scores | Annually | Procurement / Security Team |

---

### 🛡️ PROTECT

| Finding | Status |
|--------|--------|
| No MFA on remote access or administrative accounts | ❌ |
| Shared admin credentials in use | ❌ |
| No data loss prevention (DLP) strategy | ❌ |
| Staff cybersecurity training only at onboarding | ⚠️ |

## 🛡️ PROTECT – NIST CSF 2.0 Pass/Fail Table

<details close>
<summary><strong>▼ NIST Cybersecurity Framework 2.0 Pass/Fail Logs (Click to expand)</strong></summary>

### 🔐 Access Control

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| PR.AC-01 | Identities and credentials managed | Identities and credentials are managed for authorized devices and users | 1. How are usernames and passwords managed?<br>2. Is there a password policy?<br>3. Is MFA used?<br>4. How is offboarding handled?<br>5. Are user access reviews conducted? | ❌ | Active Directory is used; complex password policy in place; no MFA; no offboarding process; no user reviews |
| PR.AC-02 | Physical access managed | Physical access to assets is managed and protected | 1. Are logs reviewed for entry/exit?<br>2. Is biometric/CCTV access used?<br>3. Are keys managed securely? | ❌ | No verified entry logs or biometric access, CCTV not documented |
| PR.AC-03 | Remote access managed | Remote access is secured | 1. Is 2FA required for VPN?<br>2. How are contractors granted access?<br>3. Are remote access logs reviewed? | ❌ | VPN used; no 2FA; access granted on request; separation of duties missing |
| PR.AC-04 | Least privilege & SoD | Access follows least privilege and separation of duties | ❌ | No formal access management program; duties partially separated but unverified |
| PR.AC-05 | Network segmentation | Network is segmented to reduce risk | ✅ | VLAN segmentation implemented |

---

### 📚 Awareness & Training

| **Sub-Category** | **Control Objective** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|----------------------|---------------|--------------|
| PR.AT-01 | Users trained | 1. Is regular security awareness training conducted?<br>2. Is onboarding training mandatory? | ❌ | Onboarding training only; no refresher or targeted content |
| PR.AT-02 | Privileged users trained | 1. Do privileged users receive enhanced training?<br>2. Is privileged access management in place? | ❌ | No PAM solution; no dedicated privileged training |
| PR.AT-03 | Third-party training | 1. Are third-party stakeholders given security training?<br>2. Are contracts reviewed for training clauses? | ❌ | No 3rd party training; procurement manages contracts only |
| PR.AT-04 | Executives trained | 1. Do executives receive cyber awareness briefings?<br>2. Are board responsibilities defined? | ❌ | No training or accountability at exec level |
| PR.AT-05 | Security roles known | 1. Are all staff aware of security expectations?<br>2. Are roles assigned and acknowledged? | ❌ | No documented roles or acknowledgments |

---

### 🔐 Data Security

| **Sub-Category** | **Control Objective** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|----------------------|---------------|--------------|
| PR.DS-01 | Data-at-rest protected | 1. Is at-rest data encrypted?<br>2. Is data classified and labeled?<br>3. Is DLP implemented? | ❌ | Azure default encryption only; no classification or DLP |
| PR.DS-02 | Data-in-transit protected | 1. Is data in transit encrypted?<br>2. Are USB policies in place?<br>3. Is DLP in use for exfiltration prevention? | ❌ | Transit encryption via Azure; no DLP or USB control |
| PR.DS-03 | Assets disposal managed | 1. Do you follow asset removal and disposal policies? | ❌ | No documented offboarding or disposal policies |
| PR.DS-04 | Availability maintained | 1. Do you maintain availability of critical systems?<br>2. Do you test DoS resilience? | ❌ | Cloud relies on Azure HA; no DoS protections verified |
| PR.DS-05 | Integrity ensured | 1. Do you monitor system integrity (e.g., firmware)? | ✅ | Default integrity checking in place |
| PR.DS-06 | Development integrity | 1. Is SaaS development covered by policy? | ✅ | Development is outsourced (SaaS); covered externally |

---

### 📜 Information Protection Processes & Procedures

| **Sub-Category** | **Control Objective** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|----------------------|---------------|--------------|
| PR.IP-01 | Secure configuration | 1. Is a secure baseline (e.g., SOE) defined for endpoints? | ✅ | SOE process used for Windows deployment |
| PR.IP-02 | SDLC in place | 1. Is there an SDLC for internal software? | ✅ | All apps are SaaS – not internally developed |
| PR.IP-03 | Change control | 1. Are changes documented and approved before implementation? | ✅ | Change control managed via SaaS vendor processes |
| PR.IP-04 | Backups maintained | 1. Are backups taken and tested regularly? | ✅ | Backups exist, tested periodically; protocols noted |
| PR.IP-05 | Physical security policy | 1. Are physical protections documented and enforced? | ❌ | No physical security policy exists |
| PR.IP-06 | Data destruction | 1. Are there secure data disposal procedures? | ❌ | No destruction policy; cloud-based data only |
| PR.IP-07 | Technology effectiveness | 1. Are security tools shared across peers or standardized? | ❌ | No sharing or assessment policy in place |
| PR.IP-08 | IR/DR plans implemented | 1. Do cyber response and BCDR plans exist and get tested? | ✅ | Basic plans exist and some testing performed |
| PR.IP-09 | HR security practices | 1. Are onboarding/offboarding practices defined and secure? | ❌ | Onboarding only; offboarding not defined |
| PR.IP-10 | VM program defined | 1. Is there a documented and enforced VM policy? | ❌ | Monitoring done, but no formalized program or SLA |

---

### 🔧 Maintenance

| **Sub-Category** | **Control Objective** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|----------------------|---------------|--------------|
| PR.MA-01 | Equipment maintained | 1. Are physical servers maintained with logs? | ❌ | No physical infrastructure in scope |
| PR.MA-02 | Remote maintenance logged | 1. Do third-party maintenance activities get logged? | ✅ | Maintenance is logged by SaaS/cloud provider |

---

### 🖥️ Protective Technology

| **Sub-Category** | **Control Objective** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|----------------------|---------------|--------------|
| PR.PT-01 | Audit logs maintained | 1. Are logs generated and reviewed?<br>2. Are logs protected from tampering? | ❌ | No SIEM, no log management program |
| PR.PT-02 | Removable media protected | 1. Are USB and external drives controlled? | ❌ | No policy on removable media use |
| PR.PT-03 | Least functionality enforced | 1. Are system functions minimized to essential needs? | ✅ | Cloud/SaaS architecture reduces exposed services |
| PR.PT-04 | Communication networks protected | 1. Is network traffic encrypted by default?<br>2. Are secure protocols enforced? | ❌ | No policies or validation for encryption standards |

</details>

**Recommendation:**  
Enforce MFA using Azure AD. Deploy PAM (Privileged Access Management). Initiate DLP controls within Microsoft 365. Launch quarterly phishing simulations and exec-level security training.

---

### 🔍 DETECT

| Finding | Status |
|--------|--------|
| No SIEM or log monitoring | ❌ |
| Relying solely on Microsoft Defender alerts | ❌ |
| No defined detection thresholds or incident classification | ❌ |

## 🕵️ DETECT – NIST CSF 2.0 Pass/Fail Table

<details close>
<summary><strong>▼ NIST Cybersecurity Framework 2.0 Pass/Fail Logs (Click to expand)</strong></summary>

### 🔎 Anomalies and Events

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| DE.AE-01 | Network baseline behavior established | A baseline of expected operations is established | 1. Do you use a SIEM?<br>2. Can you detect anomalies in network behavior? | ❌ | No SIEM in place |
| DE.AE-02 | Threat analysis performed | Detected events are analyzed to identify attack patterns | 1. Do you analyze threats based on collected logs and alerts? | ❌ | No analysis workflow or threat correlation |
| DE.AE-03 | Events correlated | Logs are aggregated and correlated from multiple sources | 1. Is a SIEM/EDR solution in place for data correlation? | ❌ | No SIEM/EDR solution |
| DE.AE-04 | Impact determined | Impact of detected events is understood | 1. Are events classified by severity (low/medium/high)? | ❌ | No classification or triage structure |
| DE.AE-05 | Alert thresholds defined | Alerting and escalation thresholds are defined | 1. Do you have defined escalation levels for different types of incidents? | ❌ | No escalation rules or thresholds documented |

---

### 📡 Security Continuous Monitoring

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| DE.CM-01 | Network monitoring in place | Network is monitored for potential security events | 1. Is traffic actively monitored for anomalies? | ❌ | No SIEM or IDS in place |
| DE.CM-02 | Physical environment monitored | Physical systems are monitored for cyber threats | ✅ | Physical security monitoring exists for facility |
| DE.CM-03 | Personnel activity monitored | Personnel actions (e.g. malicious behavior) are monitored | ✅ | Unusual activity monitored via Defender; no centralized logging |
| DE.CM-04 | Malicious code detection | Malicious software is detected and contained | ❌ | Defender in use but not enterprise-managed; coverage inadequate |
| DE.CM-05 | Mobile code monitored | Unauthorized mobile code is detected | ❌ | No anti-malware or endpoint detection system in place |
| DE.CM-06 | TPRM monitoring | Third-party service activity is monitored | ❌ | No TPRM or breach alerting mechanisms from third parties |
| DE.CM-07 | Unauthorized device monitoring | Unauthorized hardware/software is monitored | ❌ | No NAC, endpoint control, or USB management in place |
| DE.CM-08 | Vulnerability scans conducted | Vulnerabilities are scanned and managed | ❌ | Scans conducted ad hoc; no policy or defined cadence |

---

### 🧪 Detection Processes

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| DE.DP-01 | Detection roles defined | Roles and responsibilities for detection are clear | ❌ | No formal assignment of detection responsibilities |
| DE.DP-02 | Compliance with detection requirements | Detection complies with regulatory or contract requirements | ❌ | No mapping of detection controls to standards |
| DE.DP-03 | Detection is tested | Detection processes are regularly tested | ❌ | No drills or detection testing performed |
| DE.DP-04 | Escalation and comms defined | Events are communicated to the right stakeholders | ❌ | No communication plan or escalation matrix |
| DE.DP-05 | Continuous improvement | Detection processes are reviewed and improved | ❌ | No feedback loop or process reviews in place |

</details>

**Recommendation:**  
Deploy SIEM (e.g., Microsoft Sentinel or Splunk). Establish baselines for normal behavior. Develop detection playbooks linked to MITRE ATT&CK techniques.

---

### 🚨 RESPOND

| Finding | Status |
|--------|--------|
| No incident response plan (IRP) exists | ❌ |
| Response is reactive, uncoordinated | ❌ |
| No legal or regulatory response considerations | ❌ |

## 🔴 RESPOND – NIST CSF 2.0 Pass/Fail Table

<details close>
<summary><strong>▼ NIST Cybersecurity Framework 2.0 Pass/Fail Logs (Click to expand)</strong></summary>

### 📑 Response Planning

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RS.RP-01 | IR plan is established and maintained | Response processes and procedures are executed and maintained | 1. Do you have a documented incident response (IR) plan?<br>2. Is the plan used during real incidents? | ❌ | No IR policy or plan exists |

---

### 📣 Communications

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RS.CO-01 | Roles and escalation paths are defined | Response personnel know their roles and responsibilities | 1. Are escalation paths clearly defined?<br>2. Are contacts updated and tested? | ❌ | No escalation matrix defined |
| RS.CO-02 | Incident thresholds and reporting standards exist | Events are reported based on established thresholds | 1. Is there a documented process to report and categorize incidents? | ❌ | No process maturity or reporting logic |
| RS.CO-03 | Stakeholders are informed based on response plans | Info is shared with internal and external stakeholders appropriately | 1. Are law enforcement or external notifications defined in IR plan? | ❌ | No IR plan or stakeholder map exists |
| RS.CO-04 | Stakeholder coordination is outlined | Coordination with stakeholders is aligned with response plans | 1. Are communications steps to business, legal, media, etc. covered? | ❌ | No coordination framework documented |
| RS.CO-05 | Cyber threat intelligence shared externally | Voluntary threat sharing occurs with external stakeholders | 1. Do you participate in threat sharing (e.g. ISACs)? | ❌ | No cyber threat intel sharing program in place |

---

### 🔍 Analysis

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RS.AN-01 | Alerts are investigated | Notifications are analyzed | 1. Is there a formal workflow for investigating alerts? | ⚠️ | Antivirus used for alerting; no formal process |
| RS.AN-02 | Incident impact is determined | Impact and criticality of incidents is assessed | 1. Are impact/priority levels assigned and documented? | ❌ | No classification model used |
| RS.AN-03 | Forensics are performed | Capability to analyze and understand root cause | 1. Can your team perform digital forensics if needed? | ❌ | No forensics capability or tooling |
| RS.AN-04 | Incidents are categorized | Incidents are prioritized based on response plans | 1. Are incidents categorized by type, severity, or business impact? | ❌ | No structured response framework or matrix |
| RS.AN-05 | Incidents are contained | Response plans ensure incidents are contained quickly | 1. Do IR playbooks focus on isolation, containment, and eradication? | ❌ | No documented IR playbooks or strategy |

---

### 🧯 Mitigation

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RS.MI-01 | Incidents are mitigated | Threats are neutralized and recovery is initiated | 1. Are SANS-style IR steps implemented in policy/playbooks? | ❌ | No containment or mitigation process |
| RS.MI-02 | Vulnerabilities identified during response are addressed | New vulnerabilities are managed | 1. Is there a VM process to capture and fix vulnerabilities found during an incident? | ❌ | Qualys is available but not tied to IR workflow or policy |

---

### 🔁 Improvements

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RS.IM-01 | Lessons learned are captured | Response plans include post-incident review | 1. Are incidents followed by formal “lessons learned” reviews? | ❌ | No lessons learned or post-incident documentation process |
| RS.IM-02 | Response plans are updated | IR plans are regularly reviewed and updated | 1. Is there a scheduled process to revise IR plans based on new threats or incidents? | ❌ | IR strategy not tested or updated regularly |

</details>

**Recommendation:**  
Develop a formal IRP using the SANS 6-step model. Train teams with tabletop exercises. Define escalation points and external communication channels.

---

### 🔁 RECOVER

| Finding | Status |
|--------|--------|
| Daily backups taken but not tested regularly | ⚠️ |
| No documented disaster recovery plan | ❌ |
| No formal post-incident lessons learned review | ❌ |

## ✅ RECOVER – NIST CSF 2.0 Pass/Fail Table

<details close>
<summary><strong>▼ NIST Cybersecurity Framework 2.0 Pass/Fail Logs (Click to expand)</strong></summary>

### 🔄 Recovery Planning

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RC.RP-01 | Recovery plan tested | Recovery processes are maintained and executed during or after an event | 1. Do you have a documented disaster recovery plan?<br>2. Has it been tested recently? | ✅ | DR plan exists; testing occurs but limited documentation |

---

### ♻️ Improvements

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RC.IM-01 | Lessons learned incorporated | Recovery planning is improved with insights from past incidents | 1. Do your DR plans include a "lessons learned" step? | ✅ | Lessons learned considered post-incident |
| RC.IM-02 | Plans are updated regularly | Recovery strategies are continuously improved | 1. Do you regularly review and update your DR plans based on test results? | ✅ | Testing informs updates; not on fixed schedule |

---

### 📣 Communications

| **Sub-Category** | **Control Objective** | **Control Description** | **Questions to Ask** | **Pass/Fail** | **Comments** |
|------------------|------------------------|--------------------------|----------------------|---------------|--------------|
| RC.CO-01 | Public relations managed | PR strategies are integrated into recovery | 1. Is PR or crisis comms part of the DR plan?<br>2. Are steps in place to protect organizational reputation? | ❌ | Not formally documented in plans |
| RC.CO-02 | Reputation is restored | Org reputation is preserved or rebuilt post-incident | 1. Do you include mitigations for brand/image impact during recovery? | ❌ | Not formally addressed in DR strategy |
| RC.CO-03 | Recovery communication defined | Communication and escalation plans support recovery | 1. Are internal stakeholders and execs included in DR comms flow? | ❌ | Communication flow exists but is undocumented and untested |

</details>

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
