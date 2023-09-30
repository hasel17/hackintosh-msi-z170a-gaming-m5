# hackintosh-msi-z170a-gaming-m5
OpenCore 0.9.5 Sonoma EFI for MSI Z170A Gaming M5

Specs
-Intel Core i7-8700<br />
-UHD 630<br />
-NVIDIA GeForce GTX 1660 Ti<br />
-16GB DDR4-3000<br />
-MSI Z170A Gaming M5 modded with CoffeeTime<br />
-128GB SATA SSD<br />
-1TB NVMe SSD<br />
-TP-Link WN725N V2 USB WiFi<br />
-Generic USB Bluetooth 5.0 CSR<br />
-Killer E2400 LAN<br />
-AsMedia USB 3.1 Controller<br />


OS Tested<br />
-macOS 14.0 Sonoma<br />
-macOS 13.0 Ventura<br />

Works:
-QE/CI UHD 630
-Sleep/Shutdown/Restart
-LAN+WiFi+Bluetooth
-HDMI/DVI+Audio
-Audio Out+Mic in
-Power management/Turbo Boost/C-state (idle)

Not working:
-1660 Ti (disabled  with dsdt)
-Front USB 3.0 (XHCI limitation on macOS)

BIOS settings :
-XHCI hand off     : on
-VT-d              : off
-Above 4G decoding : on
-DVMT size         : 128MB
-Initiate Graphic  : IGD
-CGF Lock          : off
-Windows 10 WHQL   : on
-Windows 7 support : off
-fastboot          : off
-superio serial    : off
-SATA mode         : AHCI
-m.2 genie         : off
