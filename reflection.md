# Reflection – picoCTF Annual Challenge 2026

## Activity Description
The objective of this activity was to participate in the picoCTF 2026 cybersecurity competition and solve challenges that simulate real-world security scenarios. I began participating a few days into the event and focused primarily on challenges within the “General Skills” category. Despite the category name, these challenges involved interacting with live services, analyzing system behavior, and identifying vulnerabilities in networked environments.

## Technical Decisions
Throughout the competition, I utilised an enumeration-first approach. When connecting to remote services such as SMB, I began by identifying available shares, accessible files, and valid users before attempting further interaction. Tools such as `smbclient`, `rpcclient`, and `nc` were used to gather information and understand the system structure.

One key decision was to prioritize logical exploitation over brute-force techniques. In one challenge, rather than attempting password cracking, I identified a writable script executed by a cron job. I modified the script to execute commands and write output to a log file, allowing me to explore the system and locate the flag. This approach was significantly more efficient than attempting blind or time-consuming attacks.

Additionally, I made the decision to drop a challenge that relied heavily on slow brute-force methods with limited feedback. This allowed me to focus on challenges with clearer vulnerability paths and maximize progress within the limited time available.

## Contributions
This activity was completed individually. I was responsible for all aspects of participation, including service enumeration, vulnerability identification, exploitation, and documentation. All work was performed in a Kali Linux environment using standard command-line tools.

## Quality Assessment
I would assess my participation as effective given the constraints. Despite starting late, I achieved a score of 2350 and ranked 1986 out of 8756 participants. I successfully solved multiple challenges that required multi-step reasoning and practical application of cybersecurity concepts.

If I were to repeat this activity, I would begin earlier and allocate time more strategically across challenge categories. I would also incorporate lightweight automation to improve efficiency in repetitive tasks such as enumeration and data collection.

Overall, this activity reinforced my ability to analyze systems, identify misconfigurations, and apply practical techniques to solve security problems in a time-constrained environment.