# 🛡 CipherHawk - Ultimate Network Anonymizer

![Status](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.x-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 🔍 Overview
CipherHawk enhances **privacy and security** by automatically randomizing **MAC Address, IP, Hostname, and DNS** every few seconds, making your device **harder to track** without VPNs or proxies.

## ✨ Features
- 🔄 **MAC Address Spoofing** – Changes MAC address dynamically.
- 🌍 **Public IP Randomization** – Forces a new IP address.
- 🔀 **Hostname Spoofing** – Randomizes system identity.
- 🛡 **DNS Leak Protection** – Prevents DNS-based tracking.
- 🚀 **Fully Automated** – Runs in the background with zero setup.

## 🛠 Installation
### **Prerequisites**
- 🐍 Python 3.x
- 📦 Pip & Virtual Environment
- 💻 Admin Privileges (Required for network modifications)

### **Setup**
```sh
git clone https://github.com/kdandy/CipherHawk.git
cd CipherHawk
```

### Create and activate virtual environment
```sh
python3 -m venv .venv
source .venv/bin/activate  # macOS/Linux
.venv\Scripts\activate     # Windows
```

### Install dependencies
```sh
pip install -r requirements.txt
```

## 🚀 Usage
Run with root privileges to enable full anonymization:
```sh
sudo python3 CipherHawk.py
```

## 📊 Example Output
| 🌐 New Public IP	| 🎭 MAC Address        | 🔀 Hostname    |
|--------------------|----------------------|----------------|
| 192.168.1.45      | 	02:3A:4B:5C:6D:7E   | Anon-4821      |
| 192.168.1.98      |   02:7F:2C:9D:8A:6B   | Anon-9234      |

## ⚠️ Disclaimer
This tool is intended for privacy enhancement and security research only. Unauthorized use may violate local laws.

## 📜 License
📝 MIT License
