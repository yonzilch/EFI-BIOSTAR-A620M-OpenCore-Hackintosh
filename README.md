# EFI-BIOSTAR-A620M-OpenCore-Hackintosh

### OpenCore

[OpenCore 0.9.9](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Ventura 13.x 

### Hardware

- Motherboard: BIOSTAR A620MP-E PRO
- Bios Version: A62AQ704.BSS
- CPU: AMD R5 7500F
- GPU: Sapphire AMD RADEON RX 6750gre 12G
- Audio: Realtek ALC897
- Ethernet: Realtek RTL8125B(G) PCle 2.5GbE Family Controller
- Wireless: Intel Wi-Fi AX210

#### PS:
 - All USB ports are customized well and could use USB3.0 at Boot.
 - Wireless Connection & Bluetouch works.

### Bios Setup

| Name | Option |
| ----- | --- |
| Security → System Mode → Secure Boot | Disabled |

(PS: Just use all default settings is enough.)

### Notes

 - Use suitable [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your SMBIOS

 - If you use other CPU(not 6Cores), You should change VoodooTSCSync in config.plist otherwise the performance of CPU maybe not as well as possible.

