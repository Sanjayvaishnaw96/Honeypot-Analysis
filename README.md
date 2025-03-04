# Honeypot-Analysis
Project Description:
🛡️ Honeypot-Based Cybersecurity Lab
This project sets up a practical lab environment using 3 virtual machines:

Kali Linux (Attacker Machine)
Ubuntu Honeypot (Deliberately Vulnerable Server)
Ubuntu Secure Server (Actual Production Machine)
🔍 Key Features:

SSH, HTTP, SMB, FTP Setup: Configured services on both machines — one secure and one deliberately vulnerable as a honeypot.
Firewall Rules: Strict firewall rules on the secure machine and intentionally loose rules on the honeypot to attract attackers.
Attack Scenarios: Simulating real-world attacks like dictionary attacks, SQL injection, DoS, and SMB/FTP exploitation.
Logging & Monitoring: Using Wazuh to monitor live attacks and generate alerts.
🎯 Purpose:
This project is perfect for red team and blue team practices — allowing you to perform live attacks and build defenses against them.

