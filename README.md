# 🚀 Wireless Intrusion Detection System (WIDS) using Snort

A cybersecurity project focused on detecting real-time wireless attacks on IEEE 802.11 (Wi-Fi) networks using Snort IDS.

---

## 📌 Overview

This project implements a **Wireless Intrusion Detection System (WIDS)** in a controlled lab environment. It monitors wireless traffic and detects common attacks such as:

- De-authentication Flood (DoS)
- Disassociation Attacks
- WPA/WPA2 Handshake (EAPOL) Brute Force
- Probe Request Storms
- MAC Spoofing

---

## 🛠️ Tools & Technologies

- Snort (IDS Engine)
- Kali Linux
- Wireshark
- Aircrack-ng Suite
- MDK4
- Python 3

---

## ⚙️ Features

- Real-time packet analysis using Snort  
- Custom IDS rules for wireless attack detection  
- Monitor-mode Wi-Fi traffic capture  
- Python-based alert log parser  
- Detection accuracy ~93% in lab environment  

---

## 📂 Project Structure

- `snort/` → Configuration & custom rules  
- `scripts/` → Python parser script  
- `screenshots/` → Output & alerts proof  
- `docs/` → Full project report  

---

## ▶️ Setup & Usage

### 1. Install Snort
```bash
sudo apt update
sudo apt install snort -y
```

### 2. Enable Monitor Mode
```bash
sudo airmon-ng check kill
sudo airmon-ng start wlan0
```

### 3. Run Snort
```bash
sudo snort -i wlan0mon -c /etc/snort/snort.conf -A console
```

---

## 🧪 Sample Detection

- De-authentication attack detected using MDK4  
- EAPOL brute-force detected during WPA handshake capture  

---

## 📊 Results

- Detection Accuracy: ~93.6%  
- Real-time alert generation  
- Low false positive rate  

---

## ⚠️ Disclaimer

This project is developed strictly for **educational purposes** in a controlled lab environment. Do NOT use on unauthorized networks.

---

## 🤝 Team

- Syed Ashir Nasveer  
- Albash Ahmed  
- Muhammad Noor-ul-Hassan  

---

## 🔗 Connect with Me

- LinkedIn: (your link)
- GitHub: https://github.com/COD3R3XPLOIT

---

⭐ If you like this project, give it a star!
