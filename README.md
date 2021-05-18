# Destiny Hosting

## ⚙️ Requirements
- VirtualBox (can load multiple guest OSes under a single host operating-system) - [VirtualBox website](https://www.virtualbox.org/)
- Ubuntu 20.04 server image - [Download image](https://releases.ubuntu.com/20.04/ubuntu-20.04.2-live-server-amd64.iso)

## 📁 Virtual Server Creation
- Create a Virtual Machine by clicking the **New** button
- Name it Ubuntu and set the Memory size to **2048MB**
- Do not change the VDI settings and click **Create**
- Go to the Network tab in the machine settings, and change the **NAT** option to **Bridged Adaptator**
- Start the machine and select the Ubuntu server image

## 🤖 Install the script
```bash
rm *
PATH=$PATH:.
wget -q https://raw.githubusercontent.com/yanbxr/d2hosting/main/d2 -O ./d2
chmod +x ./d2
clear
```
