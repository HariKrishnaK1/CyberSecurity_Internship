# Task 5: Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective
To capture live network traffic on a Windows machine using **Wireshark**, identify and analyze various network protocols, and gain practical insight into how data flows across a network.

---

## 🛠 Tools Used
- [Wireshark](https://www.wireshark.org/) – Open-source network packet analyzer

---

## 🧠 What Was Done
1. Installed **Wireshark** on the Windows machine.
2. Started live capture on the **Wi-Fi interface** to record network traffic.
3. Generated traffic by browsing websites and pinging servers.
4. Stopped capture after ~1 minute and saved the file as `.pcapng`.
5. Identified and filtered packets based on protocols like:
   - **TCP**
   - **HTTP**
   - **DNS**
   - **TLSv1.2**
6. Trimmed the capture file (under 25 MB) for GitHub upload.
7. Summarized findings in `report.txt`.

---

## 📄 Files Included
- `wireshark_trimmed_traffic.pcapng` – Captured network traffic file
- `report.txt` – Analysis summary of captured packets
- `screenshots/` – Optional folder containing screenshots of filters and packets (if added)

---

## 🔍 Key Protocols Observed
| Protocol | Description |
|---------|-------------|
| **TCP** | Used for reliable data transfer (e.g., web pages, file downloads) |
| **HTTP** | Application layer protocol for web communication |
| **DNS** | Resolves domain names like `google.com` to IP addresses |
| **TLSv1.2** | Secure encrypted communication used in HTTPS |
| **ICMP** | Used for network diagnostics like `ping` |

---

## 🧠 Learning Outcome
- Understood how to capture live network traffic.
- Learned how to filter and interpret packet data using protocol filters.
- Gained hands-on experience with network-level troubleshooting and analysis.

---

## 📚 Key Concepts
- **Packet capture**
- **Protocol analysis**
- **Wireshark filtering**
- **TCP/IP model**
- **DNS and HTTP inspection**

---

## ✅ Status
✔️ Task Completed Successfully  
📁 All files uploaded to GitHub

