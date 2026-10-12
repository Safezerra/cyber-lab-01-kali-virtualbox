Cyber Lab #01: Kali Linux on VirtualBox :
    A beginner-friendly cybersecurity lab setup using Kali Linux and Oracle VirtualBox.

  Objective :

The goal of this project was to build a basic cybersecurity practice environment on a Windows host machine using a Kali Linux virtual machine.

This lab will be used for future learning and authorized cybersecurity practice.

 Tools Used
     - Windows
     - Oracle VirtualBox
     - Kali Linux
     - 7-Zip

 Lab Architecture :


Windows Host
     |
     v
 VirtualBox
     |
     v
 Kali Linux VM
⚙️ VM Configuration
Example configuration used:
- RAM: 4 GB
- CPU: 2 processors
- Network Adapter 1: NAT
Resource allocation depends on the host machine. Do not allocate all available RAM/CPU to the VM.

🌐 Network Configuration
For the initial setup, NAT was used to provide basic internet connectivity to Kali.
The networking configuration will be expanded in the next Cyber Lab project.
Planned networking modes:
- NAT
- Bridged Adapter
- Host-only Adapter
- Internal Network
🔎 Basic Verification
Inside Kali:
ip addr

Used to inspect network interfaces and IP addresses.
ip route

Used to inspect routing information.
ping -c 4 google.com

Used to perform a basic connectivity test.
📸 Screenshots
Screenshots from the lab setup are stored in the screenshots/ directory.
🔐 Snapshot
A clean VirtualBox snapshot was created:
Clean Kali Setup
This provides a known-good state to return to after future experiments.
🚧 What's Next?
Cyber Lab #02: VirtualBox Networking
The next stage will explore:
- NAT
- Bridged Adapter
- Host-only Adapter
- Internal Network
- Host ↔ Kali communication
- Kali ↔ Target VM communication
- Isolated cybersecurity lab design
⚠️ Disclaimer
This repository is for educational and authorized cybersecurity practice.
Only test systems, applications, and networks that you own or have explicit permission to test.
🎥 Video
YouTube: 
https://youtu.be/uA6-PyDSHqI?si=BrY_dH4apWo6V_Es








