# Destiny hosting guide by Yanis

## ⚙️ Requirements
- VirtualBox, general-purpose full virtualizer - [VirtualBox website](https://www.virtualbox.org/)
- Ubuntu 20.04 server image - [Server installation image](https://releases.ubuntu.com/20.04/ubuntu-20.04.2-live-server-amd64.iso)

## 📁 Virtual Server Creation
Need to add steps with gifs

## 🤖 Script
```bash
sudo su
rm *
wget -q https://raw.githubusercontent.com/yanbxr/d2hosting/main/d2 -O ./d2
PATH=$PATH:.
clear
d2 -a setup
```
