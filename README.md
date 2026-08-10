# 🔐 Cybersecurity Audit — Toyverse

> Professional cybersecurity audit project based on the NIST Cybersecurity Framework (NIST CSF), focused on risk assessment, security controls evaluation, compliance review, and security improvement recommendations.

---

## 📌 Project Overview

This project presents an internal cybersecurity audit for a fictional organization, **Toyverse**, designed to demonstrate practical security auditing skills.

The audit evaluates the organization's current security posture, identifies risks and control gaps, reviews compliance practices, and provides recommendations to reduce cybersecurity risk.

The project follows the **NIST Cybersecurity Framework (NIST CSF)** as the primary security framework.

---

## 🎯 Audit Objectives

The main objectives of this audit are to:

- Identify critical organizational assets;
- Assess cybersecurity risks;
- Evaluate existing security controls;
- Identify control gaps and vulnerabilities;
- Review compliance practices;
- Assess the protection of sensitive information;
- Evaluate risks related to business continuity;
- Recommend improvements to strengthen the organization's security posture.

---

## 🔍 Audit Scope

The audit covers the following areas:

- Internal network
- Employee devices
- Servers and systems
- Customer information
- Payment processing
- Physical security
- Data storage
- Legacy systems
- Security controls
- Compliance practices

---

## ⚠️ Risk Assessment

The assessment identified several security risks that could affect the confidentiality, integrity, and availability of organizational assets.

### Overall Risk Level

**High**

The organization presents significant risks due to gaps in security controls, access management, data protection, business continuity, and compliance practices.

Key risk areas include:

- Excessive access to sensitive information;
- Lack of least-privilege access;
- Lack of separation of duties;
- Insufficient encryption;
- Lack of disaster recovery planning;
- Lack of critical data backups;
- Weak password requirements;
- Lack of centralized password management;
- Lack of an intrusion detection system;
- Insufficient legacy-system management procedures.

---

## 🛡️ Security Controls Assessment

The audit evaluates administrative, technical, and physical/operational controls.

### Administrative / Managerial Controls

Examples include:

- Least privilege
- Password policies
- Disaster recovery plans
- Separation of duties

### Technical Controls

Examples include:

- Firewall
- Intrusion Detection System (IDS)
- Antivirus software
- Encryption
- Backups
- Password management

### Physical / Operational Controls

Examples include:

- Physical locks
- CCTV surveillance
- Fire detection and prevention

The complete assessment is available in:

📄 [`03-Controls-and-Compliance.md`](audit/03-Controls-and-Compliance.md)

---

## 📋 Compliance Review

The project reviews security practices related to:

- **PCI DSS** — Payment Card Industry Data Security Standard
- **GDPR** — General Data Protection Regulation
- **SOC** — System and Organization Controls

The assessment focuses on areas such as:

- Protection of sensitive information;
- Access control;
- Data confidentiality;
- Data integrity;
- Data availability;
- Encryption;
- Password security;
- Privacy procedures;
- Incident notification.

---

## 🚨 Key Findings

The audit identified several areas requiring improvement.

### High-Priority Findings

1. Implement least-privilege access.
2. Establish separation of duties.
3. Implement encryption for sensitive information.
4. Create disaster recovery procedures.
5. Implement regular backups of critical data.
6. Strengthen password requirements.
7. Deploy centralized password management.
8. Implement an intrusion detection system.
9. Establish formal procedures for legacy-system maintenance.
10. Improve data classification and access management.

---

## ✅ Recommendations

The recommended improvements focus on reducing organizational risk and strengthening the overall security posture.

Priority should be given to:

- Protecting sensitive customer information;
- Restricting access based on job responsibilities;
- Improving authentication and password management;
- Protecting critical data through encryption and backups;
- Establishing disaster recovery procedures;
- Improving monitoring and detection capabilities;
- Strengthening compliance practices;
- Regularly reviewing and updating security controls.

Detailed recommendations are available in:

📄 [`04-Recommendations.md`](audit/04-Recommendations.md)

---

## 📁 Project Structure

```text
toyverse-security-audit/
│
├── README.md
│
├── audit/
│   ├── Executive-Summary.md
│   ├── 02-Risk-Assessment.md
│   ├── 03-Controls-and-Compliance.md
│   └── 04-Recommendations.md
│
└── LICENSE
