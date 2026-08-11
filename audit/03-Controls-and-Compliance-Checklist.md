# Risk Assessment

## Purpose

This risk assessment identifies the primary cybersecurity risks affecting Botium Toys based on the organization's current security posture, managed assets, and existing security controls.

The assessment is aligned with the Identify function of the NIST Cybersecurity Framework (CSF), with emphasis on asset management, risk identification, and the potential impact of security weaknesses on business operations and critical assets.

---

## Overall Risk Rating

**Risk Level:** High

**Risk Score:** 8/10

The current security posture presents a high level of risk due to the absence of several important administrative, technical, and operational controls.

The organization also faces potential compliance risks related to the protection of payment card information and customer data.

---

## Key Risk Areas

| Risk Area | Current Condition | Potential Impact |
|---|---|---|
| Asset management | Assets are not adequately managed or classified | Difficulty identifying critical assets and prioritizing protection |
| Access control | Least privilege and separation of duties are not implemented | Increased risk from compromised or unauthorized accounts |
| Payment data protection | Encryption is not currently implemented | Increased risk to the confidentiality of payment card information |
| Business continuity | No disaster recovery plan or backups for critical data | Increased risk of data loss and operational disruption |
| Threat detection | No intrusion detection system (IDS) is installed | Reduced ability to detect anomalous network activity |
| Password security | Existing password requirements are insufficient | Increased risk of account compromise |
| Password management | No centralized password management system exists | Increased password-related security and operational risks |
| Legacy systems | Systems require manual monitoring and maintenance without a regular schedule | Increased risk from outdated systems and unclear intervention procedures |
| Regulatory compliance | Some compliance best practices are not currently implemented | Potential regulatory penalties and increased exposure of sensitive data |

---

## Existing Security Controls

The assessment identified the following controls as currently implemented:

- Firewall
- Antivirus software
- Physical locks
- Closed-circuit television (CCTV) surveillance
- Fire detection and prevention systems
- Data integrity controls
- Data availability controls
- GDPR-related breach notification procedures
- Privacy policies, procedures, and processes

These controls provide important layers of protection; however, additional controls are required to address the organization's current risk exposure.

---

## Missing or Insufficient Controls

The following controls were identified as missing or insufficient:

- Least privilege
- Separation of duties
- Intrusion Detection System (IDS)
- Disaster recovery plans
- Backups of critical data
- Encryption
- Centralized password management
- Adequate password complexity requirements
- Regularly scheduled monitoring and maintenance for legacy systems
- Appropriate asset classification and inventory

These gaps increase the potential impact of security incidents, data exposure, operational disruption, and compliance issues.

---

## Compliance Risk

The current security posture creates potential compliance concerns involving:

### PCI DSS

Payment card information is accepted, processed, transmitted, and stored internally. Encryption and appropriate access restrictions are not fully implemented.

### GDPR

The organization has established a plan to notify European Union customers within 72 hours of a security breach and has established privacy procedures. However, appropriate data classification and protection controls remain important areas for improvement.

### SOC Type 1 and SOC Type 2

The organization has controls supporting data availability and integrity, but access control and confidentiality requirements require additional attention.

---

## Business Impact

If the identified risks are not addressed, the organization could experience:

- Exposure of customer information
- Compromise of payment card information
- Unauthorized access to sensitive data
- Data loss
- Business disruption
- Recovery difficulties following a security incident
- Regulatory penalties
- Financial losses
- Loss of customer trust

---

## Risk Assessment Conclusion

The overall risk score of **8/10** indicates that corrective action should be prioritized.

The highest priorities should include protecting sensitive customer and payment information, implementing appropriate access controls, establishing reliable backup and disaster recovery capabilities, improving password security, and strengthening threat detection.

Improving these areas would reduce the organization's exposure to cybersecurity threats and support a stronger overall security posture.

---

## Recommended Priority

### Priority 1 — Protect sensitive data

Implement encryption and restrict access to sensitive customer and payment information according to job responsibilities.

### Priority 2 — Improve business continuity

Establish disaster recovery procedures and implement reliable backups of critical data.

### Priority 3 — Strengthen access and authentication

Implement least privilege, separation of duties, stronger password requirements, and centralized password management.

### Priority 4 — Improve detection capabilities

Evaluate and implement an Intrusion Detection System (IDS) to improve the organization's ability to identify suspicious activity.

### Priority 5 — Improve asset and legacy-system management

Create an accurate asset inventory and establish a documented schedule for monitoring and maintaining legacy systems.
