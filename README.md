               # 🌟 POOKIE CLOUD VPS Bot
A fully automated Discord bot for creating and managing LXC/LXD VPS containers.

Made by SHIFA for POOKIE CLOUD

✨ Features
Create, delete, resize, suspend and reinstall VPS containers from Discord
Port forwarding and SSH access for every VPS
Multi-node support
Admin and main-admin controls
Runs 24/7 as a systemd service
📋 Requirements
A fresh Ubuntu or Debian VPS/server with root access (KVM or dedicated recommended)
A Discord Bot Token from the Discord Developer Portal
Your Discord User ID
In the Developer Portal → Bot tab, enable all three Privileged Gateway Intents (Presence, Server Members, Message Content).

🚀 Installation

Run these commands as root on your VPS:

```
apt update && apt install git -y
git clone https://github.com/PookieCloud/PookieCloud-VPS-BOT.git
cd PookieCloud-VPS-BOT
chmod +x install.sh
./install.sh
```
