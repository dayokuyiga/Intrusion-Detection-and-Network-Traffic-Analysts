# Lab 1 – Intrusion Detection and Network Traffic Analysis

This lab focuses on analyzing a network capture (PCAP) file to determine whether a suspicious or malicious event occurred within a home network. The analysis was performed using Wireshark, Network Miner, and SNORT within a virtualized lab environment (SimSpace).

## 🧪 Objectives
- Interpret and analyze PCAP files using industry-standard tools.
- Detect abnormal traffic patterns or intrusion indicators.
- Identify the devices and services communicating on the local network.
- Document packet-level findings and correlate them to possible threats.

## 🔧 Tools Used
- Wireshark
- Network Miner
- SNORT
- SimSpace Cyber Range

## 📈 Key Findings
- **Capture Duration**: 8 minutes and 43 seconds
- **Total Packets**: 2,449
- **Protocols Observed**: UDP, TCP, HTTP, IPv4
- **Host Computer**: `KaufmanUpstairs` – IP `172.16.1.35`
- **Operating System**: Windows OS identified via host scan
- **Data Spike**: Major spike at ~5:31 PM lasting ~30 seconds
- **ISP Interaction**: Notable access to MSN (Microsoft services)

## 🧠 Summary
The traffic spike was identified and analyzed using Wireshark and correlated with endpoint communication using Network Miner. Based on the data flow and service communication, no concrete evidence of malicious activity was confirmed. However, the spike in traffic suggests the need for further behavioral baselining.

## 📂 Project Files

- 📄 [Lab Instructions (PDF) - [ISCS_3523_Lab 4 Attack Analysis (1).pdf](https://github.com/user-attachments/files/20493537/ISCS_3523_Lab.4.Attack.Analysis.1.pdf)
- 📄 [My Full Analysis Report (PDF) - [Okuyiga_qvj870_3523_lab01.pdf](https://github.com/user-attachments/files/20493615/Okuyiga_qvj870_3523_lab01.pdf)


## 📚 References
- SimSpace Cyber Range
- [Weber Blog – Intro to NetworkMiner](https://weberblog.net/intro-to-networkminer/)
