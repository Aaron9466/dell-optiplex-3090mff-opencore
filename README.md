# dell-optiplex-3090mff-opencore

OpenCore for macOS sonoma (14.4.1) on Dell OptiPlex 3090 MFF

## Tutorials

- [折腾 7080MFF 黑苹果 OpenCore](https://www.jianshu.com/p/d7cfaae60509)
- [3dudu/dell-optiplex-7080-hackintosh-opencore](https://github.com/3dudu/dell-optiplex-7080-hackintosh-opencore)

## Hardware

-   CPU: Intel Comet Lake i5 10500T
-   Chipset: Intel Q470
-   Memory: 8G DDR4 2666 \* 2
-   iGPU: UHD 630
-   SSD: KINGSTON SNVS500G
-   Sound: ALC256
-   Ethernet: Intel I219-LM
-   Wireless / BT: Intel AX201

## Status

### Working

-   HWP
-   Sleep
-   iGPU with HiDPI
-   Ethernet
-   WiFi
-   Bluetooth
-   Sound
## BIOS

|Settings|Value|
|----|---|
|System Configuration → Integrated NIC | Enabled |
|System Configuration → SATA Operation | AHCI |
|Security → PTT Security/PTT On | Disabled |
|Secure Boot → Secure Boot Enable | Disabled |
|Secure Boot → Secure Boot Mode | Audit Mode |
|Intel SGE → SGX | Disabled |
|Performance → Intel SpeedStep | Enabled |
|Performance → C-States Control | Enabled |
|Performance → Turboost | Enabled |
|Performance → HyperThread Control | Enabled |
|Power Management → Intel Speed Shift Technology | Enabled |
|Power Management → Deep Sleep Control | Disabled |
|Power Management → USB Wake Support | Disabled |
|Power Management → Wake on LAN/WLAN | Lan only |
|Power Management → Block Sleep | Disabled |
|POST Behavior → Fastboot | Minimal |
|Virtualization Support → Virtualization | Enabled |
|Virtualization Support → VT For Direct I/O | Disabled |
|Advanced configurations → ASPM | Auto |

## Gotchas

- Mostly followed [折腾 7080MFF 黑苹果 OpenCore](https://www.jianshu.com/p/d7cfaae60509) to prepare the EFI for both installation and daily running environment.
- Modify BIOS to disable CFG Lock and enable DVMT.

## Updates
- 2024/03/30 upgrade oc to 0.9.9;support sonoma 14.4.1