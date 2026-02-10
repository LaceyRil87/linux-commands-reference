# Processes and services

## Goal
Learn how to view, manage, and control running processes and system services.

These skills are essential for:

- IT troubleshooting  
- System performance monitoring  
- Cybersecurity investigations  

---

## Viewing running processes

Show all running processes:

ps aux  

Display live system activity:

top  

If installed, a more user-friendly monitor:

htop  

---

## Stopping processes

Stop a process using its PID (process ID):

kill 1234  

Force stop an unresponsive process:

kill -9 1234  

---

## Background and foreground jobs

Run a command in the background:

sleep 100 &  

View background jobs:

jobs  

Bring a job to the foreground:

fg  

Send a job back to the background:

bg  

---

## Managing system services (systemd)

Check status of a service:

systemctl status sshd  

Start a service:

sudo systemctl start sshd  

Stop a service:

sudo systemctl stop sshd  

Enable a service at boot:

sudo systemctl enable sshd  

---

## Why this matters for cybersecurity

Security analysts often investigate:

- suspicious running processes  
- unauthorized services  
- malware persistence mechanisms  

Understanding process management is a **core defensive security skill**.
