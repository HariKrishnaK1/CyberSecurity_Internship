# Open Ports Explained

This file contains a breakdown of the ports discovered during the Nmap scan and their purpose.

---

## 🔎 Detected Open Ports:

| Port | Protocol | Service Name | Description                                      |
|------|----------|--------------|--------------------------------------------------|
| 135  | TCP      | RPC          | Microsoft Remote Procedure Call - used for communication between applications on Windows |
| 139  | TCP      | NetBIOS      | Used in older Windows systems for file and printer sharing |
| 445  | TCP      | SMB          | Server Message Block - shares files, printers, etc. |
| 3306 | TCP      | MySQL        | MySQL database server port for remote connections |

---

## 🧠 Why These Matter:

- **RPC (135)**: Required for many Windows processes, but may be exploited for lateral movement in a network.
- **NetBIOS (139)**: Old protocol that has known vulnerabilities; rarely needed today.
- **SMB (445)**: Frequently targeted by malware and ransomware (e.g., WannaCry).
- **MySQL (3306)**: Should not be exposed publicly; must be protected with strong credentials and IP restrictions.

---

## 🔐 Security Recommendations:

- **Close unnecessary ports**
- **Use firewalls to block external access**
- **Keep systems updated**
- **Disable legacy services like NetBIOS if not needed**
