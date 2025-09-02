# 🕵️‍♂️ Network Packet Sniffer (Python + Scapy)

Built during my CodeAlpha Cybersecurity Internship, this tool captures and analyzes TCP, UDP, and ICMP packets in real time using Scapy on Kali Linux. It’s a foundational step into ethical hacking and low-level network inspection.

---

## 🔧 Features
- Real-time packet capture on active interface
- Protocol filtering (TCP, UDP, ICMP)
- Auto-trigger logic for specific IPs (e.g., Google DNS)
- Terminal-based output with packet summaries

---

## 📸 Screenshot
https://i.postimg.cc/T25bKCFZ/Screenshot-2025-09-02-18-31-30.png

---

## 🧪 Technical Breakdown
This sniffer uses Scapy’s low-level packet manipulation capabilities to:
- Intercept live traffic
- Parse Ethernet frames and IP headers
- Filter by protocol and trigger custom logic
- Display structured output for analysis

Modular design allows future extensions like:
- Logging to file or database
- Traffic visualization
- Suspicious packet detection

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Kali Linux (or any Linux distro)
- Scapy:  
  ```bash
  pip install scapy

