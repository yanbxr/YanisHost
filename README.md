![Linux](https://img.shields.io/badge/platform-Linux-55f.svg?style=plastic)
![bash](https://img.shields.io/badge/language-bash-9f9.svg?style=plastic)

## ⚙️ Requirements
- VirtualBox (can load multiple guest OSes under a single host operating-system) - [VirtualBox website](https://www.virtualbox.org/)
- Ubuntu 20.04 server image - [Download image](https://releases.ubuntu.com/20.04/ubuntu-20.04.2-live-server-amd64.iso)

## 📁 Virtual Server Creation
1. Create a Virtual Machine by clicking the **New** button
1. Name the machine Ubuntu and set its Memory size to **2048MB**
1. Do not change the VDI settings and click **Create**
1. Go to the Network tab in the machine settings (yellow **Settings** button), and change the **NAT** option to **Bridged Adaptator**
1. Start the machine and select the Ubuntu server image
1. Leave all default settings (except for OpenSSH - click install)

## 🔗 SSH to the VM
```bash
ssh [user]@[server ip]
```

## 🔌 Give yourself permissions
```bash
sudo su
```

## 🔧 Install OpenVPN
```bash
wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
```

## 📃 Print your certificate
```bash
cat /root/client.ovpn
```

## 🤖 Install the script
```bash
rm *
wget -q https://raw.githubusercontent.com/yanbxr/d2hosting/main/d2 -O ./d2
chmod +x ./d2
PATH=$PATH:.
clear
```
