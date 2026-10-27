# 1.0 General Security Concepts 16%

## 1.1  Explain security concepts and controls.

### 1.1.1 Defense in depth

---

- Confidentiality, integrity, and availability (`CIA`)
  - **Confidentiality:** Keep private content private
    - Encryption
    - Access Controls
    - MFA 
  - **Integrity:** Ensure the accuracy of data
    - Hashing
      - **Cocept:**  mathematical algorithm to convert any amount of data into a unique, fixed-length string of characters
      - **In-Depth:** Sender combines private key & hash -> recipient decrypts hash using senders public key
      - **Example:** Checking if a downloaded file was corrupted, detecting malware, and safely saving the hash of a PW
    - Digital Signature
      - **Concept:** Data integrity, sender authentication, and `non-repudiation`
      
  - **Availability:** Access to data when needed

<br>

### 1.1.2 Control categories

---

### 1.1.3 Control types

---
