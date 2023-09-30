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
-QE/CI UHD 630<br />
-Sleep/Shutdown/Restart<br />
-LAN+WiFi+Bluetooth<br />
-HDMI/DVI+Audio<br />
-Audio Out+Mic in<br />
-Power management/Turbo Boost/C-state (idle)<br />

Not working:
-1660 Ti (disabled  with dsdt)<br />
-Front USB 3.0 (XHCI limitation on macOS)<br />

BIOS settings :
-XHCI hand off     : on<br />
-VT-d              : off<br />
-Above 4G decoding : on<br />
-DVMT size         : 128MB<br />
-Initiate Graphic  : IGD<br />
-CGF Lock          : off<br />
-Windows 10 WHQL   : on<br />
-Windows 7 support : off<br />
-fastboot          : off<br />
-superio serial    : off<br />
-SATA mode         : AHCI<br />
-m.2 genie         : off<br />
