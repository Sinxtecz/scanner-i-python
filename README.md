# 🔎 Nmap IP Scanner

A simple Python-based terminal tool that uses **Nmap** to scan an IP address and display information about the target.

Built as a beginner cybersecurity project to practice **Python + Linux + Nmap automation**.

```text
 ███████╗██╗███╗   ██╗██╗  ██╗████████╗███████╗ ██████╗███████╗
 ██╔════╝██║████╗  ██║╚██╗██╔╝╚══██╔══╝██╔════╝██╔════╝╚══███╔╝
 ███████╗██║██╔██╗ ██║ ╚███╔╝    ██║   █████╗  ██║       ███╔╝
 ╚════██║██║██║╚██╗██║ ██╔██╗    ██║   ██╔══╝  ██║      ███╔╝
 ███████║██║██║ ╚████║██╔╝ ██╗   ██║   ███████╗╚██████╗███████╗
 ╚══════╝╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚═════╝╚══════╝

                 N M A P   I P   S C A N N E R
```

## ⚙️ Features

* 🌐 Takes an IP address from the user
* 🔎 Runs an Nmap scan
* 💻 Displays the results directly in the terminal
* 🐍 Written in Python
* 🧪 Useful for learning Nmap automation

## 📦 Requirements

* Python 3
* Nmap
* Linux/Kali Linux recommended

Check Python:

```bash
python3 --version
```

Check Nmap:

```bash
nmap --version
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/nmap-ip-scanner.git
cd nmap-ip-scanner
```

Run the tool:

```bash
python3 scanner.py
```

Enter an IP address when prompted:

```text
[+] Enter target IP: 192.168.1.1
```

The script will run Nmap and display the scan results.

## 🛠️ How It Works

The tool uses Python's `subprocess` module to execute Nmap from the terminal.

```text
User
  │
  ▼
Enter IP Address
  │
  ▼
Python Script
  │
  ▼
Nmap Scan
  │
  ▼
Terminal Results
```

## 🎯 Purpose

This project was made for **learning and authorized security testing**.

Use it only against systems you own or have explicit permission to scan.

## 👤 Author

**Sinxtecz**

Learning Python, Linux, networking and cybersecurity.

```text
[+] Keep learning
[+] Keep building
[+] Keep hacking ethically
```
