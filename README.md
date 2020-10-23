# Hackintosh Dell XPS 13 7390 2-in-1 [WIP]
## OpenCore
**What works?**
- Installation
- Keyboard/Trackpad
- Battery Information
- Intel Bluetooth
- Thunderbolt (no Hot-Plug)
- HiDPI Screen

**What doesn't work (yet)**
- Intel AX200 WiFi (ITLWM works)
- Touch screen (VooDooI2C doesn't recognize my controller)
- Intel Iris Plus G7 (Starting but GIOSCREENLOCKSTATE 3 initiates before I get into MacOS) & Brightness control

CFG Lock variable is found at 0x43 and can be disabled by putting 0x0 as value.
