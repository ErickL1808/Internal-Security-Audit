# 🔐 Internal Security Audit Project

### 📘 Overview  
This project showcases a **mock internal security audit** conducted as part of the **Google Cybersecurity Professional Certificate**.  
The audit evaluates internal controls, data protection, encryption practices, and compliance with frameworks such as **NIST CSF, PCI DSS, SOC type 1 & 2, and GDPR**.

---

### 🎯 Objectives  
- Evaluate organizational security posture through an internal audit  
- Assess compliance with security frameworks and best practices  
- Identify gaps in access control, encryption, and disaster recovery  
- Recommend improvements to strengthen information security and business continuity  

---

### 🧠 Key Controls Assessed  
| Control Area | Status | Summary |
|---------------|---------|----------|
| Least Privilege | ❌ Not enforced | All employees have access to customer data |
| Separation of duties | ❌ Not enforced | Reduce fraud & unathorized access to critical data |
| Disaster Recovery | ❌ Missing | No recovery plan implemented |
| Password Policy | ⚠️ Weak | Minimal requirements allow potential compromise |
| Password management | ❌ Missing | Minimal requirements allow potential compromise |
| Firewall | ✅ In place | Blocks network traffic based on defined set of security rules |
| IDS/IPS | ❌ Absent | No system in place to detect intrusions |
| Backups | ❌ Missing | Backups are not in place & critical data is at risk |
| Encryption | ❌ Missing | Confidential data is not encrypted, sensitive data is vulnerable |
| Antivirus | ✅ Implemented | Installed and monitored by the IT department |
| Data Integrity | ✅ In place | IT ensures consistency and validation |

---

### 🧩 Frameworks & Compliance Reviewed  
- **NIST Cybersecurity Framework (CSF)**  
- **PCI DSS v4.0**  
- **SOC Type 1 & 2 Principles**  
- **GDPR**  

---

### 🔍 Tools & Skills Used  
- Risk assessment & control analysis  
- NIST CSF framework application  
- Compliance evaluation (PCI DSS, GDPR)  
- Technical documentation and reporting  
- Adobe Acrobat (PDF/Word/Google Docs) 

---

### 📈 Key Recommendations  
1. **Access Control & Identity Management**  
   - **Implement Active Directory / Entra ID** <br>
(Centralized user & device management, user permissions, security groups & password policy enforcement) 
   - **Enforce Role-Based Access Control (RBAC)**  
   - **Enable Multi-Factor Authentication (MFA)** <br>
   
**PCI DSS v4.0** requires **MFA** for all personnel with adminstrative access & anyone accessing the **Cardholder Data Environment (CDE)**. As well for SOC 2 (Trust Services Criteria), MFA is expected under **"Security"** & **"Confidentiality"** principles for protecting access to sensitive data  

2. **Data Protection & Encryption**  
   - **Encrypt all sensitive data (PII/SPII, payment info)**<br>
(Encrypt both ***at rest*** and ***in transit*** using **AES-256** or equivalent standards)

   - **Use SSL/TLS for data in transit** <br>
(This **protects data** transmitted between **systems & applications**)

   - **Implement tokenization**<br>
(Introduce **tokenization** for PCI DSS compliance)

3. **Backup & Disaster Recovery**  
   - Implement daily incremental and weekly full backups  
   - Use cloud-based storage (Azure Backup or AWS Glacier)  
   - Test restoration quarterly to verify integrity  

4. **Monitoring & Threat Detection**  
   - Deploy IDS/IPS and centralized logging (SIEM)  
   - Perform regular vulnerability assessments  

5. **Policy & Governance**  
   - Develop and enforce clear security policies  
   - Conduct ongoing employee security awareness training  

---

### 📄 Project File  
📁 [Download Full Audit Report (PDF)](./InternalSecurityAudit_EL.pdf)

---

### 🧭 Outcome  
This project demonstrates professional-level auditing, risk identification, and control recommendations.  
It showcases practical understanding of **how cybersecurity professionals assess, document, and improve** an organization’s security posture.

---

### 👨‍💻 Author  
**Erick Leon**  
Google Cybersecurity Professional Certificate Graduate  
💼 IT Professional  
🔗 [LinkedIn](https://www.linkedin.com/in/
