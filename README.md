# Windows Security/Active Directory

Below is a curated list of system administration and security configuration labs that reflect my ability to manage, harden, and monitor enterprise Windows environments — critical skills for SOC Analysts working in real-world infrastructures.

---

### [Windows Server Installation/Configuration](https://github.com/bekinal/Windows-Server-Installation-Configuration/blob/main/README.md)
This foundational lab demonstrates my ability to stand up enterprise-grade server environments. As a SOC Analyst, understanding how systems are configured is key to spotting misconfigurations and establishing a security baseline.

---

### [Configuring DNS](https://github.com/bekinal/Configuring-DNS/blob/main/README.md)
DNS is a high-value attack surface. This lab shows my understanding of DNS setup and how attackers often abuse it (e.g., DNS tunneling). As a SOC analyst, I’ll use this knowledge to detect anomalies in name resolution traffic and flag suspicious domain activity.

---

### [Creating & Managing Active Directory Objects](https://github.com/bekinal/Creating-and-Managing-AD-Objects/blob/main/README.md)
Active Directory is often the target of lateral movement and privilege escalation. This lab demonstrates my fluency in user/group management and privilege assignment — essential for understanding and detecting AD-based attacks.

---

### [Group Policy Object Configuration](https://github.com/bekinal/Group-Policy-Object-Configuration/blob/main/README.md)
GPOs define security posture across an organization. This lab showcases my ability to configure and audit security-relevant policies, making me better equipped to identify risky or weakened configurations during triage.

---

### [Implementing DHCP](https://github.com/bekinal/Implementing-DHCP/blob/main/README.md)
DHCP is vital for network access and is often a source of rogue device detection. Understanding how it's deployed helps me identify unauthorized DHCP servers or unusual IP allocations in a SIEM.

---

### [PowerShell for Active Directory/Remote Connection](https://github.com/bekinal/PowerShell-for-Active-Directory/blob/main/README.md)
PowerShell is a powerful tool for both admins and attackers. In this lab, I demonstrate the ability to use PowerShell for automation, remote management, and AD queries — critical for investigating suspicious PowerShell activity.

---

### [Shares and Permissions](https://github.com/bekinal/Shares-and-Permissions/blob/main/README.md)
This lab highlights how I manage shared resources and enforce access control. These are common targets in ransomware and insider threats. Knowing how to interpret permission structures allows me to assess risk and track data exfiltration paths.

---

### [Configuring Windows Firewall](https://github.com/bekinal/Configuring-Windows-Firewall/blob/main/README.md)
Firewall configurations determine what traffic can enter or leave a system. This lab strengthens my ability to recognize overly permissive rules and understand host-based defenses during forensic investigations.

---

### [User Password Policies](https://github.com/bekinal/User-Password-Policies)
Password policy enforcement is a core defense against brute force and credential stuffing. This lab shows my ability to implement and audit strong authentication controls — aligning with NIST and CIS benchmarks.

---

### [Handling Local Security Policies](https://github.com/bekinal/User-Password-Policies/blob/main/README.md)
Local policies govern everything from login restrictions to audit logging. This lab gives me experience with host-level policy hardening — key when hunting for persistence mechanisms or privilege abuse.

---

### [Audit Policies](https://github.com/bekinal/Audit-Policies)
Proper audit configuration is essential for visibility. This lab reflects my ability to enable and tune audit settings, which supports log analysis and incident detection — a must-have for any SOC role.

---

Together, these labs showcase not only my technical skill set but also my awareness of how attackers exploit system misconfigurations — and how defenders detect and respond to those threats. Each project strengthens my ability to **triage alerts, analyze logs, and recommend security improvements in real-world environments**.
