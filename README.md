# picoCTF Annual Challenge 2026

## Overview
This repository documents my participation in the **picoCTF 2026 Annual Challenge**, a cybersecurity competition focused on solving practical, hands-on challenges across multiple domains.

The purpose of this activity was to apply technical skills in a real-world problem-solving environment and reflect on the decisions, strategies, and outcomes of my participation.

---

## Event Information
- **Event:** picoCTF 2026 Annual Challenge  
- **Platform:** picoCTF  
- **Participation:** Individual    
- **Final Score:** 2350 points  
- **Global Rank:** 1986 / 8756  

---

## Activity Description
The goal of this activity was to solve cybersecurity challenges that simulate real-world scenarios involving system misconfigurations, network services, and data analysis.

I primarily focused on challenges in the **General Skills** category, which included:
- Interacting with network services (e.g., SMB, netcat)
- Exploring remote file systems
- Identifying and exploiting misconfigurations
- Analyzing automated processes such as cron jobs

Although labeled as “General Skills,” many of these challenges required multi-step problem solving and practical exploitation techniques.

---

## Technical Approach
My general approach to solving challenges followed these steps:

1. **Enumeration First**
   - Identify available services, files, and users
   - Use tools such as `smbclient`, `rpcclient`, and `nc`

2. **Analyze System Behavior**
   - Understand how services are configured
   - Look for unintended access or exposed functionality

3. **Exploit Misconfigurations**
   - Writable scripts
   - Public vs. private access controls
   - Scheduled task execution (cron jobs)

4. **Avoid Inefficient Paths**
   - Dropped challenges that relied heavily on slow brute-force methods
   - Focused on challenges with clear logical or structural weaknesses

---

## Key Skills Demonstrated
- Network service enumeration (SMB, RPC)
- File system navigation and analysis
- Identifying insecure configurations
- Exploiting automation (cron-based execution)
- Efficient problem-solving under time constraints
- Use of Linux command-line tools in a Kali environment

---

## Notable Challenges

### Printer Shares Series
- Enumerated SMB shares and accessed public resources
- Identified valid users through RPC queries
- Exploited writable scripts executed by cron jobs
- Extracted system data and flags from restricted directories

This series demonstrated how small misconfigurations can lead to full system exposure.

---

## Proof of Participation
Screenshots included in this repository:
- Scoreboard (rank and score)
- CTF completion tracker

---

## Reflection
A full reflection of this activity is included in `reflection.md`, covering:
- Technical decisions made during challenges
- Individual contributions
- Evaluation of performance
- Improvements for future participation

---

## Conclusion
This activity provided practical experience in analyzing and exploiting system vulnerabilities in a controlled environment. Despite starting late, I was able to successfully solve multiple medium-difficulty challenges and demonstrate strong problem-solving and technical reasoning skills.

If repeated, I would begin earlier and incorporate more automation to improve efficiency and maximize performance.
