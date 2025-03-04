# Hackintosh-Asus-PRIME-Z690-P

**Opencore Bootloader 1.0.1. Tested on Sequoia 15.0**



## Hardware
* **Motherboard**: [ASUS PRIME Z690-P WIFI D4](https://www.asus.com/motherboards-components/motherboards/prime/prime-z690-p-wifi-d4/) (BIOS Version: 3403)
* **CPU**:  Intel® Core™ i5-13600KF
* **GPU**: [AMD Radeon™ RX 5700 XT Challenger D 8G OC](https://www.asrock.com/Graphics-Card/AMD/Radeon%20RX%205700%20XT%20Challenger%20D%208G%20OC/)
* **RAM**: Asgard 32GBx4 DDR4 @3600 
* **HDD**: Seagate FireCuda 510 2T
* **LAN**: RTL8125B / Intel X550-T2
* **Wi-Fi & Bluetooth**: BCM943602CS



## Working
* CPU Turbo Boost & SpeedStep
* Radeon™ RX 5700 XT HW acceleration
* Front panel / Back panel Audio Jacks
* USB Ports (Aura USB port disabled due to macOS ports limit)
* all LAN / Wireless / Bluetooth
* Sleep & Wakeup
* Airdrop / Airplay / Handoff / Universal Control



## BIOS Settings
### Advanced \ Platform Misc Configuration
* PCI Express Native Power Management: Enabled
* Native ASPM: Enabled
* PEG - ASPM: L0sL1
### Advanced \ System Agent Configuration
* VT-d: Enabled
### Advanced \ Thunderbolt Configuration
* PCIE Tunneling over USB4: Disabled
* Discrete Thunderbolt Support: Disabled
### Advanced \ Trusted Computing
* Security Device Support: Disable
### Advanced \ PCI Subsystem Settings
* Above 4G Decoding: Enabled
* Re-Size BAR Support: Enabled
### Advanced \ USB Configuration
* XHCI Hand-off: Enabled

### BOOT \ CSM
* Launch CSM: Disabled
### BOOT \ Secure Boot
* OS Type: Other OS
* Secure Boot Mode: Custom



## Post Install
* Make the Boardcom Wi-Fi/BT card work on Sonoma with [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher).
* Prevent high CPU usage caused by Bluetooth Deamon after wakeup with the [SleepWatcher scripts](https://gist.github.com/webleon/8de3632a3d21fe1a670a9563703c45f2).




  
## Screenshots
![](https://github.com/webleon/Hackintosh-Asus-PRIME-Z690-P/blob/main/images/systeminfo.png) 
![](https://github.com/webleon/Hackintosh-Asus-PRIME-Z690-P/blob/main/images/geekbench6.png)
![](https://github.com/webleon/Hackintosh-Asus-PRIME-Z690-P/blob/main/images/cinebenchR23.png)
