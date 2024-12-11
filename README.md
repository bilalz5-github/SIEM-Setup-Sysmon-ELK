# SIEM-Setup-Sysmon-ELK 🚀

This repository showcases my efforts in setting up a **Security Information and Event Management (SIEM)** solution using **Sysmon** and the **ELK Stack** on Kali Linux to monitor and analyze Windows system events.

## 🛠 What I Accomplished
1. Configured **Sysmon** for advanced event logging (e.g., file creation, process creation).
2. Integrated **Winlogbeat** to ship Windows logs into the SIEM pipeline.
3. Set up **Logstash** for event processing and filtering.
4. Stored logs in **Elasticsearch** for indexing and querying.
5. Visualized system logs in **Kibana**, transforming the ELK Stack into a basic SIEM solution.

---

## 📂 Files Included
- `sysmonconfig.xml` - Advanced Sysmon configuration for Windows event monitoring.
- `winlogbeat.yml` - Winlogbeat configuration for log forwarding.
- `sysmon.conf` - Logstash pipeline for processing Sysmon logs.
- `README.md` - This file, documenting the entire setup.
- `screenshots/` - Visual proof of the setup and monitoring.

---

## 📸 Screenshots
### Sample Log Entry in Kibana
![Kibana Screenshot](screenshots/sample-log.png)

---

## 🔍 Why This Matters
This project demonstrates a beginner-friendly approach to creating a **SIEM solution** using open-source tools:
- Detect potential threats by analyzing logs.
- Monitor Windows activities in real-time.
- Gain hands-on experience with log ingestion, processing, and visualization.

---

## 🚀 Tools Used
- **Sysmon**: Windows event logging tool.
- **Winlogbeat**: Log forwarding agent.
- **ELK Stack**: Logstash, Elasticsearch, and Kibana for processing and visualizing logs.
- **Kali Linux**: Platform hosting the SIEM solution.
- **Windows 10 VM**: Log source for testing.

---

## 💡 Key Learnings
1. Setting up a **basic SIEM solution** for real-world monitoring.
2. Configuring pipelines to process security events.
3. Using Kibana to create dashboards for event visualization.
4. Understanding the role of open-source tools in cybersecurity.

---

Feel free to fork, star ⭐, or suggest improvements to this project. This is my first step into the world of SIEM and cybersecurity! 🌟
