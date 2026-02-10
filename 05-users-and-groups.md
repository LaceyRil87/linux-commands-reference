# Users and groups

## Goal
Understand how Linux manages user accounts, groups, and privileges.

These skills are essential for:

- System administration  
- Access control  
- Security hardening  

---

## Identify current user information

Show the logged-in user:

whoami  

Show detailed user ID information:

id  

Show group memberships:

groups  

---

## Creating and managing users

Create a new user:

sudo useradd lacey  

Set a password for the user:

sudo passwd lacey  

Add user to administrative group (Red Hat based):

sudo usermod -aG wheel lacey  

Add user to sudo group (Debian based):

sudo usermod -aG sudo lacey  

---

## Important system files

List all users on the system:

cat /etc/passwd  

List all groups:

cat /etc/group  

---

## Why this matters for cybersecurity

Attackers often attempt to:

- create hidden users  
- escalate privileges  
- modify group permissions  

Security professionals must know how to:

- verify legitimate users  
- audit group membership  
- control administrative access  
