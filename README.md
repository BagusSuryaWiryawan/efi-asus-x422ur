# EFI OpenCore – ASUS X442UR (i7-7500U)

EFI ini dibuat untuk laptop **ASUS X442UR** dengan prosesor **Intel Core i7-7500U (Kaby Lake)**.  
Konfigurasi disusun untuk mencapai kestabilan terbaik pada macOS menggunakan OpenCore.

---

## ✨ Spesifikasi Perangkat

| Komponen | Detail |
|---------|--------|
| **Model Laptop** | ASUS X442UR / X442URK |
| **Prosesor** | Intel Core i7-7500U (2 Cores / 4 Threads, 2.7–3.5 GHz, Kaby Lake) |
| **iGPU** | Intel HD Graphics 620 |
| **dGPU** | NVIDIA GeForce 930MX *(tidak digunakan, non-aktif di macOS)* |
| **RAM** | 8GB / 12GB / 16GB DDR4 (tergantung konfigurasi pengguna) |
| **Penyimpanan** | HDD / SSD SATA / SSD NVMe (opsional) |
| **Ukuran Layar** | 14 inci |
| **Resolusi Layar** | 1366×768 (HD) — beberapa varian menggunakan panel 1080p |
| **WiFi & Bluetooth** | Realtek / Atheros / Intel *(compatibility berbeda)* |
| **Audio Codec** | Realtek ALC255 |
| **Port** | USB 2.0, USB 3.0, USB-C, HDMI, Audio Jack, SD Card |

---

## ✔️ Fitur yang Bekerja

- Intel HD 620 Graphics (QE/CI enabled)
- Trackpad & Keyboard
- Audio Output/Input (ALC255)
- Wi-Fi & Bluetooth *(tergantung kartu yang dipakai)*
- USB Mapping Stabil
- Sleep/Wake
- Battery Status
- Brightness Control
- HDMI Output

---

## ⚠️ Fitur yang Tidak Berfungsi

- NVIDIA 930MX (tidak kompatibel dengan macOS)
- Pembaca kartu SD tertentu (tergantung chipset)
- WiFi bawaan Realtek/Intel mungkin butuh penggantian modul

---

## 📁 Isi EFI

