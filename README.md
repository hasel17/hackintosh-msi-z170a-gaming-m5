# hackintosh-msi-z170a-gaming-m5
OpenCore 0.9.5 Sonoma EFI for MSI Z170A Gaming M5

Specs:<br />
-Intel Core i7-8700<br />
-AMD Radeon RX 5700 XT<br />
-16GB DDR4-3000<br />
-MSI Z170A Gaming M5 modded with CoffeeTime<br />
-256GB+500GB NVMe SSD<br />
-TP-Link WN725N V2 USB WiFi<br />
-Generic USB Bluetooth 5.0 CSR<br />
-Killer E2400 LAN<br />
-AsMedia USB 3.1 Controller<br />


OS Tested:<br />
-macOS 15.0 Sequoia Beta 7<br />
-macOS 14.0 Sonoma<br />
-macOS 13.0 Ventura<br />

Works:<br />
-QE/CI 5700 XT<br />
-Sleep/Shutdown/Restart<br />
-LAN+WiFi+Bluetooth<br />
-HDMI/DVI+Audio<br />
-Audio Out+Mic in<br />
-Power management/Turbo Boost/C-state (idle)<br />
-All SATA and M.2 NVMe Ports <br />
<br />
Not working: <br />
-Front USB 3.0 (XHCI limitation on macOS)<br />
<br />
BIOS settings : <br />
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
