# CompTIA Security+ SY0-701 Study Guide

A comprehensive study guide for the CompTIA Security+ (SY0-701) certification exam, synthesized from course materials and official exam objectives. Built as a single dark-mode HTML file with full anchor navigation.

🔗 **[View the Study Guide](https://conwilso92.github.io/security-plus-study-guide)**

---

## Coverage

All 17 chapters mapped to the 5 official exam domains:

| Domain | Weight | Chapters |
|---|---|---|
| General Security Concepts | 12% | Ch. 1, 7 |
| Threats, Vulnerabilities & Mitigations | 22% | Ch. 2, 3, 4, 5, 6 |
| Security Architecture | 18% | Ch. 9, 10, 12, 13 |
| Security Operations | 28% | Ch. 8, 11, 14, 15 |
| Security Program Management & Oversight | 20% | Ch. 16, 17 |

### What's Inside

- **Chapter 1 — Today's Security Professional:** CIA Triad, DAD Triad, security control categories (Technical/Managerial/Operational/Physical), control types (Preventive/Deterrent/Detective/Corrective/Compensating/Directive), AAA framework, gap analysis, breach impact categories (financial, strategic, compliance, operational, reputational)
- **Chapter 2 — Cybersecurity Threat Landscape:** Threat actor types (script kiddies, hacktivists, insider threats, organized crime, nation-state/APT), hacker hats (white/black/gray), threat intelligence (OSINT, closed-source, ISACs), zero-day attacks, TTPs, attack motivations
- **Chapter 3 — Malicious Code:** Malware types (virus, fileless virus, worm, Trojan, ransomware, spyware, adware, PUP, rootkit, backdoor, bot/botnet, keylogger, logic bomb), client-server vs peer-to-peer botnet models
- **Chapter 4 — Social Engineering & Password Attacks:** Seven social engineering principles, attack techniques (phishing, spear phishing, whaling, vishing, smishing, pretexting, baiting, tailgating, shoulder surfing, dumpster diving, watering hole), password attacks (dictionary, brute force, rainbow table, credential stuffing, password spraying), salting and key stretching
- **Chapter 5 — Security Assessment & Testing:** Vulnerability assessment types (passive, active, credentialed, non-credentialed, agent-based, network-based), CVSS scoring (0.0–10.0 ratings, all eight metrics), scan result validation (true/false positives and negatives), penetration testing (black/white/gray box, rules of engagement), vulnerability management life cycle, common scanning tools (Nessus, Qualys, OpenVAS, Nikto, Metasploit)
- **Chapter 6 — Application Security:** SDLC models (Waterfall, Agile, Spiral, DevSecOps), development environments (dev/test/staging/production), web vulnerabilities (SQLi, XSS stored/reflected/DOM, CSRF, directory traversal, buffer overflow, race condition, hard-coded credentials), secure coding practices, OWASP Top 10, WAF, tokenization, data masking
- **Chapter 7 — Cryptography & PKI:** Symmetric vs asymmetric comparison table, encryption algorithms (AES, 3DES, RSA, ECC, Diffie-Hellman, DHE/ECDHE), hashing (MD5, SHA-1, SHA-256, SHA-3, HMAC), digital signature process (step-by-step), PKI components (CA, X.509, CRL, OCSP, certificate stapling, CSR, TPM, HSM, key escrow), obfuscation (steganography, tokenization, data masking), cryptographic attacks
- **Chapter 8 — Identity & Access Management:** Authentication protocols (PAP, CHAP, EAP, RADIUS, TACACS+, Kerberos, LDAP/LDAPS, SAML, OAuth 2.0, OpenID Connect), MFA factors (know/have/are/somewhere you are), TOTP vs HOTP, biometrics (FAR, FRR, CER), access control models (DAC/MAC/RBAC/ABAC/Rule-Based), federation and SSO, identity providers vs service providers
- **Chapter 9 — Resilience & Physical Security:** Redundancy (geographic dispersion, multi-path networks, replication, clustering, load balancing, platform diversity), backup types (full/incremental/differential/snapshot with archive bit logic), DR site types (hot/warm/cold), site restoration order, resilience testing (tabletop/simulation/parallel/failover), physical controls (vestibule, bollards, fencing, cameras, sensors, access badges)
- **Chapter 10 — Cloud & Virtualization Security:** Cloud service models (IaaS/PaaS/SaaS/FaaS), shared responsibility model, hypervisor types (Type 1/Type 2), VM escape, VM sprawl, container security, VPC, security groups, CASB, vertical vs horizontal scaling, cloud security issues (misconfiguration, data sovereignty, insecure APIs)
- **Chapter 11 — Endpoint Security:** Endpoint hardening (ports, services, patching, Secure Boot, Measured Boot, FDE), endpoint security tools (AV, EDR, HIDS/HIPS, DLP), embedded systems assessment, SCADA/ICS security, IoT security, firmware vulnerabilities
- **Chapter 12 — Network Security:** Network segmentation, DMZ, Zero Trust architecture (subjects/policy engines/enforcement points), fail open vs fail closed, NAC, IDS vs IPS deployment (inline vs passive), NGFW, port mirroring, honeypots/honeynets/honeytokens, secure vs insecure protocol table (Telnet→SSH, HTTP→HTTPS, FTP→SFTP, etc.), email security (SPF/DKIM/DMARC), network attacks (DDoS, SYN flood, MITM, DNS poisoning, ARP poisoning)
- **Chapter 13 — Wireless & Mobile Security:** Wi-Fi security protocol comparison (WEP/WPA/WPA2/WPA3), SAE vs PSK, enterprise wireless authentication (EAP-TLS, PEAP, EAP-TTLS, RADIUS), wireless attacks (evil twin, rogue AP, deauthentication, jamming, wardriving), mobile device deployment models (BYOD/COPE/CYOD/corporate owned), MDM, remote wipe, sideloading, jailbreaking and rooting
- **Chapter 14 — Monitoring & Incident Response:** Incident response process (PICERL: Preparation/Identification/Containment/Eradication/Recovery/Lessons Learned), attack frameworks (Cyber Kill Chain, MITRE ATT&CK, Diamond Model), SIEM (log sources, correlation rules, dashboards), Indicators of Compromise (IoCs), threat hunting, root cause analysis (Five Whys)
- **Chapter 15 — Digital Forensics:** Chain of custody, legal holds, forensic imaging, order of volatility (RAM → disk → remote), EDRM 9-stage model, forensics tools (FTK Imager, FTK, Autopsy, Volatility), write blockers, cloud forensics considerations
- **Chapter 16 — Security Governance & Compliance:** Policy hierarchy (policies/standards/procedures/guidelines/AUP), compliance frameworks (HIPAA, PCI DSS, GDPR, SOX, GLBA, FERPA), NIST Cybersecurity Framework (5 core functions: Identify/Protect/Detect/Respond/Recover, 4 implementation tiers), NIST RMF (7-step process), change management process, version control
- **Chapter 17 — Risk Management & Privacy:** Risk fundamentals (threat/vulnerability/risk), quantitative assessment (SLE = AV × EF, ALE = SLE × ARO), qualitative assessment (risk matrix), risk responses (mitigation/avoidance/transference/acceptance), risk register, risk appetite vs tolerance, data roles (owner/custodian/processor/steward), data classification, privacy enhancing technologies (data minimization, anonymization, pseudonymization, data sovereignty, right to be forgotten)

---

## Related Study Tools

Part of a broader CompTIA certification study toolkit:

| Repo | Description |
|---|---|
| [CompTia-core1-flashcards](https://github.com/conwilso92/CompTia-core1-flashcards) | A+ Core 1 interactive flashcard app |
| [CompTia-core2-flashcards](https://github.com/conwilso92/CompTia-core2-flashcards) | A+ Core 2 interactive flashcard app |
| [network-plus-flashcards](https://github.com/conwilso92/network-plus-flashcards) | Network+ interactive flashcard app |
| [network-plus-study-guide](https://github.com/conwilso92/network-plus-study-guide) | Network+ N10-009 comprehensive study guide |
| [server-plus-study-guide](https://github.com/conwilso92/server-plus-study-guide) | Server+ SK0-005 comprehensive study guide |
| [homelab](https://github.com/conwilso92/homelab) | Homelab documentation and configs |

---

## About

Built while studying for the CompTIA Security+ certification at Star V Learning Centers, Jacksonville, FL. Materials synthesized from course slide decks and the official SY0-701 exam objectives.

**Certifications:** CompTIA A+ (Core 1 & Core 2 passed) · Network+ (in progress) · Security+ (in progress)
