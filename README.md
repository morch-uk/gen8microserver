# gen8microserver

helpful site: https://github.com/laris/HPE_Microserver_Gen8
https://pingtool.org/latest-hp-ilo-firmwares/

## Drives

front bay drives filled with 4x SATA - removed for first install

one SSD in the optical bay also

sd card internally - removed for first install

## Bios Options

2019 firmware

AHCI SATA raid controller mode in the F9 Menu instead of (software) raid


## Install proxmox 9.1

installing through ilo iso mount gets a lot of i/o errors and fails, installs ok with usb drive

but error after first boot
<img width="955" height="477" alt="image" src="https://github.com/user-attachments/assets/eddc926c-6f5c-431d-a264-88795359f865" />

so disabled vt-t "Boot > F9 Bios > System > Processor Options > VT-d = disabled"
src: https://forum.proxmox.com/threads/updated-to-8-2-dma-error.145907/




