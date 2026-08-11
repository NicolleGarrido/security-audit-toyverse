# Security Controls and Compliance Assessment

## Audit Objective

This assessment evaluates the security controls and compliance practices currently implemented by Botium Toys.

The assessment is based on the organization's documented security posture, risk assessment, and identified assets.

---

# 1. Security Controls Assessment

| Control | Category | Status | Assessment |
|---|---|---|---|
| Least Privilege | Administrative | ❌ Not Implemented | Access is not restricted according to job responsibilities. |
| Disaster Recovery Plans | Administrative | ❌ Not Implemented | No disaster recovery plan is currently in place. |
| Password Policies | Administrative | ⚠️ Needs Improvement | A password policy exists, but its requirements are insufficient. |
| Separation of Duties | Administrative | ❌ Not Implemented | Separation of duties has not been implemented. |
| Firewall | Technical | ✅ Implemented | A firewall is configured to filter network traffic according to security rules. |
| Intrusion Detection System (IDS) | Technical | ❌ Not Implemented | No IDS is currently installed. |
| Backups | Technical | ❌ Not Implemented | Critical data is not currently backed up. |
| Antivirus Software | Technical | ✅ Implemented | Antivirus software is installed and regularly monitored. |
| Legacy System Monitoring | Technical / Operational | ⚠️ Needs Improvement | Legacy systems are monitored, but there is no regular schedule or clearly defined intervention process. |
| Encryption | Technical | ❌ Not Implemented | Encryption is not currently used to protect payment card information. |
| Password Management System | Technical | ❌ Not Implemented | No centralized password management system is currently available. |
| Physical Locks | Physical / Operational | ✅ Implemented | Offices, storefront, and warehouse have sufficient locks. |
| CCTV Surveillance | Physical / Operational | ✅ Implemented | Current CCTV surveillance is in place and up to date. |
| Fire Detection and Prevention | Physical / Operational | ✅ Implemented | Fire detection and prevention systems are functioning. |

---

# 2. PCI DSS Compliance Assessment

| PCI DSS Best Practice | Status | Assessment |
|---|---|---|
| Only authorized users have access to customer credit card information | ❌ Not Compliant | Employees currently have broad access to internally stored data and may access cardholder information. |
| Credit card information is stored, accepted, processed, and transmitted in a secure environment | ❌ Not Compliant | Payment card information is handled internally without adequate access restrictions and encryption. |
| Implement encryption procedures for payment data | ❌ Not Compliant | Encryption is not currently implemented. |
| Adopt secure password management policies | ❌ Not Compliant | Existing password requirements are insufficient and no centralized password management system exists. |

---

# 3. GDPR Compliance Assessment

| GDPR Best Practice | Status | Assessment |
|---|---|---|
| E.U. customer data is kept private and secure | ❌ Not Compliant | Employees have broad access to internally stored data, including potential access to PII/SPII. |
| Notify E.U. customers within 72 hours of a breach | ✅ Compliant | A notification plan has been established for E.U. customers. |
| Ensure data is properly classified and inventoried | ❌ Not Compliant | The organization does not currently have adequate asset and data classification practices. |
| Enforce privacy policies and procedures | ✅ Compliant | Privacy policies, procedures, and processes have been developed and enforced. |

---

# 4. SOC Type 1 / SOC Type 2 Assessment

| SOC Best Practice | Status | Assessment |
|---|---|---|
| User access policies are established | ❌ Not Compliant | Least privilege and separation of duties have not been implemented. |
| Sensitive data (PII/SPII) is confidential | ❌ Not Compliant | Broad employee access creates a confidentiality risk. |
| Data integrity is maintained | ✅ Implemented | The IT department has implemented controls supporting data integrity. |
| Data is available to authorized individuals | ⚠️ Needs Improvement | Data availability controls exist, but access is not sufficiently restricted to authorized personnel. |

---

# 5. Key Findings

The assessment identified several high-priority security gaps:

1. Sensitive customer and payment information is not adequately restricted.
2. Encryption is not implemented for payment card information.
3. Critical data is not backed up.
4. Disaster recovery procedures have not been established.
5. Least privilege and separation of duties are not implemented.
6. Password security requires improvement.
7. No centralized password management system exists.
8. The organization lacks an intrusion detection capability.
9. Asset and data classification practices require improvement.
10. Legacy system monitoring lacks a formal schedule and documented intervention procedures.

---

# 6. Overall Assessment

**Overall Security Posture: High Risk**

The organization has several foundational security controls in place, including firewall protection, antivirus software, physical security controls, CCTV surveillance, and fire detection systems.

However, significant gaps remain in access control, data protection, business continuity, authentication, threat detection, and compliance practices.

These gaps may increase the organization's exposure to unauthorized access, data loss, payment information compromise, operational disruption, and regulatory risk.

---

# 7. Audit Conclusion

Based on the available evidence, Botium Toys should prioritize the implementation of controls that protect sensitive information, restrict access, preserve critical data, and improve incident detection and recovery capabilities.

The highest priorities are:

- Implement least privilege and separation of duties.
- Encrypt sensitive payment information.
- Establish reliable backups.
- Develop disaster recovery procedures.
- Strengthen password requirements.
- Implement centralized password management.
- Evaluate the implementation of an IDS.
- Improve asset and data classification.
- Establish a formal maintenance schedule for legacy systems.

These improvements would reduce organizational risk and strengthen the overall cybersecurity posture.
