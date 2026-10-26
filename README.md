 # Cybersecurity Lab Setup

## Student: Khensie - Lab Setup Working

This lab shows a working Cybersecurity setup using VirtualBox and Kali Linux.

### 1. Virtual Machine Configuration
- **Platform:** Oracle VirtualBox 7.x
- **VM:** kali-linux-2026.2-virtualbox-amd64
- **State:** Running - Clean Install - Working Internet
- **Shared Folder:** sf_downloads (Working)

### 2. Network Configuration - NATNetwork
- **Network Name:** NATNetwork
- **Subnet:** 10.0.0.0/24
- **Kali IP:** 10.0.0.2/24 (DHCP)
- **Interface:** eth0 UP
- **MAC:** 08:00:27:5a:87:bc

### Screenshot 1 - Kali IP Proof (10.0.0.2/24)
This proves Kali is connected to NATNetwork with correct IP.
![Kali IP Proof](1-kali-ip.png)


### Screenshot 2 - Internet & Network Proof
Ping to 8.8.8.8 and NATNetwork Manager showing 10.0.0.0/24.
![Kali Ping Proof](2-kali-ping.png)

### 3. Verification Commands Used
```bash
ip a
# Shows: inet 10.0.0.2/24 brd 10.0.0.255 scope global dynamic noprefixroute eth0

ping -c 4 8.8.8.8
# Shows: 4 packets transmitted, 4 received, 0% packet loss

ping -c 4 google.com
# Shows internet DNS working
