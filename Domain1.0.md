# 1.0 General Security Concepts 16%

## 1.1  Explain security concepts and controls.

### Defense in depth

- Confidentiality, integrity, and availability (`CIA`)
  - **Confidentiality:** Keep private content private
    - Encryption
    - Access Controls
    - MFA
  - **Integrity:** Ensure the accuracy of data
    - Hashing
      - **Concept:**  mathematical algorithm to convert any amount of data into a unique, fixed-length string of characters
      - **Example:** Checking if a downloaded file was corrupted, detecting malware, and safely saving the hash of a PW
    - Digital Signature
      - **Concept:** Data integrity, sender authentication, and `non-repudiation`
      - **In-Depth:** Sender combines private key & hash -> recipient decrypts hash using senders public key
  - **Availability:** Access to data when needed
    - Redundancy
    - Maintain (keep up to date)
      
- Authentication, authorization, accounting (`AAA`)
  - **Authentication:** "Who are you?"
  - **Authorization:** "What are you allowed to do?"
  - **Accounting:** "What did you do?"
- Non-repudiation
  - **Concept:** only 1 specific person has access to their unique private key, any data signed by it can be mathematically traced back to them using their public key.
  - **Terminology:** repudiation = deny , Non-repudiation essentially means unable to deny.

- Zero Trust principles
    - **Concept:** Never trust, always verify.
    - **In-Depth:** Always running in background, checking if you and your device are secure, and limiting user access with expiration timers, and minimal permissions

- Least privilege
  - **Concept:** Only grant the minimum level of access or permissions required.

### Control categories & 1.1.3 Control types

- Control categories
  - Technical/logical
  - Managerial/administrative
  - Physical/environmental
  - Operational
    
- Control types
  - Preventive
  - Deterring
  - Corrective
  - Detective
  - Compensating
  - Directive

| Category | Preventive | Deterrent | Detective | Corrective | Compensating | Directive |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Technical** | Firewall rules | Splash screen | System logs | Backups | Block traffic | Storage policies |
| **Managerial** | Onboarding policy | Threat of demotion | Login report review | Reporting policy | Separation of duties | Compliance policy |
| **Operational** | Guard shack | Reception desk | Guard patrols | Contact authorities | Multiple staff | Security training |
| **Physical** | Door locks | Warning signs | Motion detectors | Fire extinguisher | Power generator | Authorized personnel sign |

<br>

## 1.2 Given a scenario, demonstrate the impact of change management processes on security

### Business processes impacting security operations
- Change Advisory Board (CAB)
  - **Concept:** A formal group of stakeholders that meets to review, prioritize, and evaluate proposed modifications to systems.
- Approval Process
  - **Concept:** Every non-standard alteration requires a formal Request for Change (RFC). No engineer should push fixes straight to production without CAB sign-off.
- Fail Forward
  - **Concept:** instead of rolling back a failed update, you rapidly push a minor hotfix
- Maintenance Window
  - **Concept:** A designated, low-traffic time block (like 2:00 AM on a Sunday)
- Standard Operating Procedures (SOPs)
  - **Concept:**  Step-by-step instructions engineers follow to deploy updates safely and systematically

### Version Control
- **Concept:**  Utilizing central repositories (like Git) to log and track every code, configuration, or documentation revision. 

<br>

## 1.3 Explain the importance of using appropriate cryptographic solutions.

### Public Key Infrastructure (PKI)
- Key Escrow
  - **Concept:** Third-party storage of cryptographic keys for authorized data recovery.
 
### Certificates
- Certificate Authorities (CA)
- Certificate Revocation Lists (CRLs)
- Online Certificate Status Protocol (OCSP)
- Self-Signed Certificates
- Third-Party Certificates
- Root of Trust
- Certificate Signing Request (CSR) Generation
- Wildcard Certificates
