# Cybersecurity Lab Setup (VirtualBox & Kali Linux) - Week 1

## Overview
This repository documents the setup of a isolated Cybersecurity & Ethical Hacking lab environment using VirtualBox, custom NATNetwork configurations, and Kali Linux as the primary attacker machine[cite: 1].

## Lab Architecture & Technical Details
- **Hypervisor:** Oracle VM VirtualBox[cite: 1]
- **Attacker OS:** Kali Linux (`10.0.0.2/24`)[cite: 1]
- **Network Subnet:** `10.0.0.0/24` (NATNetwork with DHCP Enabled)[cite: 1, 4]
- **Default Gateway:** `10.0.0.1`[cite: 6]
- **DNS Server:** `8.8.8.8`[cite: 6]

## Key Configuration Steps
1. **VirtualBox NATNetwork Setup:** Configured custom subnet `10.0.0.0/24`[cite: 1, 3].
2. **Kali Linux VM Setup:** Assigned static IP (`10.0.0.2/24`), enabled shared clipboard, bidirectional drag & drop, and host `/downloads` folder sharing[cite: 1].
3. **Connectivity Verification:** Tested Internet reachability and NetworkManager settings[cite: 1, 6, 7].
4. **VM Snapshot:** Took initial clean state snapshot for backup and safe rollback[cite: 3].

## Screenshots
<img width="1366" height="732" alt="image" src="https://github.com/user-attachments/assets/d21b8adc-1105-4544-b362-5d209e7dc83a" />
<img width="1366" height="702" alt="VirtualBox_kali-linux-2026 2-virtualbox-amd64_27_10_2026_22_22_32" src="https://github.com/user-attachments/assets/e98852c6-b36f-4a22-8c6d-769dff0cac52" />
