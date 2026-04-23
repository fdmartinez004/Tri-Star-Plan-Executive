# Strategic Risk Management: The Tri-Star Plan
## Defensive Mitigation and Prevention Matrix
**Prepared by:** Frank Martinez, Transportation Safety and Communications Specialist
**Date:** April 2026

---

<div align="center">
  <h2>Tri-Star Plan: Technical Attack Mitigation Table</h2>
</div>

| Threat Category | Specific Attacks | Tri-Star Component | Defensive Mechanism |
| :--- | :--- | :--- | :--- |
| **Identity & Authentication** | Phishing, Business Email Compromise (BEC), Credential Stuffing | **YubiKey + Cloudflare Email Security** | Hardware-backed FIDO2 authentication eliminates proxy-based phishing and unauthorized "man-in-the-middle" access. |
| **Network & Availability** | DDoS, Smurf Attacks, TCP/UDP Floods, Teardrop, DNS Attacks | **Cloudflare Magic Transit + Aruba Gateways** | Absorbs volumetric traffic at the edge; stateful inspection drops malformed/fragmented packets before they reach the data center. |
| **Endpoint & Malware** | Viruses, Worms, Ransomware, Compromised Laptops | **CrowdStrike Falcon** | AI-driven Indicators of Attack (IOAs) provide real-time prevention and containment of malicious payloads, even off-network. |
| **Web & Application** | SQL Injection (SQLi), Cross-Site Scripting (XSS), XSRF (Forgery) | **Cloudflare WAF** | Analyzes HTTP/S requests in real-time to block malicious code injection and session forgery attempts at the application layer. |
| **Internal & IoT Infrastructure** | Smart TV Instructional Devices, Unauthorized Proxy Servers | **Aruba ClearPass + ZTNA** | Micro-segmentation isolates vulnerable IoT devices (Smart TVs) from the core network; ZTNA replaces vulnerable VPNs. |

---

<div align="center">
  <h3>Strategic Mitigation Strategy</h3>
</div>

### 1. Identity Assurance (The Human Element)
By deploying **YubiKey**, we effectively eliminate the risk associated with **Phishing** and **Business Email Compromise (BEC)**. Even if an employee’s credentials are stolen, the physical hardware token ensures that an attacker cannot gain access, securing the "human perimeter."

### 2. Infrastructure Resilience (The Network Element)
The combination of **Cloudflare** and **Aruba** provides a dual-layer shield. While Cloudflare manages global threats like **DDoS** and **DNS Attacks**, Aruba's hardware manages local vulnerabilities like **Smurf** and **Teardrop** attacks through advanced packet inspection and network segmentation.

### 3. Continuous Monitoring (The Endpoint Element)
**CrowdStrike Falcon** secures every district **laptop** and server. It prevents **Worms** and **Viruses** from spreading laterally. This is critical for mobile devices that move between the district network and home environments.

---
<div align="center">
  <h1>Strategic Risk Governance & ROSI Framework</h1>
  <p><em>A Transition to Identity-Based Security Architecture</em></p>
</div>

<hr>

<div align="justify">
  As our organization matures toward a <strong>Zero Trust, identity-centric architecture</strong>, this matrix serves as the primary driver for <strong>ROSI (Return on Security Investment)</strong>. By shifting the paradigm from technical implementation to <strong>Strategic Risk Mitigation</strong>, we categorize every security control as a <strong>Prevented Loss Event</strong>. The focus remains on safeguarding the district’s operational continuity and fiscal health against an evolving threat landscape.
</div>

<br>

<div align="center">
  <h3>Tri-Star Mitigation & Financial Impact Matrix</h3>
</div>

| Loss Event Target | Threat Neutralized | Tri-Star Component | Financial/Operational Impact |
| :--- | :--- | :--- | :--- |
| **District General Fund** | Business Email Compromise (BEC) | **YubiKey + Cloudflare** | Prevents fraudulent wire transfers and payroll redirection. |
| **Student Data Privacy** | SQL Injection / Data Breach | **Cloudflare WAF** | Eliminates potential civil litigation and regulatory fines from PII exposure. |
| **Classroom Continuity** | Ransomware / Worms | **CrowdStrike Falcon** | Prevents system-wide lockdowns and the multi-week cost of manual re-imaging. |
| **Safety Infrastructure** | IoT / Smart TV Hijacking | **Aruba Segmentation** | Ensures physical safety devices (GPS/Video) remain isolated and operational. |

<br>

| <div align="center"><h3>The Cost of Inaction (COI)</h3></div> |
| :--- |
| <div align="justify">The financial and reputational impact of a single <strong>Ransomware event</strong> or a <strong>Major Data Breach</strong> carries costs that exponentially outweigh the total investment of the Tri-Star Plan. This strategy ensures fiscal responsibility by protecting the District against "Black Swan" events that could deplete emergency reserves, compromise student safety, or damage the public trust in Midland ISD’s governance.</div> |



<div align="center">
  <h3>Strategic Governance References</h3>
  <p><strong>NIST CSF 2.0</strong> | <strong>COBIT 2019</strong> | <strong>SROI (Social Return on Investment)</strong></p>
</div>
---

<div align="center">
  <h3>Reference Documentation & Frameworks</h3>
</div>

* **NIST CSF 2.0 (Protect & Detect Functions):** [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
* **CIS Controls (v8) - Data Protection & Access Control:** [Center for Internet Security](https://www.cisecurity.org/controls)
* **CISA: Understanding Smurf/DDoS Attacks:** [CISA Security Tips](https://www.cisa.gov/news-events/news/understanding-denial-service-attacks)
* **FIDO Alliance: Multi-Factor Authentication Standards:** [FIDO Alliance](https://fidoalliance.org/)
* **CrowdStrike: AI and Indicators of Attack:** [CrowdStrike Tech Center](https://www.crowdstrike.com/cybersecurity-101/indicators-of-attack/)
