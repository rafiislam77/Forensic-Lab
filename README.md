# DFIR Madness: The Case of the Stolen Szechuan Sauce

Welcome to my repository for "The Case of the Stolen Szechuan Sauce", a fictional digital forensics and incident response (DFIR) scenario designed to simulate a real-world cyber breach investigation. This project showcases my skills in DFIR methodologies, memory and disk forensics, malware analysis, and network investigation.
About the Case
BR
This engaging scenario revolves around the theft of a secret Szechuan sauce recipe leaked on the dark web. My goal was to identify the attack's entry point, analyze malware, map adversary infrastructure, and uncover the full extent of the breach.

### Key Questions Investigated:

    Was there a breach, and how did it occur?
    What malware was used, and what were its capabilities?
    Did the attacker access or steal sensitive data, and when?
    What were the malicious IP addresses and adversary infrastructure involved?
    What immediate and long-term security improvements could have prevented this attack?

Key Skills and Tools Demonstrated
Forensics Tools:

    FTK Imager Lite: For extracting system artifacts and disk images.
    Redline Collector: For memory analysis and incident artifact collection.
    Volatility Framework: Memory forensics, identifying malicious processes, and suspicious activity.
    Autopsy/Sleuth Kit: Disk analysis to identify file tampering, malware persistence, and timestamps.
    Wireshark: Network packet analysis for detecting adversary communications.

Incident Response Frameworks:

    NIST 7-Step Incident Response Process
    MITRE ATT&CK Framework

Key Techniques Used:

    Malware analysis: Identified payloads, persistence mechanisms, and command-and-control (C2) infrastructure.
    Log analysis: Correlated logs to identify unauthorized access and adversary activity.
    Timeline analysis: Reconstructed attack events to pinpoint key breaches and exfiltration points.
    Reporting: Created a detailed investigation report with actionable recommendations.

Artifacts Analyzed

    Disk Images (Server and Desktop)
    Memory Dumps (Server and Desktop)
    PCAP Files for Network Activity
    Autorun Configurations

Key Findings

    Operating Systems: The server ran Windows Server 2012, and the desktop used Windows 10.
    Initial Entry Vector: Exploitation of a known vulnerability in outdated software.
    Malware Identified: A custom payload with persistence mechanisms and C2 communication.
    Data Breach: Exfiltration of sensitive files, including the Szechuan sauce recipe, Beth’s secret files, and other sensitive data.
    Adversary IPs: Linked to known malicious infrastructure actively used in other attacks.

Lessons Learned

This case reinforced the importance of:

    Regular system updates and patch management.
    Enhanced monitoring using SIEM and centralized log management.
    Employee awareness training to mitigate phishing and other social engineering tactics.
    Strong access controls and network segmentation.

How to Use This Repository

This repository includes:

    Artifacts Analysis: Step-by-step investigation notes and screenshots.
    Malware Analysis Reports: Detailed insights into identified malware and its behavior.

Feel free to explore and use this project as a learning resource for improving your DFIR skills!
Contact

For questions or feedback, please feel free to reach out via  <a href="https://www.linkedin.com/in/rashedulrafi/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a> 

Let me know if you'd like further customization or additions to this description!
