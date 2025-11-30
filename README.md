# Asus X442UR – OpenCore Configuration (i7-7500U)
![Home](https://github.com/BagusSuryaWiryawan/efi-asus-x422ur/blob/bbcd7caa4dca5323d585300e5bb3de8bee8e12e3/Screenshot)

## macOS Support
- **Monterey** ✅  
  (Installer: Litemint)

---

## System Specification

| Item | Detail |
|------|--------|
| **Model** | ASUS X442UR / X442URK |
| **CPU** | Intel Core i7-7500U (Kaby Lake, 2C/4T, 2.7–3.5 GHz) |
| **Display Resolution** | 1366 × 768 (HD) |
| **Screen Size** | 14 inch |
| **Graphics** | Intel HD Graphics 620 & NVIDIA GeForce 930MX (disabled) |
| **RAM** | 12GB DDR4 (4GB onboard + 8GB SODIMM) |
| **Storage** | HDD 1TB + SSD 128GB |
| **Wi-Fi / Bluetooth** | Qualcomm Atheros (Disabled) Change to Realtek Wifi USB  |
| **Ethernet** | Realtek RTL8168H |
| **Card Reader** | Realtek USB Based Card Reader |
| **Webcam** | ASUS UVC Camera |
| **Audio** | Realtek ALC256 (Codec Name) |
| **Touchpad** | ELAN1200 |

---

## ✅ What's Working (Monterey)
- Intel HD 620 QE/CI  
- Power Management  
- Shutdown / Sleep / Restart  
- Internal Speaker  
- Headphone Jack (audio OK)  
- Trackpad + Gesture  
- Battery Indicator  
- Camera  
- HDMI (video & audio)  
- Ethernet  
- Brightness Control  
- FN Keys  
- USB Ports (after mapping)  
- Bluetooth (via Atheros USB/BT module jika tersedia)

---

## ❌ Not Working / Known Issues
- **NVIDIA 930MX** — tidak didukung macOS  
- **Internal Microphone** — *not working*  
- **Qualcomm Atheros Wi-Fi** — tidak kompatibel macOS (Wi-Fi tidak bisa digunakan)  
- AirDrop / Handoff (karena Wi-Fi tidak kompatibel)  
- Beberapa fitur Continuity

---

## EFI Structure
EFI/
├── BOOT
└── OC
├── ACPI
├── Drivers
├── Kexts
├── Resources
└── config.plist

yaml
Copy code

---

## Notes
- Disarankan mengganti Wi-Fi ke card yang **fully macOS-supported**  
  (contoh: Broadcom BCM94352 / BCM94360)  
- NVIDIA 930MX otomatis dinonaktifkan karena tidak pernah didukung macOS.  
- Internal mic pada model ini sering gagal berfungsi di macOS karena codec ALC255 + layout-ID tertentu tidak membaca input device.  

---

## License
Bebas digunakan untuk pembelajaran & penggunaan pribadi.
