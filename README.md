# nmap-recon-project
Nmap Recon Project – Host Discovery, Port Scanning, OS Detection + Report Files
Nmap Reconnaissance Project

This project demonstrates practical reconnaissance techniques using Nmap.
It includes host discovery, port scanning, service detection, OS fingerprinting, and saving scan outputs in multiple formats.

1. Objective of the Project
Learn & implement recon techniques
Understand TCP/UDP port behavior
Capture real scan outputs
Analyse services running on a target
Build a cybersecurity portfolio project

2. Tools Used
Nmap (Network Mapper)
Kali Linux / Linux Terminal

3. Commands Used
basic scan --> nmap <target-ip>
Service & version detection --> nmap -sV <target-ip>
OS detection --> nmap -O <target-ip>
Aggressive full recon (recommended) --> nmap -A <target-ip>
Save results in 3 formats (TXT, GNMAP, XML) --> nmap -sV -O -oA scan <target-ip>

4. Output Files Description
File              purpose
scan.txt          Human-readable scan results
scan.gnmap        Machine readable → import into tools
scan.xml          Output suitable for scripting/grep

5. Key Findings Form Scans
2 open ports found
tcpwrapped service running
OS details -- Apple iOS 15.0 - 15.6
host is up with 0.014 latency

6. What I Learned
How recon works
How attackers enumerate services
How to save/import scan data
How to detect OS and service versions
How to document a cybersecurity projec
