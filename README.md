# OpenCore Intel i9-10900k ASUS-PRIME-Z590M

# Setup

* Intel I9-10900K
* ASUS PRIME Z590M
* 64GB RAM (32GBx2 Kingston DD3 3200)
* AMD Radeon RX 6900 XT (dGPU)
* UHD Graphics 630 (iGPU)

# EFI 

SMBIOS: iMac20,2
OpenCore: 0.7.2


# Working
- [x] **Tested with macOS macOS Big Sur 11.5.2**
- [ ] **Dont have WiFi**
- [x] **USB**, except Type-C port.
- [x] **1Gbit Ethernet (Intel onboard)**
- [x] **Sleep/Wake**
- [x] **Shutdown**
- [x] **Restart**

## Language

Default Keyboard Layout/Language setting was changed to EN-US in v1.5.

If you want to change this, just edit this setting in the config.plist:

```
- NVRAM
	- Add
		- 7C436110-AB2A-4BBB-A880-FE41995C9F82
			- prev-lang:kbd | String | en-US:0
```


# Credits
Thanks for your support
- [Dortania](https://github.com/dortania) for this great OpenCore Desktop Guide
- [SchmockLord](https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D) for Original repo with the config 
- [Acidanthera](https://github.com/acidanthera)
- [RehabMan](https://github.com/RehabMan)
- [OpenCore project](https://github.com/OpenCorePkg)
