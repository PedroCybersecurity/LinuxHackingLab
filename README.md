# Linux Hacking Lab

## Overview
This repository documents the steps and commands used to perform a basic Linux hacking task as part of TryHackMe's room. The task involves gaining unauthorized access to a target Linux system through reconnaissance, FTP server interaction, and privilege escalation.

## Lab Tasks
1. Reconnaissance: Use Nmap to discover open ports and services on the target system.
2. FTP Server Interaction: Connect to the FTP server, discover a hidden password, and access files.
3. Privilege Escalation: Gain root access to the target Linux system using the discovered password.

## Implementation Details
- Reconnaissance: Utilized Nmap to scan for open ports and services.
- FTP Server Interaction: Connected to the FTP server, discovered a hidden password in `secret.txt`, and accessed files.
- Privilege Escalation: Used the discovered password to gain root access to the target Linux system.

## Lab Results
- Password in `secret.txt`: ABC789xyz123
- Content of `flag.txt` in the `/root` directory: THM{FTP_SERVER_OWNED}
- Content of `flag.txt` in the `/home/librarian` directory: THM{LIBRARIAN_ACCOUNT_COMPROMISED}

The provided commands and steps demonstrate a basic Linux hacking scenario and are for educational purposes only. Always ensure you have legal authorization before attempting any form of penetration testing or ethical hacking.
