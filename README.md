<div align="center">
  
[![](https://img.shields.io/badge/Repositories-pierpaolodimarzo-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/pierpaolodimarzo?tab=repositories)
[![](https://img.shields.io/badge/Gitter%20Ice%20Lake-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/ICE-LAKE-HACKINTOSH-DEVELOPMENT/community)
[![](https://img.shields.io/badge/Gitter%20HL%20Community-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/Hackintosh-Life-IT/community)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)
[![](https://img.shields.io/badge/PayPal-HackintoshLifeIT-informational?style=flat&logo=paypal&logoColor=white&color=00B2EE)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RWBVVWL8H9JC2&source=url)

</div>

# Intel NUC10i5FNH Hackintosh :sunglasses:

EFI for Intel NUC10i5FNH with OpenCore 0.6.7 bootloader

![descrizione](./Infos/pc.png)

### INFO PC:

| Component        | Brank                                  |
| ---------------- | ---------------------------------------|
| CPU              | Intel® Core™ i5-10210U                 |
| iGPU             | Intel® UHD Graphics 630                |
| Audio            | Realtek ALC256                         |
| RAM              | 16 GB DDR4 2600 Mhz                    |
| WiFi + Bluetooth | Intel® Wireless-AC 9560 + Bluetooth 5.0|
| LAN              | Intel I219-V.                          |
| Thunderbolt 3    | JHL7540 Thunderbolt 3                  |
| NVMe             | Kingstone A2000 M.2 2280 NVME (MacOS)  |
| SMBios           | Macmini8,1                             |
| BootLoader       | OpenCore 0.6.7                         |
| macOS            | Big Sur 11.2.3                         |


![infobigsur](./Infos/infomac.png)

See the [IOREG](https://github.com/pierpaolodimarzo/Intel-NUC10i5FNH/blob/main/Mac%20mini.ioreg)

### What works and What doesn't or WIP:

- [x] CFG Unlock
- [x] Intel Graphics UHD iGPU HDMI Output
- [x] ALC256 Internal Speakers
- [x] ALC256 HDMI/Thunderbolt Audio Output
- [x] All USB Ports (3.0/3.1)
- [x] Sleep / Wake / SpeedStep 
- [x] AC 9560 Wi-Fi and Bluetooth
- [x] Controller NVME PciE Gen3x4 
- [x] NVRAM
- [x] microSDXC Card Reader
- [x] Thunderbolt 3 GC Titan Ridge V2
- [x] Thunderbolt Hotplug for GC Titan Ridge
- [x] USB C Hotplug For GC Titan Ridge

## Peripherals & Benchmarks

![infohack](./Infos/peripherals.png)
![CPU](./Infos/cputest.png)
![GPU-metal](./Infos/metal.png)
![GPU-opencl](./Infos/opencl.png)

This is the speed test of [Kingstone A2000 - SSD NVMe PCIe](https://www.kingston.com/italy/it/ssd/a2000-nvme-pcie-ssd)

![InternalDisk](./Infos/InternalNVME.png)

This is the speed test of RAM [Crucial 8GB x2 DDR4 2400](https://it.crucial.com/memory/ddr4/ct2k8g4sfs824a)

![InternalRAM](./Infos/testRAM.png)

## OS Version Tested

macOS Big Sur 11.1

## BIOS config

BIOS version FNCML357.0050 (latest)
•	Advanced
	◦	Storage
		▪	SATA Mode Selection -> AHCI
	◦	Video
		▪	IGD Minimum Memory -> 64MB
		▪	IGD Aperture Size -> 256MB
		▪	IGD Primary Video Port -> Auto
•	Boot
	◦	Secure Boot
		▪	Secure Boot -> Disabled
	◦	Boot Priority
		▪	UEFI Boot -> Checked
		▪	Legacy Boot -> Unchecked
		▪	Fast Boot -> Unchecked
•	Power
	◦	Secondary Power Settings
		▪	Deep S4/S5 -> Off
		▪	Wake on Lan from S4/S5 -> Stay Off
		▪	Wake System from S5 -> Off
		▪	Wake From Thunderbolt Device -> Off

