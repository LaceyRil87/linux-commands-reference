# Search and text processing

## Goal
Learn how to find files, search inside logs, and filter command output.

These are core skills for:

- Cybersecurity investigations  
- Log analysis  
- Linux system administration  

---

## Finding files with find

Search for a file by name:

find / -name "hosts" 2>/dev/null  

Search for log files in the current directory:

find . -type f -name "*.log"  

---

## Searching text with grep

Find a word inside a file:

grep "error" file.txt  

Ignore uppercase vs lowercase:

grep -i "error" file.txt  

Search inside folders recursively:

grep -r "password" /etc 2>/dev/null  

---

## Pipes and redirection

Send output from one command into another:

cat file.txt | grep "success"  

Save command output to a file:

ls -la > listing.txt  

Append instead of overwrite:

echo "note" >> notes.txt  

Suppress error messages:

2>/dev/null  

---

## Common text tools

Count lines, words, and characters:

wc file.txt  

Sort lines alphabetically:

sort file.txt  

Remove duplicate lines:

uniq file.txt  

Extract specific fields:

cut -d ":" -f 1 /etc/passwd  

---

## Why this matters for cybersecurity

Security professionals must quickly:

- search massive log files  
- locate suspicious activity  
- filter important evidence  

Mastering grep and find is a **major Linux milestone**.
