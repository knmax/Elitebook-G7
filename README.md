HP Elitebook G7-Series

Tested on: HP Elitebook 840 G7
Should be working on all G7 Series - maybe Battery needs it's own Patch

dsdt_orig.aml needs to be removed before using this EFI to boot.

OC 0.6.6 with macOS 11.2


SPECS:

Model: HP Elitebook 840 G7

CPU: Intel Core i5 10210U

GPU: Intel UHD 620

RAM: 16GB - 8+8

Storage: 256GB SSD

WIFI/BT: Intel AX201NGW


STATUS:

working:

Keyboard incl. Brightness and Volume Buttons

Trackpad

USB-Ports including Portmapping – 2 different USB-Maps
USB-C Dock only working with USBMapDockG7.kext – only the back port is mapped – front port coming soon

Speakers + 3.5mm Combojack

Webcam

Battery

WIFI with integrated Intel AX201NGW

not working:

Sleep 

Bluetooth with integrated Intel AX201NGW

Fingerprint

Integrated Microphone


Special thanks go to redditor u/Ragip_mehmet for creating the SSDT-BATT and according plist-patches.
