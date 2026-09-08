# Tryhackme-management-wants-a-word

A practical penetration-testing lab completed on TryHackMe.

## 🎯 Objective

The objective of this room was to assess a vulnerable target, identify weaknesses through enumeration, obtain initial access, and escalate privileges.

## 🖥️ Lab Information

* **Platform:** TryHackMe
* **Room:** Management
* **Type:** Penetration Testing / CTF
* **Focus:** Enumeration, Web Security, Linux, Privilege Escalation
* **Status:** Completed ✅

## 🔍 Methodology

I followed a structured penetration-testing workflow:

1. Reconnaissance
2. Port and service enumeration
3. Web enumeration
4. Vulnerability analysis
5. Initial access
6. Local enumeration
7. Privilege escalation
8. Post-exploitation

## 1. Reconnaissance

I started by identifying the services exposed by the target and determining which services required further investigation.

Tools used:

* Nmap
* Gobuster
* Linux command-line utilities

## 2. Enumeration

The exposed services and web application were investigated for potential attack surfaces.

Areas examined included:

* Open ports and services
* Web directories
* Application functionality
* Hidden resources
* User and system information
* File permissions
* Potential misconfigurations

## 3. Initial Access

After analyzing the available attack surface, I identified a viable path to obtain initial access to the target.

Sensitive challenge answers, credentials, flags, and exact exploit details are intentionally not included in this public repository.

## 4. Privilege Escalation

After gaining access, I performed local enumeration to identify possible privilege-escalation opportunities.

Key areas investigated:

```text
Current user
User/group privileges
Sudo permissions
SUID binaries
Running processes
Interesting files
File permissions
System configuration
```

This ultimately allowed me to obtain higher privileges on the target.

## 🛠️ Tools Used

* Nmap
* Gobuster
* Linux CLI
* Burp Suite
* Other enumeration tools as required

## 🧠 Skills Practiced

* Network reconnaissance
* Service enumeration
* Web enumeration
* Vulnerability assessment
* Linux enumeration
* Initial access
* Privilege escalation
* Penetration-testing methodology
* Documentation

## 📸 Evidence

Screenshots documenting important stages of the assessment are available in the `screenshots/` directory.

## 📚 Key Takeaways

This room reinforced the importance of:

* Thorough enumeration
* Understanding the attack surface before exploitation
* Investigating unusual application behavior
* Performing systematic post-exploitation enumeration
* Checking permissions and misconfigurations carefully

## ⚠️ Disclaimer

This repository documents work performed in an authorized TryHackMe training environment.

All testing was conducted against the intentionally vulnerable machine provided by TryHackMe.

## 🏁 Status

**Completed ✅**

TryHackMe: Management
