# Dell-Vostro-5590-Hackintosh-EFI
EFI folder for OpenCore 0.7.5 and macOS Big Sur compatible with the Dell Vostro 5590 and 5490. Supposedly works with Inspiron 5490/5498/5590/5598.

### Specs:
Type | Details
| -------------- |:----------------------------:|
CPU | Intel Core i7-10510U
iGPU | Intel UHD 620
dGPU | NVIDIA GeForce MX250
Display | 1920x1080
RAM | 8GB
Audio | Realtek ALC3204/236
WLAN | Intel 9462AC
LAN | Realtek RTL8169
SSD | 480GB Kingston UV500 - macOS boot
NVMe | 512GB Samsung PM991 - Windows
KB | Built-in Standard PS2 Keyboard
TP | Built-in I2C HID Trackpad
SMBIOS | MacBookPro16,4
Bootloader | OpenCore 0.7.7

### What works and What doesn't or WIP:
- [x] Intel UHD 620 iGPU eDP Output (with Backlight)
- [x] Intel UHD 620 iGPU HDMI Output
- [x] ALC3204/236 Internal Speakers
- [x] ALC3204/236 Native Jack Output
- [x] ALC3204/236 HDMI Audio Output
- [x] All USB Ports Type A (2xUSB 3.0 and 1xUSB 2.0)
- [x] SpeedStep / Sleep / Wake
- [x] I2C Touchpad
- [x] Intel Bluetooth Module
- [x] Realtek RTL8169 LAN
- [x] USB Cardreader
- [x] ACPI Battery
- [x] NVRAM
- [x] Wi-Fi (on Big Sur)

- [ ] DisplayPort over Type-C (did not check)
- [ ] MX250 dGPU (Not supported)
- [ ] Internal / External Mic and Camera

## Important Notes:
- Generate your OWN SMBIOS
- Do not COPY & PASTE this and use on your installer or Mac disk's EFI Partition. This is to give you idea on what will work and a jump start to hackintosh this laptop.
- Fixes for current problems are appreciated.
