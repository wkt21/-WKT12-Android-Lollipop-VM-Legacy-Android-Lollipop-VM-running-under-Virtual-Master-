# WKT12 Android Lollipop VM

Legacy Android Lollipop VM running under Virtual Master with UEFI-style control and boot flow visualization.

<img width="1536" height="1024" alt="IMG_3019" src="https://github.com/user-attachments/assets/4bc57b78-bad5-4470-8940-98527f6bd539" />

---

## 🧩 Overview
This repository documents and preserves the **Android Lollipop (5.x)** virtual machine environment configured through **Virtual Master** and booted via a **UEFI interactive shell**.  
It’s part of the **WKT12.tech** research and virtualization series by **Frank C. Francis**.

---

## 🧠 Features
- UEFI shell command reference for Virtual Master
- Android Lollipop VM configuration examples
- Bootloader and EFI stub documentation
- WKT12 signature image and branding assets
- Modular folder structure for expansion and testing

---

## 📁 Repository Structure

wkt12-android-lollipop-vm/
├─ README.md
├─ LICENSE
├─ docs/
│  ├─ boot-flow.md
│  └─ virtual-master-setup.md
├─ images/
│  └─ wkt12-signature.png
├─ uefi/
│  ├─ commands-cheatsheet.md
│  └─ startup.nsh
└─ vm/
├─ android-lollipop-notes.md
└─ config-example.txt


---

## ⚙️ Boot Flow Diagram

UEFI Shell → BOOTX64.EFI → Android VM → Android 5.1 Lollipop


---

## 🧾 UEFI Shell Commands
```text
map -r
ls fs0:\
cd fs0:\EFI\ANDROID\
BOOTX64.EFI
memmap
pci
drivers
handles

Quick Start

git clone https://github.com/YOUR-USERNAME/wkt12-android-lollipop-vm.git
cd wkt12-android-lollipop-vm

Author
Frank C. Francis — WKT12.tech
Cybersecurity • OSINT • Virtualization • UEFI Research

Badges
https://img.shields.io/badge/UEFI-Boot-blue
https://img.shields.io/badge/Virtual-Master-green
https://img.shields.io/badge/Android-5.1_Lollipop-orange
