# Package management

## Goal
Understand how Linux installs, removes, and updates software packages.

Package management is essential for:

- System administration  
- Security patching  
- Software troubleshooting  

---

## Red Hat based systems (RHEL, CentOS, Rocky, Alma)

Install a package:

sudo dnf install tree  

Remove a package:

sudo dnf remove tree  

Update all packages:

sudo dnf update  

List installed packages:

dnf list installed  

Query RPM database directly:

rpm -qa  

---

## Debian based systems (Ubuntu, Kali)

Update package list:

sudo apt update  

Install a package:

sudo apt install tree  

Remove a package:

sudo apt remove tree  

Upgrade installed packages:

sudo apt upgrade  

List installed packages:

dpkg -l  

---

## Why this matters for cybersecurity

Security vulnerabilities often exist in:

- outdated software  
- unpatched libraries  
- misconfigured packages  

Security professionals must:

- verify installed software  
- apply updates quickly  
- remove unnecessary programs  
