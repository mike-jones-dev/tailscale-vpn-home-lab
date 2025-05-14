# 🔐 Tailscale VPN: Secure Remote Access to My Home Network

## 📌 Project Overview

This project documents how I set up **Tailscale**, a mesh VPN, to securely access my home network and personal PC remotely — including from my Android phone while on the job.

It was designed to give me secure, encrypted access to:
- My home desktop from any location
- Shared folders and files over LAN
- Windows Server testing environments
- Local tools and services (OBS, dev environments, etc.)

---

## 🛠️ Tools & Tech Used

- 🧠 Tailscale (Free Tier)
- 💻 Windows 11 Pro Desktop
- 💻 Windows 11 Home Laptop
- 💻 Windows 11 Home Microsoft Surface Go 2
- 📱 Android Phone (Mobile client)
- 🧰 Admin rights and network access for install
- 🔧 Remote Desktop + Command Line tools

---

## ⚙️ Setup Process

1. **Created a Tailscale Account**  
   Used my GitHub to register.

2. **Installed Tailscale Client**  
   Installed on:
   - Windows 11 Pro desktop (primary machine)
   - Windows 11 Home laptop
   - Windows 11 Home Surface Go 2
   - Android phone

3. **Logged In & Linked Devices**  
   Devices appeared in the Tailscale admin panel.

4. **Tested Remote Access**  
   - Connected from phone using Tailscale IP
   - Verified file system access and latency
   - Tested RDP connection

5. **Security Check**  
   - Enabled multi-factor authentication
   - Verified Tailscale firewall settings

---

## 🧠 What I Learned

- 🔄 How peer-to-peer mesh VPNs differ from traditional VPNs
- 🔑 Importance of MFA and access control in network security
- 🌐 How to securely expose local network services without port forwarding
- 📶 The value of low-latency VPN access for future IT use cases

---

## 📸 Screenshots (Optional)

> You can upload and embed:
> - A screenshot of your devices in the Tailscale dashboard  
> - A screenshot of a successful remote session  
> - Obfuscate personal IPs or usernames

---

## ✅ Next Steps

- Setup persistent services (file share or server) behind VPN
- Test access from additional devices (e.g., work laptop)
- Configure ACLs in Tailscale admin panel
- Document network diagram in `network-diagrams/` folder (coming soon)

---

📁 Repo created and maintained by [Mike Jones](https://github.com/mike-jones-dev)



