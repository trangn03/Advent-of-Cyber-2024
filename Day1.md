# OPSEC
1. To quickly determine file's content, use ```file```
2. There are multiple ways to inspect ```.lnk``` files to reveal the embedded commands and attributes.
3. The ```-ep Bypass -nop``` flags disable PowerShell's usual restrictions, allowing scripts to run without interference from security settings or user profiles.
4. The ```DownloadFile``` method pulls a file from a remote server and saves it in the ```C:\\ProgramData\\ ```directory on the target machine.

## Introduction to OPSEC
- A term orginally coined in the military to refer to the process of protecting sensitive information and operations from adversaries
- **Goal**: identify and eliminate potential vulnerabilities before the attacker can learn their identity
- Common OPSEC mistakes
  - Reusing usernames, email addresses, or account handles across multiple platforms. One might assume that anyone trying to cover their tracks would remove such obvious and incriminating information, but sometimes, it's due to vanity or simply forgetfulness.
  - Using identifiable metadata in code, documents, or images, which may reveal personal information like device names, GPS coordinates, or timestamps.
  - Posting publicly on forums or GitHub (Like in this current scenario) with details that tie back to their real identity or reveal their location or habits.
  - Failing to use a VPN or proxy while conducting malicious activities allows law enforcement to track their real IP address.

**AlphaBay Admin Takedown**
- One of the most spectacular OPSEC failures involved Alexandre Cazes, the administrator of AlphaBay, one of the largest dark web marketplaces