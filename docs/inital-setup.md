# Initial Setup
---

## Arch Linux Setup
While I am very familiar with several distributions (Fedora, Pop OS, Linux Mint, Ubuntu), I chose Arch because I wanted an linux distribution that held my hand as little as possible and cam with as little preinstalled software as possible.
I initially tried Ubuntu for widespread software compatibility, but very quickly got frustrated with how often I'd go to set something up, like SSH, and it would already be done.

I did use archinstall instead of the real manual process.

1. Disk Partitioning: I chose to go use the 1TB drive (nvme0n1) for:
- nvme0n1p1 - 1GB - /boot
- nvme0n1p2 - 953GB - /
and the 2TB drive (nvme1n1) for /home.

2. BTRFS
I have never used BTRFS, but I do want to learn how to use it and its snapshots.

3. Bootloader
I chose GRUB because I am familiar with it and it's customization. That's really the main reason.

4. The rest of the setup I just followed the menu.

Below is a screenshot of the setup:
![computer configuration screenshot](../screenshots/system-overview.png)
