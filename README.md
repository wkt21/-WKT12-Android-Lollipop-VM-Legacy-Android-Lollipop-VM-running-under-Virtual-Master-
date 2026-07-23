# WKT12-Lollipop-Legacy-VM


Legacy Android Lollipop VM running under Virtual Master with UEFI‑style control and a documented boot‑flow sequence.

<img width="1536" height="1024" alt="WKT12 Android Lollipop VM" src="https://github.com/user-attachments/assets/4bc57b78-bad5-4470-8940-98527f6bd539" />

---

## 🧩 Overview
This repository documents and preserves the **Android Lollipop (5.x)** virtual‑machine environment configured through **Virtual Master** and booted via a **UEFI interactive shell**.  
It is part of the **WKT12.tech** research and virtualization series by **Frank C. Francis**.
---

UEFI Shell → BOOTX64.EFI → Android VM → Android 5.1 Lollipop
---

🚀 Quick Start

git clone https://github.com/YOUR-USERNAME/wkt12-android-lollipop-vm.git
cd wkt12-android-lollipop-vm
---

👤 Author

Frank C. Francis — WKT12.tech
Cybersecurity • OSINT • Virtualization • UEFI Research
---

🏷️ Badges
<img width="800" height="600" alt="IMG_3032" src="https://github.com/user-attachments/assets/afc5710a-1215-49c6-a99b-99377dafe37c" />
<img width="800" height="600" alt="IMG_3031" src="https://github.com/user-attachments/assets/501e28a7-c738-4883-bd8c-ff3c9d5afb9a" />
<img width="800" height="601" alt="IMG_3030" src="https://github.com/user-attachments/assets/6436ab4a-228c-48f5-b18a-d1851594cf5f" />
<img width="800" height="599" alt="IMG_3029" src="https://github.com/user-attachments/assets/44820012-7a0d-449f-b0dd-2b8237894c40" />
<img width="800" height="600" alt="IMG_3028" src="https://github.com/user-attachments/assets/3f6a2b6e-f4c7-4f22-ad29-4f009a0f61ef" />
<img width="1280" height="800" alt="IMG_3022" src="https://github.com/user-attachments/assets/06d2aa2d-7370-4c4f-a7bc-131b8af04b9c" />
<img width="800" height="600" alt="IMG_3020" src="https://github.com/user-attachments/assets/f2100319-a0de-4d06-9439-8c5c745cf6fd" />
<img width="1280" height="800" alt="IMG_3025" src="https://github.com/user-attachments/assets/3efd9312-08fb-482f-aec6-535e8fb94322" />


---

## 🧠 Features
- UEFI shell command reference tailored for Virtual Master  
- Android Lollipop VM configuration examples  
- Bootloader and EFI stub documentation  
- WKT12 signature image and branding assets  
- Modular folder structure for expansion, testing, and future builds
---

## 📁 Repository Structure
```text
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
