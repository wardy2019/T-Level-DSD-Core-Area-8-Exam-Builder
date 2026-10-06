# T Level Digital Software Development
## Core Paper 2 – Content Area 8: Security

## Purpose

This knowledge source supports revision for **Core Paper 2, Content Area 8: Security** of the T Level Technical Qualification in Digital Software Development.

It is designed to support:

- independent student revision
- retrieval practice
- exam-style question generation
- scenario-based application
- analysis and evaluation
- examiner-style marking and feedback
- identification of misconceptions
- personalised revision priorities

The content is restricted to **Core Area 8 only**, specification references **8.1.1–8.4.2**.

---

# 8.1 Security Risks

## Confidential Information

Students should know the types of confidential information held by organisations.

### Human Resources
- salaries and benefits
- staff personal details

### Commercially Sensitive Information
- client details
- stakeholder details
- intellectual property
- sales numbers
- contracts

### Access Information
- usernames
- passwords
- multi-factor authentication details
- PINs
- access codes
- passphrases
- biometric data

---

# Why Information Must Be Confidential

Students should understand why organisations protect different types of information.

## Salaries and Benefits
Protecting this information can:

- prevent competitors offering higher wages to attract staff
- prevent employees comparing salaries and demanding comparable pay

## Staff Details

Protecting staff details can:

- protect staff privacy
- prevent competitors directly contacting employees

## Intellectual Property

Confidentiality can prevent competitors copying designs.

## Client Details

Protecting client information can:

- protect client privacy
- prevent competitors contacting clients

## Access Information

Protecting authentication and access information helps prevent unauthorised access.

---

# Impact of Privacy and Confidentiality Failures

Students should understand potential impacts including:

- regulatory non-compliance
- loss of licence to practise
- loss of trust
- damage to organisational image
- financial loss
- fines
- refunds
- loss of earnings
- termination of contracts
- legal action
- reduced security

Application questions should link the information that is exposed to a realistic organisational impact.

---

# 8.2 Threats and Vulnerabilities

A useful security relationship is:

**Threat → Vulnerability → Impact → Mitigation**

Students should not confuse these terms.

## Threat

Something capable of causing harm.

## Vulnerability

A weakness that could be exploited.

## Impact

The consequence if the threat successfully exploits the vulnerability.

## Mitigation

A measure used to prevent or reduce the risk or impact.

---

# Technical Threats

Students should understand the threats, impacts and appropriate prevention or mitigation methods associated with:

- botnets
- DoS
- DDoS
- malicious hacking
- password cracking
- brute-force attacks
- cross-site scripting
- SQL injection
- buffer overflow

Malicious hackers may include:

- hacktivists
- nation states
- organised crime
- individuals

---

# Malware

Students should understand:

## Virus

Malicious code that attaches to files or programs and spreads when activated.

## Worm

Malware capable of self-replication and spreading between systems.

## Keylogger

Records keyboard input and may capture sensitive information.

## Ransomware

Prevents access to systems or data and demands payment.

## Spyware

Secretly collects information or monitors activity.

## Remote Access Trojan

Provides unauthorised remote access or control while appearing to be legitimate software or content.

---

# Social Engineering

Students should understand the differences between:

## Phishing

Fraudulent communication designed to make users reveal information or perform an unsafe action.

## Spear Phishing

Targeted phishing designed for a specific person or organisation.

## Smishing

Phishing using text messages.

## Vishing

Phishing using voice communication.

## Pharming

Redirecting users towards a fraudulent destination.

## Watering-Hole Attack

Compromising a website or service likely to be used by intended targets.

## USB Baiting

Leaving malicious removable media where someone may connect it to a system.

Students should distinguish these techniques rather than using "phishing" as a generic answer for all social engineering.

---

# Other Technical Threats

Students should understand:

- DNS attack/redirection
- insecure APIs
- man-in-the-middle attacks
- open/unsecured Wi-Fi networks

Questions may require students to connect these threats to vulnerabilities, possible impacts and appropriate mitigation.

---

# Technical Vulnerabilities

Students should understand:

## Inadequate Security Processes
- weak encryption
- inadequate password policy
- failure to use MFA

