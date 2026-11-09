# 2.0 Threats, Vulnerabilities, and Attacks 24%

## 2.1  Explain characteristics of threats and vulnerabilities.
### Threats
  - Threat feeds
    - **Concept:** Trackers, and vendors sharing information on emerging security risk
  - Likelihood
  - Impact
  - Intelligence sources
    - OSINT
    - Dark web
  - Life cycle
    -  Direction (defining requirements),
    -  Collection (gathering data),
    -  Processing (formatting data),
    -  Analysis (turning data into useful insights),
    -  Dissemination (sharing with stakeholders), 
    -  Feedback (refining the requirements)
### Vulnerabilities  
  - Scoring
    - The systematic process of evaluating a security flaw's attributes to calculate a numerical severity rating.
  - Common Vulnerability Scoring System (CVSS)
    - An open industry standard for assessing the severity of computer system security vulnerabilities.
  - Prioritization
  - Vulnerability types
    - Zero-day: A security flaw unknown to the vendor, leaving 0 days for a patch to be created before exploitation can occur.
    - Legacy platforms: Outdated operating systems or software applications that no longer receive official updates or security patches.
  - Common Vulnerabilities and Exposures (CVE)
    - **Concept:** A catalog of publicly disclosed cybersecurity vulnerabilities maintained by the MITRE Corporation.

## 2.2 Describe common threat actors and motivations.
### Threat actors
  - Crime syndicate/organized crime
    -  Professional groups hacking for huge payouts.
  - Terrorist
    - Their goal is causing real-world damage and widespread panic.
  - Unskilled attacker
    - Script kiddies with premade tools.
  - Hacktivist
    - They break into systems to fight for a cause.
  - Insider
    - Current or former employees using their real access to do harm.
  - Accidental/unintentional
    - Regular employees who accidentally click phishing links or delete files.
  - Competitor
    - Rival companies trying to steal blueprints or business secrets.
  - State-sponsored
    - High-budget government hackers
### Motivations
  - Financial
  - Influence
  - Intellectual property
  - Notoriety
  - Espionage
  - Fear/chaos
  - Extortion
  - General curiosity
  - Revenge
  - Ideological
  - Political
  - Ethical
### Attributes of actors
  - Internal/external
  - Resources/funding
  - Level of sophistication/capability

## 2.3 Describe threat vectors and sources.
### Advanced persistent threat (APT)
### Message-based
  - Email
  - Short Message Service (SMS)
  - Rich Communication Services (RCS)
  - Instant messaging
  - Collaboration tools
### Image-based
  - Quick response (QR) codes
  - Embedded content
  - Completely Automated Public Turing test to tell Computers and Humans Apart (CAPTCHA)
### Attachment-based
  - Embedded macros
  - Rich Text Format (RTF) documents
  - Portable Document Formats (PDFs)
### Browser-based
  - Extensions
  - JavaScript
  - Password managers
  - Cookies
  - Session tokens
### Network-based
  - Infrastructure devices
  - Virtualized devices
  - Session keys
### Remote access
  - Remote desktop
  - Virtual Network Computing (VNC)
  - Virtual private network (VPN)
### Endpoint-based
  - Mobile devices
  - Workstations
  - Servers
  - Tablets
  - Trusted devices
  - Built-in tools
  - Living-off-the-land tools
### Supply chain-based
  - Third-party providers
  - Managed service providers
  - Logistic providers
  - Software as a service (SaaS) providers
### External media-based
  - Malicious Universal Serial Bus (USB)
### Human-based
  - Impersonation
  - Contractor
  - Visitor
  - Biometric
  - Watering hole
### Internet of Things (IoT)-based
  - Cameras
  - Sensors
  - Printers
### Operational technology (OT)-based
### Physical-based
  - Lock and key
  - Access vestibule
  - Access passes
### Signal-based
  - Bluetooth
  - Radio frequency (RF)
  - Near-field communications (NFC)

## 2.4 Explain types of vulnerabilities and attack surfaces.
### Asset Lifecycle & Patch Management
- Unsupported products
- Obsolete systems
- Unpatched systems
- Unmanaged systems
- Zero-day
### Software, Application & Code Flaws
- Applications
  - Race conditions
    - Time-of-check (TOC)
    - Time-of-use (TOU)
  - Malicious update
- Code
  - Hardcoded secrets
  - Unsafe exception handling
### Host & Infrastructure Surfaces
- Operating system (OS)-based
- Virtualization
- Ports and services
- Cryptographic vulnerabilities
### Identity, Access & Governance
- Identity providers
- Unmanaged/stale credentials
- Misconfiguration
- Shadow IT
- Rogue devices
### Endpoint & Emerging Edge Surfaces
- Mobile devices
- Wireless and low-powered communications
- Large language models (LLMs)
### Cloud, Data & External Repositories
- Public object storage
- Public repositories

## 2.5 Given a scenario, analyze indicators of malicious activity.
### Malware attacks
- Ransomware
- Trojan
- Worm
- Spyware
- Adware
- Virus
- Rootkit
- Keylogger
- Logic bomb
- Fileless malware
### Physical attacks
- Tailgating
- Shoulder surfing
- Skimming
- Forced entry
### Network attacks
- Distributed denial of service (DDoS)
- Protocol downgrade
- Rogue
- Sniffing
- Spoofing
- On-path
- Domain Name System (DNS) attacks
- Cache poisoning
### Social engineering attacks
- Smishing
- Vishing
- Phishing
- Whaling
- Spear phishing
- Quishing
- Impersonation
- Deepfake
### Indicators of compromise
- Hash
- Internet Protocol (IP) address
- Domain
- Malicious processes
- File system artifacts
- Timestamp
- Log manipulation
- Excessive resource consumption
- Plaintext strings
- Account lockout
- Impossible travel
- Concurrent sessions
### Application attacks
- Injection
- Buffer overflow
- Replay
- Privilege escalation
- Forgery
- Directory traversal
### Credential attacks
- Password spraying
- Brute force
- User enumeration
- Replay
- Multifactor authentication (MFA) bypass

## 2.6 Summarize threats and vulnerabilities associated with artificial intelligence (AI) usage.
### Input & Model Manipulation Attacks
- Prompt injection
- Jailbreaking
- Model manipulation
- Evasion
- Poisoning
### System, Interface & Execution Risks
- Code execution
- Session hijacking
- Data loss
### Model Reliability & Output Flaws
- Hallucinations
- Bias
- Explainability
### Data Governance, Compliance & Trust
- Privacy
- Ethical considerations
