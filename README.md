# 🛡️ Ethigotchi - AI-Powered Wireless Security Companion  

![Ethigotchi](https://i0.wp.com/efcomputer.net.au/blog/wp-content/uploads/2024/06/20240607_pwnagotchi.jpg?ssl=1)

## 📌 Overview  
**Ethigotchi** is an AI-powered wireless security companion, inspired by **Pwnagotchi**, designed for **Wi-Fi security analysis and ethical hacking**. It leverages machine learning and automation to detect vulnerabilities in wireless networks, making it a valuable tool for cybersecurity enthusiasts and penetration testers.  

## 🚀 Features  
✔️ **Automated Wi-Fi Packet Capture** - Sniffs wireless traffic for analysis.  
✔️ **AI-Driven Learning** - Improves attack efficiency based on past results.  
✔️ **Raspberry Pi Zero W Compatible** - Runs on a lightweight, portable device.  
✔️ **E-Ink Display Integration** - Displays real-time stats and system updates.  
✔️ **Customizable Security Modes** - Passive monitoring and active penetration testing.  
✔️ **Remote Access & Logging** - SSH and web-based access for control.  

## 🛠️ Hardware Requirements  
To set up Ethigotchi, you’ll need:  
🔹 **Raspberry Pi Zero Wireless WH** (Pre-Soldered Header)  
🔹 **Waveshare 2.13-inch E-Paper Display**  
🔹 **MicroSD Card** (Min 8GB, Class 10 Recommended)  
🔹 **External Power Bank / 1000mAh Battery Pack**  
🔹 **Wireless Dual-Band MU-MIMO WiFi USB Adapter** (For Monitor Mode)  

## 📦 Installation  
### 1️⃣ **Flash Raspberry Pi OS**  
Download and install **Raspberry Pi OS Lite** on your microSD card using [Raspberry Pi Imager](https://www.raspberrypi.org/software/).  

### 2️⃣ **Set Up Dependencies**  
SSH into your Pi and install required packages:  
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install python3-pip aircrack-ng hcxdumptool hcxtools screen
