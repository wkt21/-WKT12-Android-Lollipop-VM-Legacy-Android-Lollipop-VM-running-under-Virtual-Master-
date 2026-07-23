# WKT12-Lollipop-Legacy-VM

Legacy Android Lollipop VM running under Virtual Master with UEFI-style control and a documented boot-flow sequence.

<img width="1536" height="1024" alt="WKT12 Android Lollipop VM" src="https://github.com/user-attachments/assets/4bc57b78-bad5-4470-8940-98527f6bd539" />
---

## Overview
This repository documents and preserves the Android Lollipop (5.x) virtual-machine environment configured through Virtual Master and booted via a UEFI interactive shell.  
It is part of the WKT12.tech research and virtualization series by Frank C. Francis.
---

## Boot Flow
---

Author

Frank C. Francis — WKT12.tech
Cybersecurity • OSINT • Virtualization • UEFI Research
---

Visual Badges and Project Media
---

Features

• UEFI shell command reference tailored for Virtual Master
• Android Lollipop VM configuration examples
• Bootloader and EFI stub documentation
• WKT12 signature image and branding assets
• Modular folder structure for expansion, testing, and future builds
---

# Repository Structure

wkt12-android-lollipop-vm
/
├─ README.md
├─ LICENSE
   ├─ docs/
   │  ├─ boot-flow.md
   │  └─ virtual-master-setup.md
   ├─ images/
  │    └─ wkt12-signature.png
  ├─ uefi/
  │  ├─ commands-cheatsheet.md
  │  └─ startup.nsh
  └─ vm/
   ├─ android-lollipop-notes.md
   └─ config-example.txt
---

## Quick Start
```bash
git clone https://github.com/YOUR-USERNAME/wkt12-android-lollipop-vm.git
cd wkt12-android-lollipop-vm

