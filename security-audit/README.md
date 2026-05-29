# Conduct a Security Audit

### Fictional Scenario
Botium Toys is a small U.S. retail business operating from a single physical location. The company’s online presence has recently expanded, increasing its customer worldwide. In order to understand the current security posture, the IT manager requests an internal security audit applying the NIST Cybersecurity Framework (NIST CSF). The audit includes reviewing physical equipments, internal network and systems.

### Objectives
- Evaluate current IT assets at Botium Toys.  
- Identify weaknesses in current security posture using Controls and Compliance Checklist.  
- Determine which controls and practices should be implemented to improve Botium Toys’ security posture.

### Applied Frameworks
- NIST Cybersecurity Framework (CSF).
- Payment Card Industry Data Security Standard (PCI DSS).
- General Data Protection Regulation (GDPR).
- System and Organizations Controls (SOC 1 / SOC 2).
- CIA Triad.

### Controls and Compliance Checklist

#### Implemented Controls
- Firewall, antivirus software, physical security (locks, CCTV surveillance), and fire detection/prevention systems.
  
#### Weaknesses in Controls
- Least privilege, password policies, separation of duties, password management system. 
- Intrusion Detection System (IDS), manual monitoring/maintenance for legacy systems.  
- Encryption.  
- Disaster recovery plans and backups.
  
#### Implemented Compliance
- General Data Protection Regulation (GDPR): Breach notification process (72-hour requirement), privacy policies, procedures, and processes.
- SOC type 1, SOC type 2: Data integrity controls in place.
  
#### Weaknesses in Compliance
- PCI DSS: access control, encryption of credit card data, password policy practices and management.
- General Data Protection Regulation (GDPR): encryption for customers financial data, asset classification.
- System and Organization Controls (SOC type 1, SOC type 2): Least Privilege, separation of duties, encryption of private/confidential information.

### Recommendations

#### Access Control 
- Implement Identity and Access Management (IAM) to enforce least privilege.
- Enforce separation of duties across business operations.
  
#### Authentication & Password Security
- Implement stronger password policies (including special characters, expiration dates, lengths).
- Apply multi-factor authentication (MFA) for critical systems.
- Deploy a centralized password management system to enforce password policy’s minimum requirements.
  
#### Data Protection
- Encrypt sensitive data at rest and in transit.
- Classify data.

#### Network Security & Monitoring
- Deploy the Intrusion Detection System (IDS) to monitor network activity.
  
#### Backup & Recovery
- Establish plans for disaster recovery and business continuity.
- Implement automated backups with secure storage.
- Test recovery procedures regularly.

#### Compliance Improvements
- Strengthen PCI DSS controls for payment data protection and access control.
- Enhance GDPR compliance through encryption and proper data handling.
- Improve SOC alignment with least privilege and separation of duties.

### Conclusion
The security audit showed that Botium Toys implemented basic security measures, but there are significant gaps in the internal system. The weaknesses were found in access control, authentication practices, data encryption, system monitoring, and disaster recovery processes. Moreover, the compliance gaps were identified through PCI DSS, GDPR, and SOC standards, which may increase the risk of data breaches, regulatory penalties, and business continuity. In conclusion, Botium Toys’ current security measures are established, but lacking strong implementation. Addressing these weaknesses is important to support the company’s expansion in a larger scale.
