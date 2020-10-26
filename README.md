# Hackintosh Dell XPS 13 7390 2-in-1 [WIP]
## OpenCore
**What works?**
- Installation
- Keyboard/Trackpad
- Battery Information
- Intel Bluetooth
- Intel WiFi with native Airport WiFi picker
- Thunderbolt (no Hot-Plug)
- HiDPI Screen

**What doesn't work (yet)**
- Touch screen
- Audio
- Fingerprint scanner
- Intel Iris Plus G7 (Boot argument -igfxvesa disables IGPU.)

CFG Lock variable is found at 0x43 and can be disabled by putting 0x0 as value.
