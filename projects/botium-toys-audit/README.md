# Project: Internal Cybersecurity Audit - Botium Toys

## 📌 Project Overview
This project consists of a comprehensive internal cybersecurity audit for **Botium Toys**, a fictional company preparing to scale its online retail operations. The audit was conducted to identify vulnerabilities, assess risks, and ensure compliance with international security standards such as NIST CSF, PCI DSS, and GDPR.

## 🎯 Scope and Goals
* **Scope:** The entire security program, including employee equipment (desktops, laptops, smartphones), the internal network, and data retention systems.
* **Goals:** Assess existing assets, complete a controls/compliance checklist, and provide recommendations to improve the company's security posture.

## ⚠️ Risk Assessment Findings
* **Risk Score:** **8 / 10** (High)
* **Primary Risks:** Inadequate management of assets and a lack of proper controls to meet U.S. and international regulations.
* **Impact of Loss:** Rated as **High** regarding potential fines from governing bodies due to missing critical data security practices.

## 🔍 Critical Gaps & Vulnerabilities
Based on the audit, the following issues were identified:
* **Access Control:** No "Least Privilege" or "Separation of Duties" policies are currently in place. All employees currently have access to sensitive PII/SPII and cardholder data.
* **Data Security:** Encryption is not used for credit card information processed or stored locally. 
* **Monitoring:** While a firewall and antivirus are present, there is **no Intrusion Detection System (IDS)** installed.
* **Resilience:** There are currently **no disaster recovery plans** or critical data backups.
* **Authentication:** Password policies are nominal and do not meet modern complexity requirements. There is no centralized password management or Multi-Factor Authentication (MFA).

## 💡 Recommended Security Controls
To ensure a secure transition to the large-scale online market, the following priority actions were recommended:
1. **Implement Least Privilege & Separation of Duties:** Restrict access to sensitive data to authorized users only.
2. **Deploy Encryption:** Use data encryption for all credit card transactions and stored PII/SPII.
3. **MFA and Centralized Passwords:** Establish a system for Multi-Factor Authentication and stronger password complexity.
4. **Regular Maintenance:** Create a schedule for monitoring and maintaining legacy systems to prevent exploitation.

## 🛠️ Skills & Frameworks Applied
* **NIST Cybersecurity Framework (CSF):** Focused on the "Identify" and "Protect" functions.
* **Compliance Standards:** Evaluated against PCI DSS, GDPR, and SOC (Type 1 & 2).
* **Technical Auditing:** Risk assessment, asset classification, and security control identification.
