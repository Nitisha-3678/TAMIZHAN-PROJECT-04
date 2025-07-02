# Port Scanner using Python

This project is a simple yet effective **Port Scanner** built using Python's `socket` module. It scans for open ports on a target IP address and helps users understand basic network reconnaissance techniques.

---

## 📌 Features

- 🔍 Scans a range of ports (1–65535 or custom range)
- ⚡ Fast scanning using basic socket connections
- 💡 Displays open ports along with common service names
- 🧵 Optional multi-threading support (for speed optimization)
- ✅ Easy to use and fully CLI-based

---

## 🧠 Why This Project?

Port scanning is one of the first steps in penetration testing. This tool demonstrates how attackers identify vulnerable services — and how network defenders can detect and protect against unauthorized access.

---

## 🛠️ Requirements

- Python 3.x  
- No external libraries required (only built-in `socket` and `datetime`)

---
python port_scanner.py
Enter the target IP address and port range when prompted.

🧪 Sample Output
Target IP: 192.168.1.1
Scanning ports 1 to 100...

[+] Port 21 is open (FTP)
[+] Port 22 is open (SSH)
[+] Port 80 is open (HTTP)
Scan completed in 5.12 seconds.
⚙️ How It Works
Uses socket.connect_ex() to check if a port is open

Maps known ports to their typical services (e.g., 22 → SSH)

Measures scan time using datetime

Loops through the port range and logs open ports

📂 Project Structure
port-scanner/
└── port_scanner.py
📚 Learning Outcomes
Deepened understanding of:

TCP/IP communication

Open vs. closed ports

Common service ports (SSH, FTP, HTTP, etc.)

Gained hands-on experience with:

Python sockets

Network reconnaissance techniques

Basic scanning logic used in ethical hacking

🔐 Ethical Use
This tool is intended strictly for educational purposes.
Do NOT use it on networks or systems without explicit authorization.

👨‍💻 Built With
Python 3.x
Socket Programming
Guidance from #TamizhanSkills

🚀 Open to Opportunities
I'm actively learning and exploring the field of cybersecurity and network analysis, and I'm open to internship and project opportunities. Let’s connect!



