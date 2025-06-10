# 🧠 Complete CTF Learning Curriculum

> Author: KaliGPT  
> Target Audience: Beginners to Intermediate CTF Players  
> Format: Tiered curriculum for building practical hacking skills

---

## 1. 🐧 Linux & Bash

### Why?
Linux is the foundation of almost every CTF environment.

### Topics:
- Basic shell navigation (`ls`, `cd`, `cat`)
- File permissions and user rights
- Bash scripting (loops, variables, redirection)
- Package management (`apt`, `pip`)

### Resources:
- OverTheWire: Bandit
- https://linuxcommand.org

---

## 2. 🐍 Python & Scripting

### Why?
Python helps automate exploitation, parsing, and solving challenges.

### Topics:
- Syntax, file handling, subprocess
- Argument parsing with `argparse`
- HTTP requests (`requests`)
- Regex, encoding/decoding

### Resources:
- Python.org Official Tutorial
- TryHackMe: Python Basics

---

## 3. 🔐 Cryptography

### Why?
Many CTFs hide flags with weak or classical encryption.

### Topics:
- Base64, Hex, Binary, ROT13
- Caesar, Vigenère, XOR cipher
- Hashing: MD5, SHA1
- Public-key vs symmetric encryption

### Tools:
- CyberChef
- Hashcat
- John the Ripper

### Resources:
- https://cryptohack.org
- CTFlearn: Crypto section

---

## 4. 🕵️ Steganography & OSINT

### Why?
Flags are often hidden in media files or metadata.

### Topics:
- EXIF data in images
- Strings, hex viewers
- File carving and signature detection

### Tools:
- `stegsolve`, `zsteg`, `binwalk`, `exiftool`

### OSINT Tools:
- Google Dorking
- theHarvester, Maltego

### Resources:
- StegOnline
- OSINTFramework.com

---

## 5. 🌐 Web Exploitation

### Why?
Web is one of the most frequent categories in CTFs.

### Topics:
- HTML, HTTP, cookies, sessions
- SQL Injection (classic, blind)
- XSS (stored, reflected)
- Directory traversal
- Command injection

### Tools:
- Burp Suite
- curl, Postman

### Resources:
- PortSwigger Web Academy
- TryHackMe: Web Fundamentals
- DVWA

---

## 6. 🔁 Reverse Engineering

### Why?
Understand and dismantle binaries to find hidden logic.

### Topics:
- Strings, symbols, function flow
- Static vs dynamic analysis
- Decompilation

### Tools:
- Ghidra
- IDA Free
- Radare2

### Resources:
- Crackmes.one
- picoCTF Reversing Path

---

## 7. 💣 Binary Exploitation (Pwn)

### Why?
Some of the most rewarding and technical CTF challenges.

### Topics:
- Stack layout, buffer overflows
- Calling conventions
- Shellcode and NOP sleds
- Format string vulnerabilities

### Tools:
- GDB, pwndbg
- pwntools
- ROPgadget

### Resources:
- OverTheWire: Protostar
- ROP Emporium

---

## 8. 🔍 Forensics

### Why?
Analyze digital artifacts like memory dumps, PCAPs, disk images.

### Topics:
- File recovery
- Network packet analysis
- Memory forensics

### Tools:
- Wireshark
- Volatility
- Autopsy

### Resources:
- TryHackMe Forensics Room
- Remnux Toolkit

---

## 9. 🧠 Operating Systems Concepts

### Why?
To exploit systems effectively, you must understand how they work.

### Topics:
- Processes & threads
- Virtual memory, paging
- System calls and I/O
- File systems

### Book:
- **Operating Systems: Three Easy Pieces** (OSTEP)

---

## 10. 🌐 Networking Fundamentals

### Why?
Exploiting networks and analyzing traffic is core to many CTFs.

### Topics:
- TCP/IP, ports, UDP
- ARP, DNS, DHCP
- HTTP headers & methods
- NAT, VPN, Firewall basics

### Tools:
- Wireshark
- tcpdump, nmap

### Resources:
- PracticalNetworking.net
- HTB Academy: Networking Basics

---

## 11. 🧱 Computer Architecture

### Why?
Essential for reverse engineering and pwn challenges.

### Topics:
- CPU registers
- Stack vs heap
- Assembly (x86, x64)
- Instruction pipelines

### Book:
- **Computer Systems: A Programmer’s Perspective**

---

## 12. 🗃️ Databases & SQL

### Why?
SQL Injection and DB forensics are common in Web CTFs.

### Topics:
- SQL syntax, subqueries
- UNION, SELECT, ORDER BY
- Blind SQLi and time-based inference

### Tools:
- sqlmap
- SQLite Browser

### Resources:
- PortSwigger SQLi Labs
- TryHackMe: SQL Injections

---

## 🏁 Suggested Progression Path

1. Linux & Python
2. Crypto, Stego, Web
3. OSINT & Forensics
4. Reverse Engineering
5. Databases
6. Binary Exploitation
7. OS, Networking, and Architecture

---

## 🎯 Platforms to Practice

- [picoCTF](https://picoctf.org)
- [CTFlearn](https://ctflearn.com)
- [Hack The Box](https://hackthebox.com)
- [TryHackMe](https://tryhackme.com)
- [Root Me](https://root-me.org)

---

*Built by KaliGPT — Stay legal. Stay ethical. Hack wisely.*
