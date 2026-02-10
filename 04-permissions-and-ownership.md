# Permissions and ownership

## Goal
Understand how Linux controls access to files and directories.

Permissions are critical for:

- System security  
- Protecting sensitive data  
- Red Hat administration tasks  

---

## Viewing permissions

List files with permission details:

ls -l  

Example permission string:

-rwxr-xr--

Breakdown:

- First character → file type  
- Next three → owner permissions  
- Next three → group permissions  
- Last three → others permissions  

---

## Permission numbers

Numeric values used with chmod:

- 7 → read, write, execute  
- 6 → read, write  
- 5 → read, execute  
- 4 → read only  

Common examples:

chmod 644 file.txt  
chmod 755 script.sh  

Make a script executable:

chmod +x script.sh  

---

## Changing ownership

Change file owner:

chown user file.txt  

Change owner and group:

chown user:group file.txt  

---

## Checking detailed file info

stat file.txt  

Shows:

- permissions  
- owner  
- timestamps  
- size  

---

## Why this matters for cybersecurity

Incorrect permissions can:

- expose sensitive files  
- allow privilege escalation  
- break system security  

Security professionals must always verify:

- who owns a file  
- who can read or modify it  
- whether permissions are too open  
