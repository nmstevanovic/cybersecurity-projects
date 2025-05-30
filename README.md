## Cybersecurity Projects Portfolio

Hello! I’m Nicholas Stevanovic, a recent graduate of Fullstack Academy’s Cybersecurity Bootcamp through the University of Illinois Chicago. This portfolio showcases my applied experience in both offensive and defensive security, featuring projects where I’ve used industry-standard tools and frameworks to solve real-world challenges.

Explore the projects below to see how I apply practical techniques to secure systems, analyze vulnerabilities, and simulate attack scenarios.

## 🛠️ Featured Projects


## 🔐 Password Cracking & Hash Analysis

 - Used **John the Ripper**, **hashcat**, and **Kali Linux** environments to identify and crack various passwords.
 - Analyzed password complexity and vulnerability to common cracking techniques.
 - Developed recommendations for stronger password policies to enhance security posture.

## 🌐 Web Application Exploitation (DVWA)

 - Executed brute-force login attacks and session manipulation using Burp Suite, Hydra, and Repeater. Performed host discovery and reconnaissance with Nmap prior to exploitation.
 - Exploited common web application vulnerabilities such as SQL Injection and Cross-Site Scripting (XSS).
 - Documented mitigation strategies to improve application security and prevent exploitation.

## 🖥️ Active Directory & Lateral Movement

 - Emulated Windows domain environments to practice lateral movement using PSExec, WMI, and Pass-the-Hash techniques. Also explored SSH key-based access and credential reuse on Linux systems to simulate cross-platform attack paths.
 - Mapped privilege escalation and attack paths using the MITRE ATT&CK framework.
 - Gained practical insight into detecting and defending against lateral movement attacks within enterprise networks.


## 🧰 Tools & Skills

Throughout these projects, I applied a broad range of cybersecurity tools, methodologies, and frameworks, including vulnerability assessment, penetration testing, system hardening, and defensive monitoring techniques. Key proficiencies include:

- **Tools:** Kali Linux, Burp Suite, Metasploit, MSFvenom, John the Ripper, hashcat, Hydra, Nmap, Wireshark, PowerShell, Event Viewer, Snort IDS, AIDE, Sysinternals Suite, Netcat, Hash-Identifier, and hasdump.  
- **Concepts:** Credential Attacks, Privilege Escalation, Lateral Movement, Network Enumeration, Red & Blue Team Operations, Defense in Depth, and Pass the Hash.  
- **Frameworks:** MITRE ATT&CK, OWASP Top 10

> _Currently exploring additional tools such as Impacket and tcpdump to deepen my expertise in offensive operations and packet analysis._


## 🔍 Selected Project Showcases

## 🖥️ IT Pre-Onboarding Runbook (Windows Workstation Setup)

- Developed a comprehensive runbook for setting up Windows workstations for new hires at a fictional company.
- Included step-by-step processes for domain joining, Active Directory user and group creation, Group Policy Object (GPO) configuration, shared folder setup, and login script deployment.
- Implemented security and compliance checks through Group Policy restrictions and Event Viewer log auditing.
- Created PowerShell scripts to automate running service listings and software inventory collection for auditing purposes, automating a process that previously required 2 hours of manual effort per workstation. Included Event Viewer log analysis and optional Wireshark packet captures to validate network configurations and monitor login behavior.
- Demonstrates ability to create clear, repeatable IT processes using Windows Server administration tools in a practical context, reducing new hire workstation setup time by an estimated 20% compared to previous manual procedures.


## 🔒 Enhancing Cybersecurity Posture: Lessons from a Log Access Disruption

- Investigated and resolved log access disruption in StackFull Software’s Splunk system caused by a misconfigured config.conf file.
-Diagnosed security risks due to overly permissive file permissions, identifying 3 critical vulnerabilities and verified file integrity using MD5 hashing before and after remediation.
- Collaborated with SOC analysts to identify root cause and implemented fixes, including restoring admin configurations and securing file permissions.
- Created secure backups to ensure disaster recovery readiness, reducing the potential data loss window from 24 hours to 4 hours.
- Developed actionable recommendations for improving Splunk system security posture, including permission restrictions, role-based access control (RBAC), file integrity
  monitoring, auditing, and routine backups.


## 🛡️ Network Security & Defense in Depth Planning: Sweetwater Manufacturing

- Designed a multi-layered network security plan for Sweetwater Manufacturing using a Defense in Depth strategy, reducing the potential attack surface by 40% through network segmentation.
- Implemented edge security with firewalls and DMZ isolation to protect public-facing services, blocking an average of 100+ malicious connection attempts per day.
- Established perimeter controls including VPN access, IP whitelisting, and industrial machine isolation.
- Applied internal segmentation via VLANs and subnets to reduce lateral movement risk.
- Deployed active monitoring tools like Snort IDS and AIDE for host and network detection.
- Enforced host endpoint hardening with local firewalls, security certificates, and USB restrictions.
- Defined administrative policies and physical security controls to secure user and device access.


## 🎯 Simulated Red Team Engagement

- Conducted network reconnaissance using Nmap to map the environment and identify potential entry points.
- Gained initial access to a Linux system via SSH based on discovered services.
- Performed information gathering on the Linux system, leading to the discovery of a password hash.
- Successfully cracked the password hash using John the Ripper and dictionary attacks with standard wordlists on Kali Linux, revealing a weak password.
- Leveraged the cracked credentials with the Metasploit Framework (`windows/smb/psexec` module) to achieve initial access on a Windows server.
- Utilized Meterpreter to dump password hashes from the compromised Windows system.
- Demonstrated lateral movement by employing the "Pass the Hash" technique within Metasploit to authenticate to a secondary Windows server using the obtained hashes.
- On the final target, used Meterpreter's file search capabilities to locate and retrieve the contents of a sensitive file, demonstrating successful completion of the engagement.





## 📫 Connect with Me
- [LinkedIn](https://linkedin.com/in/nicholas-stevanovic-6383561a0)
- [GitHub](https://github.com/nmstevanovic)
