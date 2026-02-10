# Viewing and editing files

## Goal
Learn how to safely read, monitor, and edit files inside Linux systems.

These skills are essential for:

- IT support troubleshooting  
- Reading log files  
- Cybersecurity investigations  

---

## Viewing files

### cat
Displays the full contents of a file.

cat file.txt

---

### less
Allows you to scroll through a file safely.

less /var/log/messages

Useful keys:

- Space → move down one page  
- b → move up one page  
- q → quit  

---

### head and tail
Show the beginning or end of a file.

head file.txt  
head -n 20 file.txt  

tail file.txt  
tail -n 50 file.txt  

Monitor a log file in real time:

tail -f /var/log/syslog  

---

## Editing files

### nano
Beginner friendly text editor.

nano file.txt

Save:  
CTRL + O → Enter  

Exit:  
CTRL + X  

---

### vim
Common editor used on servers.

vim file.txt

Basic survival commands:

- i → insert mode  
- ESC → exit insert mode  
- :wq → save and quit  
- :q! → quit without saving  

---

## Why this matters for cybersecurity

Security analysts and IT support professionals constantly:

- read system logs  
- monitor activity in real time  
- edit configuration files safely  

Mastering these commands is a core Linux skill.
