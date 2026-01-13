# My Homelab Setup

## About
This is my homelab setup. It is ever-changing, but I plan to keep up with my changes and updates here.
I have this lab for a few reasons:
1. Learn Linux at a deep level.
2. Set up and configure Virtual Machines on a Virtual Network.
3. Start practicing with cybersecurity-oriented VMs (etc. Kali and Metasploitable)
4. General system administration and automation.
5. Programming (Bash and Python for now).
6. A place for the random project ideas I come up with.

## Hardware
### Main PC:
I converted my old gaming PC into a daily driver and the main component of this home lab.
- Operating System: Debian 13 Stable "Trixie"
- Desktop Environment: KDE Plasma
- CPU: AMD Ryzen 7 3700X 16-Core
- GBU: Nvidia GeForce RTX 2070 Super
- Disk 1: NVMe M.2 1TB SSD - Host OS and Daily Files
- Disk 2: NVMe M.2 2TB SSD - Virtual Machine and Docker Containers

### Home Lab Architecture
```
-nvme1n1p1
|
| Networking
| |
| | pfsense VM
|
| QEMU/KVM Virtual Machines
| |
| | Attack Systems
| | |
| | | Kali Linux
| | |
| | | Parrot Security
| | 
| | Victim Systems
| | |
| | | Metasploitable
| | |
| | | Windows 11
|
| Docker Containers
| |
| | DVWA - Damn Vulnerable Web App
```
### Hardware Lab
I am currently experimenting/learning about hardware programming and hacking.
**3x ESP32 WROOM SoC devkit boards.**
I am using these to learn about programming devices to interface and manipulate RF signals, mainly WiFi and Bluetooth.

**5x AiTrip Digispark Attiny Micro USB dev boards**
I am using these to learn how to write usb payloads that run automatically when a usb device is plugged into a computer. Basically a home-build rubber ducky.


### Auxillary Hardare

**Wireless/Physical Pentesting Tools**
- Flipper Zero with WiFi dev board - my first device that got me addicted to wireless security!
- JCMK Marauder Dual Touch v.3
- Pineapple Pager with GPS

**Radio Lab**
- Raspberry Pi 5 16GB, 16BG RAM, 128GB SSD
- Raspberry Pi 1080p Monitor
- Operating System: Raspberry Pi OS Lite (no GUI)
This is currently running as a Software Defined Radio basestation.
I currently have both a telescopic antenna for ease of use, as well as a wideband discone antenna set up in my backyard. I have a 65ft. coax cable running from that to the raspberry pi/rtl-sdr.

- Heltec Automation ESP32 V3 Mesh Radio Node
