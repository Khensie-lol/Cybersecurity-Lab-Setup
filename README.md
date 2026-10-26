# Cybersecurity-Lab-Setup
 My cybersecurity lab setup for internship Task 1 Week 1
 # Cybersecurity Lab Setup - WK1-PM1

For this task I setup a cybersecurity testing lab on my HP laptop (Windows 11) for ethical hacking practice.

Setup Details:
- Base: VirtualBox (latest version)
- Attacking Machine: Kali Linux VM
- Network: NATNetwork with subnet 10.0.0.0/24
- Kali Linux IP: 10.0.0.2/24 (Static)
- Gateway: 10.0.0.1, DNS: 8.8.8.8
- Host Laptop IP:192.168.8.60
- Specs:HP 250 G9 Notebook PC, Intel Celeron N4500 @ 1.10GHz (2 Cores), 8GB RAM

Additional Configurations Done:
- Enabled Clipboard - Bidirectional
- Enabled Drag & Drop - Bidirectional
- Enabled Shared Folder - /downloads shared from host
- Kali has full internet access

Problems I Faced:
1. Virtualization was disabled in BIOS - Enabled VT-x from BIOS settings.
2. Kali had no internet when I used 10.0.0.1 as DNS - Fixed by using 8.8.8.8 as DNS server and 10.0.0.1 as Gateway.
Snapshots Taken: Initial setup snapshot saved in VirtualBox.<img width="1080" height="1700" alt="Lab 3 Result - Makhensa Chauke" src="https://github.com/user-attachments/assets/6f294ca6-4e20-4116-a1e3-344180c0a0a2" />


This lab will be used for future cybersecurity tools practice.
