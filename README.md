# Gigabyte B450M Aorus + Ryzen7 3700X + RX 580 Sapphire Nitro + Fenvi BRCM20702

![about-12 3 1](https://raw.githubusercontent.com/nilsen-daniel/EFI-Desktop-B450-AORUSM-AMD-Ryzen7-3700X-RX580/refs/heads/main/Images/Ryzentosh.png)

**Latest working macOS**: 13.7.6 (22H625)
<br>
**Current OpenCore**: 1.0.5

## Attention 
Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
*1. MLB (Board Serial)
<br>
2. ROM (Mac Address)
<br>
3. SystemSerialNumber (Serial)
<br>
4. SystemUUID (SmUUID)*

Please use [*genSMBIOS*](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [*ProperTree*](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.

## Complete hardware specs
- AMD Ryzen7 3700X
- Gigabyte B450M Aorus BIOS F6a
- RX 580 - Nitro Sapphire
- 4x 8Gb DDR4 3000Mhz JUHOR with XMP Enabled
- Wifi/BT by Fenvi BRCM20702

![hardware](https://raw.githubusercontent.com/nilsen-daniel/EFI-Desktop-B450-AORUSM-AMD-Ryzen7-3700X-RX580/refs/heads/main/Images/Hardware.png)

## USB-MAP
![mapped-usb](https://raw.githubusercontent.com/nilsen-daniel/EFI-Desktop-B450-AORUSM-AMD-Ryzen7-3700X-RX580/refs/heads/main/Images/USB-Ryzentosh.png)

## What works
- macOS Ventura
- Audio
- HDMI
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- I Dont Know Yet

## Kexts used:
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Innie.kext
- Lilu.kext
- RealtekRTL8111.kext
- SMCSuperIO.kext
- SMCAMDProcessor.kext
- SMCProcessor.kext
- RestrictEvents.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [luchina-gabriel BASE EFI AMD - Ryzen and Threadripper](https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER-PUBLIC)

## Best Place To Learn And Best Community On Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
