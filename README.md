# OpenCore-Hackintosh-HP-255-G7
OpenCore EFI for HP 255 G7 (AMD Ryzen 5 3500U)

Credits:
[OpCore-OneClick](https://github.com/redpersongpt/OpCore-OneClick/releases/tag/v6.0.0)
[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)
[Dortania install guide](https://dortania.github.io/OpenCore-Install-Guide/)
[GenSMBIOS](https://github.com/corpnewt/gensmbios)

> [!WARNING]
> **Generate you oun SMBIOS for MacBookPro16,3**
# Hardware Specifications
| Component | Status | Notes |
|---|---|---|
| CPU |  Working | Ryzen 5 3500U |
| GPU |  Working | Radeon Vega 8 |
| Audio |  Working | ALC236 |
| Wi-Fi |  Working | RTL8821CE |
| SATA/NVMe drive | SATA working/NVMe untested |  |
| Ethernet |  Working | RTL8168 |
| Bluetooth |  Not Working | Not supported by macOS |
| OpenCore | Version 1.0.8 |  |
| USB/HDMI | All USB/HDMI working |  |
| DVD-drive | Not tested | Maybe working |
| Keyboard/Trackpad | Fully functional |  |
| Brightness | Works | Keys (F2-F3) |
| Sleep | Not working |  |

# BIOS Settings
CSM (OFF)
The BIOS is stripped-down, so everything else is already configured in "config.plist"

# Kexts
* `Lilu.kext`
* `VirtualSMC.kext` (+ `SMCBatteryManager`, `SMCAMDProcessor`, `SMCRadeonSensors`, `SMCLightSensor` `SMCBatteryManager`)
* `NootedRed.kext`
* `AppleALC.kext`
* `VoodooPS2Controller.kext`
* `AirportRTW.kext`
* `UTBDefault.kext` (+ `USBToolBox` )
* `RestrictEvents.kext`
* `RealtekRTL8811.kext`
* `GenericUSBXHCI.kext`
* `ForgedInvariant.kext`
* `ECEnabler.kext`
* `BrigtnessKeys.kext`
* `AMDSata.kext`
* `AMDRyzenCPUPowerManagement.kext`
