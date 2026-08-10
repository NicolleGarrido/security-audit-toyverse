# Controls and Compliance Checklist

## Assessment Overview

This checklist evaluates the security controls currently implemented by Botium Toys and identifies gaps that may increase cybersecurity and compliance risks.

The assessment is based on the information provided in the Botium Toys risk assessment and the organization's current security posture.

---

# 1. Security Controls Assessment

| Security Control | Implemented | Assessment |
|---|:---:|---|
| Least Privilege | No | All employees currently have access to internally stored data. |
| Disaster Recovery Plans | No | No disaster recovery plan is currently in place. |
| Password Policies | Yes | A password policy exists, but its requirements are weak and outdated. |
| Separation of Duties | No | Separation of duties has not been implemented. |
| Firewall | Yes | A firewall is configured to block traffic based on defined security rules. |
| Intrusion Detection System (IDS) | No | No IDS has been installed. |
| Backups | No | Critical data is not currently backed up. |
| Antivirus Software | Yes | Antivirus software is installed and regularly monitored. |
| Manual Monitoring and Maintenance | Yes | Legacy systems are monitored and maintained, although there is no regular schedule. |
| Encryption | No | Customer payment information is not encrypted. |
| Password Management System | No | No centralized password management system is currently implemented. |
| Physical Locks | Yes | Offices, storefront, and warehouse have sufficient locks. |
| CCTV Surveillance | Yes | The physical location has up-to-date CCTV surveillance. |
| Fire Detection and Prevention | Yes | Fire detection and prevention systems are functioning. |

---

# 2. PCI DSS Compliance Assessment

The Payment Card Industry Data Security Standard (PCI DSS) requirements were reviewed based on the current handling of customer payment information.

| PCI DSS Best Practice | Compliant | Assessment |
|---|:---:|---|
| Only authorized users have access to customer credit card information | No | All employees may have access to internally stored data and potentially cardholder information. |
| Credit card information is stored, accepted, processed, and transmitted securely | No | Payment information is handled internally without encryption. |
| Implement encryption procedures for payment data | No | Encryption is not currently implemented for customer credit card information. |
| Adopt secure password management policies | No | Existing password requirements are weak and there is no centralized password management system. |

---

# 3. GDPR Compliance Assessment

The General Data Protection Regulation (GDPR) requirements were reviewed because Botium Toys serves customers in the European Union.

| GDPR Best Practice | Compliant | Assessment |
|---|:---:|---|
| E.U. customer data is kept private and secure | No | Access controls and encryption are insufficient to adequately protect customer information. |
| Notify E.U. customers within 72 hours of a breach | Yes | A notification plan has been established. |
| Data is properly classified and inventoried | No | The organization currently has inadequate asset and data management. |
| Privacy policies and procedures are enforced | Yes | Privacy policies, procedures, and processes have been developed and enforced. |

---

# 4. SOC Type 1 and SOC Type 2 Assessment

The following practices were evaluated based on the organization's current access, confidentiality, integrity, and availability controls.

| SOC Best Practice | Compliant | Assessment |
|---|:---:|---|
| User access policies are established | No | Least Privilege and Separation of Duties have not been implemented. |
| Sensitive data is confidential and private | No | Sensitive information is accessible to all employees and is not encrypted. |
| Data integrity is maintained | Yes | The IT department has implemented controls to support data integrity. |
| Data is available to authorized individuals | Yes | The IT department has implemented controls supporting data availability. |

---

# 5. Key Findings

The assessment identified several high-priority security and compliance gaps.

### Critical Findings

- Excessive access to sensitive information
- Lack of encryption for payment information
- No disaster recovery plan
- No backups for critical data
- No centralized password management
- No Intrusion Detection System

### Additional Findings

- Password requirements are outdated.
- Legacy system monitoring does not follow a defined schedule.
- Asset management and classification require improvement.
- Separation of duties has not been implemented.

---

# 6. Positive Security Controls

Despite the identified gaps, Botium Toys has several controls already in place:

- Firewall protection
- Antivirus software
- Physical locks
- CCTV surveillance
- Fire detection and prevention
- Data integrity controls
- Data availability controls
- GDPR breach notification planning
- Privacy policies and procedures

These controls provide a foundation for improving the organization's overall security posture.

---

# 7. Assessment Conclusion

Botium Toys has implemented several foundational security controls, but significant gaps remain in access control, data protection, business continuity, monitoring, and compliance.

The highest priorities should be protecting sensitive customer information, limiting access to authorized personnel, establishing backup and disaster recovery capabilities, and strengthening password management.

These improvements would reduce the organization's overall risk and improve its ability to protect critical business and customer data.
