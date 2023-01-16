# LenovoX1EGen2-OSXCatalina-OpenCore

My Laptop Config:
CPU: i7-9750H
GPU: GTX 1650 MAX-Q
SSD: 512GB Samsung NVMe Drive
Screen: 1080p FHD Panel
WiFi: Intel AX200 Gig+

I have included the SSDT/ACPI custom patch files which turn off the Nvidia GPU and disable the Samsung NVMe drive due to MacOS incompatability with Turing and power consumption.

The Intel AX200 wifi chipset is working on 5G/2.4G using the OpenIntelWireless kexts.

This configuration of opencore is made for MacOS X Catalina, it may not work as intended for different software versions or hardware configs of this laptop.
