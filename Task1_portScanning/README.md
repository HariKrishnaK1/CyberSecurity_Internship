# Task 1 - Port Scanning using Nmap

## 🎯 Objective:
To perform a TCP SYN scan on the local network using Nmap and identify open ports, understand services, and evaluate potential security risks.

---

## 🛠️ Tools Used:
- Nmap
- (Optional) Wireshark
- Windows 11 (Dell Inspiron 3520)

---

## 🌐 Network Range Scanned:
192.168.48.0/24


---

## 📋 Open Ports Found on Local Machine:

| Port  | State | Service | Description                         |
|-------|-------|---------|-------------------------------------|
| 135   | Open  | RPC     | Remote Procedure Call used by Windows |
| 139   | Open  | NetBIOS | Legacy protocol for file sharing    |
| 445   | Open  | SMB     | Windows File & Printer Sharing      |
| 3306  | Open  | MySQL   | Open-source database server         |

---

## ⚠️ Potential Security Risks:

| Port  | Risk Level | Reason                                    | Recommendation                         |
|-------|------------|-------------------------------------------|-----------------------------------------|
| 139   | 🔴 High     | Vulnerable and outdated service           | Disable if not used                     |
| 445   | 🔴 High     | Common target for ransomware              | Block externally, disable if possible   |
| 3306  | 🟡 Medium   | Database exposure can lead to data theft  | Restrict access, use localhost only     |
| 135   | 🟢 Low      | Used by Windows but can be abused         | Monitor usage, block unnecessary traffic|

---

## ✅ Outcome:
- Gained hands-on experience with **TCP SYN scanning**
- Learned to identify services from open ports
- Understood basic network exposure and risk assessment
