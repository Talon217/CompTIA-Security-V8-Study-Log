# 1.0 General Security Concepts 16%

## 1.1  Explain security concepts and controls.

### 1.1.1 Defense in depth

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

<br>

- Authentication, authorization, accounting (`AAA`)
  - **Authentication:** "Who are you?"
  - **Authorization:** "What are you allowed to do?"
  - **Accounting:** "What did you do?"

<br>

- Non-repudiation
  - **Concept:** only 1 specific person has access to their unique private key, any data signed by it can be mathematically traced back to them using their public key.
  - **Terminology:** repudiation = deny , Non-repudiation essentially means unable to deny.

<br>


- Zero Trust principles
    - **Concept:** Never trust, always verify.
    - **In-Depth:** Always running in background, checking if you and your device are secure, and limiting user access with expiration timers, and minimal permissions

<br>

- Least privilege

<br>

### 1.1.2 Control categories

- Technical/logical
- Managerial/administrative
- Physical/environmental
- Operational

### 1.1.3 Control types

- Preventive
- Deterring
- Corrective
- Detective
- Compensating
- Directive

---