## Out-of-Date Components
- hardware
- software
- firmware

Outdated components may expose organisations to weaknesses that have not been corrected.

---

# Human Threats

Students should understand:

## Human Error

Possible controls include:

- file properties
- confirmation boxes
- staff training

## Malicious Employee

Possible responses include:

- immediate removal from premises
- immediate suspension of user accounts

## Disguised Criminal

Controls include:

- checking visitor identification
- accompanying visitors

## Poor Cyber Hygiene

Good practice includes:

- locking unattended machines
- not writing down passwords
- appropriate password management

---

# Physical Vulnerabilities

Students should understand:

## Lack of Access Control
Use entry-control systems.

## Poor Access Control
Measures include:

- preventing tailgating
- complex access codes
- changing codes regularly
- monitoring access areas
- auditing staff access

## Nature of Location
Protection may be required against:

- shoulder surfing
- environmental threats
- vandalism

## Poor System Robustness

Rugged equipment may be suitable in some environments.

## Natural Disasters

Physical protection, recovery and resilience measures may be required.

---

# Impact of Threats and Vulnerabilities

Students should understand potential consequences including:

- loss or leakage of sensitive data
- unauthorised access to digital systems
- data corruption
- disruption of service
- unauthorised access to restricted physical areas

Strong responses should connect a specific threat or vulnerability to a specific impact.

---

# 8.3 Threat Mitigation

Students should understand the:

- purpose
- process
- benefits
- drawbacks

of security controls.

---

# Security Controls

Students should understand:

- hardware security settings
- software security settings
- anti-malware software
- intrusion detection
- encryption
- user access policies
- staff vetting
- staff training
- software-based access control
- device hardening
- backups
- software updates
- firmware/driver updates
- air gaps
- API certification
- VPNs
- multi-factor authentication
- password managers
- port scanning
- penetration testing

---

# Encryption

## Hashing

Creates a one-way representation of data.

It may support integrity checking and protecting stored comparisons.

Hashing is **not reversible encryption**.

## Symmetric Encryption

Uses the same secret key to encrypt and decrypt data.

### Benefit
Efficient for protecting large quantities of data.

### Drawback
The key must be shared and stored securely.

## Asymmetric Encryption

Uses related public and private keys.

### Benefit
The private key does not need to be shared.

### Drawback
It generally requires more processing than symmetric encryption.

Students should understand the differences rather than treating all encryption methods as identical.

---

# Backups

Students should understand:

- full backups
- incremental backups
- differential backups
- safe backup storage

Backups support **recovery**.

They do not prevent malware or other attacks from occurring.

---

# Multi-Factor Authentication

MFA requires more than one authentication factor.

### Benefit
A stolen password alone may not be sufficient to gain access.

### Limitation
MFA does not make an account impossible to compromise.

---

# VPN

A VPN creates a protected private connection over another network.

It can be appropriate when staff use an untrusted network.

A VPN does not automatically protect an unsafe endpoint from every security threat.

---

# Device Hardening

Device hardening reduces unnecessary exposure by removing or disabling:

- ports
- applications
- permissions
- unnecessary access

Students should be able to explain how this reduces the available attack surface.

---

# Penetration Testing

Penetration testing attempts to identify exploitable weaknesses.

Students should understand the distinction between:

- ethical hacking
- unethical hacking

Authorisation and scope are important when penetration testing is carried out.

---

# Internet Security Procedures

Students should understand:

## Firewall Configuration

Rules can control:

- inbound traffic
- outbound traffic
- traffic type
- applications
- IP addresses

## Network Segregation

Networks may be separated:

- virtually
- physically
- offline

Segregation can limit communication and restrict the spread of an incident.

## Network Monitoring

Monitors activity to identify possible threats or unusual behaviour.

## Port Scanning

Identifies exposed ports and services for investigation.

---

# Layered Security

Students should understand that a single security control will not normally remove every risk.

For example:

**Ransomware risk**

Possible layered measures:

- staff training
- anti-malware
- software updates
- access control
- network segregation
- protected backups
- monitoring
- recovery procedures

Higher-demand questions should encourage students to justify combinations of controls.

---

# 8.4 Effective Security

# CIA Triad

