# ⚡ CreebNet VPN AutoScript (Premium Edition)

![Version](https://img.shields.io/badge/Version-v2.0_Stable-cyan?style=for-the-badge) 
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge) 
![Platform](https://img.shields.io/badge/Platform-Ubuntu_&_Debian-orange?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-Enterprise_Grade-red?style=for-the-badge)

**The Ultimate High-Performance VPN Autoscript.** Built for elite tunneling, seamless bypassing of strict ISP firewalls, and enterprise-grade server stability. Features intelligent traffic multiplexing, auto-healing daemons, multi-login anti-abuse systems, Telegram integration, and support for the latest generation of Xray and SSH protocols.

---

## 🚀 Key Features

Our script integrates an arsenal of elite tunneling protocols engineered to effortlessly bypass the most restrictive Deep Packet Inspection (DPI) and ISP firewalls globally. By multiplexing high-speed payloads over standard ports (like 80 and 443) and utilizing advanced WebSocket and gRPC routing, it guarantees ultra-low latency, unbreakable connections, and military-grade stealth—whether you're gaming, streaming, or securing enterprise data.

### 💎 Supported Protocols & Ports

| Protocol / Service | Port | Description |
| :--- | :--- | :--- |
| **Nginx** | `81` | Core web server & reverse proxy |
| **OpenSSH** | `22` | Standard Secure Shell |
| **Dropbear** | `109`, `143`, `179` | Lightweight SSH server |
| **Stunnel4** | `447`, `448`, `777` | Universal SSL/TLS tunneling |
| **HAProxy** | `8888`, `8880`, `2095` | High availability TCP/HTTP load balancer |
| **OHP** | `8000`, `8181`, `8087` | Open HTTP Proxy for payload injection |
| **Websocket HTTP** | `80`, `8080`, `8880` | Plain WebSocket tunneling |
| **Websocket SSL TLS** | `443`, `2053`, `8443` | Encrypted WebSocket tunneling |
| **BadVPN UDPGW** | `7100-7300` | UDP Gateway for gaming and voice calls |
| **Http/Sock5 Proxy** | `3128`, `1080` | Standard and secure proxying |
| **Ovpn Tcp** | `119` | OpenVPN via TCP |
| **Ovpn Udp** | `2200` | OpenVPN via UDP |
| **Dnstt (SlowDNS)** | `52`, `5300` | DNS Tunneling |
| **Ssh Udp** | `1-65535` | Full range UDP support over SSH |
| **XRAYS Vmess TLS** | `443` | VMess over TLS |
| **XRAYS Vmess GRPC** | `443` | VMess over gRPC |
| **XRAYS Vmess None TLS** | `80` | Plain VMess |
| **XRAYS Vless TLS** | `443` | VLESS over TLS |
| **XRAYS Vless GRPC** | `443` | VLESS over gRPC |
| **XRAYS Vless None TLS** | `80` | Plain VLESS |
| **XRAYS Trojan TLS** | `443` | Trojan over TLS |
| **XRAYS Trojan GRPC** | `443` | Trojan over gRPC |

### 🛡️ Smart Automation & Security

* 🌐 **Cloudflare WARP Routing Engine:** Seamlessly routes VPN traffic through the Cloudflare WARP network. Unlocks geo-restricted streaming (Netflix, Hulu) and masks your server IP with clean Cloudflare IPs.
* 📱 **Full Telegram Bot Management:** Complete remote administration via Telegram. Create users, check bandwidth, lock accounts, and manage the server from your phone without ever opening an SSH terminal.
* 🧹 **Automated Ghost-Account Sweeper:** A self-cleaning daemon that automatically hunts down and wipes out expired users at midnight, keeping the server database clean, fast, and secure.
* ⚡ **1-Click Free Trial Generator:** Built-in trial generators for all protocols, allowing server owners to instantly create 1-hour or 24-hour test accounts to attract new clients.
* 🤖 **Autonomous Auto-Heal Engine:** Background daemons actively monitor core services (Nginx, Xray, SSH). If a service crashes or memory spikes, the engine automatically restarts the process to prevent downtime.
* ☁️ **Cloud Backups:** Seamlessly backup your server configurations and user data to Telegram. Restore your server instantly on a new node via cloud recovery.
* 🚫 **Aggressive Anti-Multilogin (Autokill):** Advanced cron-based sniper daemon (running every 2 minutes) actively hunts live Dropbear/OpenSSH PIDs. Automatically terminates and locks users who exceed their device limits.
* 🧱 **Fail2Ban & DDoS Protection:** Hardened system firewall actively mitigates brute-force SSH attacks, blocks malicious network floods, and integrates with Cloudflare WAF/WASP for maximum perimeter defense.
* 🛑 **Anti-Torrent Protection:** Deep packet inspection drops BitTorrent traffic to prevent DMCA takedowns and ISP flagging, keeping your server IP clean.
* 🎨 **WebPanel GUI & Custom Banners:** Manage your node via a clean, intuitive WebPanel GUI. Easily set up custom SSH login banners and connection messages for your users.
* 📊 **Smart Quota & Bandwidth Engine:** Actively monitors byte-level bandwidth consumption and automatically halts network access when users reach their specific GB limit. 

---

## ⚙️ System Requirements

* **Supported OS:** Ubuntu (20.04 / 22.04 / 24.04 LTS) and Debian (10 / 11 / 12)
* **Architecture:** AMD64 / x86_64
* **Privileges:** `root` access required for installation and daemon management.

---

## 📥 Installation

### Simple Installer

**1. Package updates**
```bash
apt update && apt upgrade -y
```

**2. Script installer**
```bash
curl wget jq && wget -qO setup https://raw.githubusercontent.com/creebchamp/CreebAutoScript/main/setup && chmod +x setup && sudo ./setup
```

**3. Alt script installer**
```bash
wget jq && wget -qO setup https://raw.githubusercontent.com/creebchamp/CreebAutoScript/main/setup && chmod +x setup && sudo ./setup
```

### Single Auto-installer

```bash
apt update && apt install -y curl wget jq && wget -qO setup https://raw.githubusercontent.com/creebchamp/CreebAutoScript/main/setup && chmod +x setup && sudo ./setup
```

---

## 🔑 License Activation

To use this script, you will need a valid license key. Click the button below to get your license key instantly from our Telegram bot!

[![Get License Key](https://img.shields.io/badge/Get_License_Key-Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/Creebnetbot)

---

## 📜 Disclaimer
This script is provided for educational and internal infrastructure management purposes only. Users are strictly responsible for their own network compliance and usage.
