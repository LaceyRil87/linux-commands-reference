# Networking essentials

## Goal
Understand how to check IP addresses, test connectivity, inspect ports, and make web requests in Linux.

These skills are critical for:

- IT support troubleshooting  
- Network diagnostics  
- Cybersecurity investigations  

---

## IP address and routing

Show IP address information:

ip a  

Show routing table:

ip route  

---

## Connectivity testing

Ping a public server 4 times:

ping -c 4 8.8.8.8  

Trace the network path to a host:

traceroute google.com  

---

## DNS lookups

Query DNS using nslookup:

nslookup example.com  

Advanced DNS query tool:

dig example.com  

---

## Checking open ports and listening services

Show listening TCP and UDP ports:

ss -tuln  

Show ports with process names:

ss -tulpn  

---

## Making web requests

Fetch a web page:

curl https://example.com  

Fetch only headers:

curl -I https://example.com  

Download a file:

wget https://example.com/file.zip  

---

## Why this matters for cybersecurity

Security professionals constantly:

- verify network connectivity  
- identify exposed services  
- inspect suspicious traffic  
- test reachable systems  

Networking knowledge is the **foundation of penetration testing and defense**.