Students should understand how the three elements interrelate.

## Confidentiality

Ensuring data remains private by controlling access.

Possible controls include:

- access control
- encryption
- MFA

## Integrity

Ensuring that data has not been tampered with.

Possible controls include:

- hashing
- permissions
- monitoring

## Availability

Ensuring data and systems remain available and useful.

Possible controls include:

- backups
- redundancy
- recovery arrangements

The CIA elements should not be treated as completely independent.

For example:

A confidentiality failure could allow an unauthorised person to alter data, damaging integrity.

Damaged or corrupted data may no longer be useful, reducing availability.

---

# IAAA Model

Students should understand:

1. Identification
2. Authentication
3. Authorisation
4. Accountability

---

## Identification

Recognises or establishes the claimed identity of a user.

Methods include:

- username
- possession-based identification
- biometric-based identification

---

## Authentication

Checks that the user is genuinely the person claimed during identification.

Methods include:

- passwords
- passphrases
- MFA
- biometric authentication

---

## Authorisation

Determines which resources and actions an authenticated user is permitted to access.

Methods include:

- role-based access
- access-control lists

---

## Accountability

Ensures actions can be traced to the responsible user.

Methods include:

- audit logs
- user activity records

---

# IAAA Example

A user enters a username.

**Identification:**  
The username identifies the claimed account.

The user supplies a password and MFA code.

**Authentication:**  
The system checks whether the identity claim is valid.

The system grants access to approved files only.

**Authorisation:**  
Permissions determine what the authenticated user can access.

The user's actions are recorded.

**Accountability:**  
Audit logs allow activity to be traced back to the account.

---

# Common Misconceptions

The revision agent should identify and correct misconceptions including:

- threat and vulnerability mean the same thing
- privacy failures only cause financial loss
- all social-engineering attacks are phishing
- viruses and worms spread in exactly the same way
- anti-malware prevents every cyberattack
- hashing is reversible encryption
- symmetric and asymmetric encryption work identically
- MFA makes an account impossible to compromise
- backups prevent ransomware infection
- VPNs prevent every security threat
- penetration testing is always automatically authorised
- identification and authentication are the same process
- authentication automatically gives access to every resource
- authorisation and accountability are the same thing
- CIA components operate independently
- one security measure is enough to secure an organisation

---

# Paper 2 Assessment Focus

Core Area 8 is assessed on **Core Paper 2**.

Questions should therefore include both:

## Section A Style

Primarily:

- knowledge
- understanding
- definitions
- features
- purposes
- benefits and drawbacks
- short explanations

## Section B Style

Primarily:

- contextual application
- analysis
- comparison
- recommendations
- security decisions
- evaluation
- justified judgement

Students should not receive full application credit for generic security facts that are not connected to the scenario.

---

# Important Question Relationships

The revision agent should regularly assess:

### Threat Questions

Threat  
→ Vulnerability  
→ Impact  
→ Mitigation

### Security Control Questions

Control  
→ Purpose  
→ Process  
→ Benefit  
→ Limitation  
→ Suitability

### Confidentiality Questions

Information  
→ Why confidential  
→ Risk  
→ Organisational impact

### CIA Questions

Security problem  
→ CIA element affected  
→ Impact  
→ Appropriate control

### IAAA Questions

Stage  
→ Purpose  
→ Technique  
→ Benefit/drawback  
→ Scenario application

---

# Higher-Demand Revision

Students should practise questions requiring them to:

- identify a security threat from a scenario
- identify the vulnerability being exploited
- explain likely organisational impact
- recommend appropriate mitigation
- justify why the mitigation suits the threat
- recognise limitations of the chosen control
- compare alternative controls
- recommend layered security
- analyse effects on CIA
- distinguish IAAA stages
- evaluate security approaches
- reach a justified contextual judgement

---

# Revision-Agent Boundary

Generate and mark questions only from:

**Core Paper 2 – Content Area 8: Security**

Specification references:

**8.1.1–8.4.2**

Use the supplied Core Area 8 knowledge source as the primary source for question generation and marking.

Do not introduce unrelated advanced cybersecurity knowledge.

Security examples should support defensive learning and examination preparation.
