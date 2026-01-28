# Project: Internal Cybersecurity Audit - Botium Toys

## 🎯 Executive Summary
I conducted an internal cybersecurity audit for Botium Toys to assess their current security posture as they prepare to scale their online presence. The audit focused on identifying gaps in controls and ensuring compliance with NIST CSF, PCI DSS, and GDPR standards.

## 🔍 Key Findings & Vulnerabilities
Based on the audit, the following critical vulnerabilities were identified:
* [cite_start]**Access Control Issues:** Currently, all employees have access to internal data, including sensitive credit card information (SPII)[cite: 95].
* [cite_start]**Weak Authentication:** Existing password policies are weak, and there is no centralized password management or Multi-Factor Authentication (MFA) in place[cite: 101, 102].
* [cite_start]**Encryption Gaps:** Data encryption procedures are not currently implemented for securing credit card transactions or stored data[cite: 59, 98].
* [cite_start]**Compliance Gaps:** The organization is currently non-compliant with GDPR (missing a 72-hour breach notification plan) and SOC (lack of established user access policies)[cite: 73, 81, 82].

## 💡 Top Recommendations
To patch these vulnerabilities, I recommended the following priority actions:
1. [cite_start]**Implement Least Privilege:** Restrict data access so employees only see what is necessary for their roles[cite: 97].
2. [cite_start]**Deploy Encryption:** Ensure all PII/SPII is encrypted at rest and in transit[cite: 98, 100].
3. [cite_start]**Strengthen Passwords:** Establish a Centralized Password Management System and enforce MFA[cite: 102].
4. [cite_start]**Legacy System Maintenance:** Regularize maintenance for legacy systems to prevent easy exploitation[cite: 103].

## 🛠️ Skills Applied
* [cite_start]Compliance Auditing (PCI DSS, GDPR, SOC) [cite: 50, 61, 77]
* [cite_start]Risk Assessment [cite: 2]
* NIST Cybersecurity Framework (CSF)
