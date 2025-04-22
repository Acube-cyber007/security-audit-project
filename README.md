# 🔐 Botium Toys Security Audit

## 📋 Project Overview

This project documents a security audit conducted on **Botium Toys**, a fictional retail and manufacturing company. The audit assessed Botium's IT and physical security controls, compliance posture, and data protection strategies.

The purpose of this audit is to identify vulnerabilities, evaluate existing controls, and provide actionable recommendations to improve Botium's cybersecurity maturity and compliance with industry standards such as **PCI DSS**, **GDPR**, and **SOC 2**.

---

## ✅ Audit Scope

- **Access Controls**
- **Network Security**
- **Physical Security**
- **Data Protection**
- **Compliance Readiness**
- **Disaster Recovery and Operational Security**

---

## 📊 Summary of Findings

| Control Area | Issue Identified | Explanation |
|--------------|------------------|-------------|
| Least Privilege | ❌ | All employees currently have access to customer data. Privileges need to be limited to reduce the risk of a breach. |
| Disaster Recovery Plan | ❌ | No formal recovery plans in place, which puts business continuity at risk in case of an incident. |
| Password Policy | ❌ | Weak or minimal password requirements could allow threat actors easy access to systems. |
| Separation of Duties | ❌ | The CEO manages daily operations and payroll — a potential fraud risk due to lack of role segregation. |
| Firewall | ✅ | An effective firewall is currently implemented with appropriate security rules. |
| Intrusion Detection System (IDS) | ❌ | No IDS present, making it difficult to detect real-time threats or breaches. |
| Backups | ❌ | Critical data is not consistently backed up, endangering continuity during disasters. |
| Antivirus | ✅ | Antivirus solutions are in place and regularly monitored. |
| Legacy System Maintenance | ⚠️ | Legacy systems are maintained but without clear schedules or intervention procedures. |
| Encryption | ❌ | No encryption is used to protect sensitive customer and payment data. |
| Password Management | ❌ | No password management system is in place to assist users or improve security. |
| Physical Security (Locks, CCTV, Fire Safety) | ✅ | Office and warehouse have adequate locks, CCTV, and fire detection systems. |

---

## 📜 Compliance Observations

**PCI DSS**
- 🔴 All employees have access to credit card data — violates best practices.
- 🔴 No encryption used for credit card transactions.
- 🔴 Weak password policies and no password management in place.

**GDPR**
- 🔴 No encryption for EU customer data.
- 🔴 Customer data not classified.
- ✅ 72-hour breach notification policy exists.
- ✅ Privacy policies enforced across teams.

**SOC 2**
- 🔴 Lack of proper access control and encryption weakens confidentiality.
- ✅ Data integrity measures are in place.
- 🔴 Sensitive data access is too broad and not role-restricted.

---

## 🛠️ Recommendations

1. **Implement Least Privilege and Role-Based Access Control (RBAC)**
2. **Develop a formal Disaster Recovery & Business Continuity Plan**
3. **Enforce strong password policies (length, complexity, expiration)**
4. **Deploy a centralized Password Management System**
5. **Introduce an Intrusion Detection System (IDS)**
6. **Encrypt all sensitive customer and financial data**
7. **Schedule and document regular maintenance for legacy systems**
8. **Backup critical data regularly and store off-site**
9. **Enforce Separation of Duties in operations and finance**
10. **Conduct periodic compliance audits and employee security training**

---

## 📁 Folder Structure

📦botium-toys-security-audit/ ┣ 📂screenshots/ ┣ 📂materials/ ┣ 📂report/ ┃ ┗ 📄final_audit_summary.pdf ┣ 📄README.md ┗ 📄controls_assessment.xlsx
---

## 📌 Usage

This project can be used as:
- A reference for conducting internal or academic cybersecurity audits.
- A sample case study for IT security training or certification practice.
- A framework to assess small or mid-sized businesses’ security postures.

---

## 📎 Author

**Abraham Alao**  
Cybersecurity Enthusiast | Biomedical Science Graduate | ISC2 Member  
📧 alaobayo5@gmail.com  
📍 Based in Nigeria  

---

## 📄 License

This project is provided for educational and demonstrative purposes. Feel free to fork, modify, and share.

