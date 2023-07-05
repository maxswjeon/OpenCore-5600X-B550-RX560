# OpenCore for AMD 5600X / B550 / RX 560 4GB

## Basic Information

### Hardware

| **Component** | **Model**                          |
| ------------- | ---------------------------------- |
| CPU           | AMD Ryzen 5600X                    |
| Motherboard   | ASUS B550M Pro4                    |
| GPU           | AMD Radeon 560 4GB                 |
| RAM           | Samsung DDR4-3200 32GB x 4 (128GB) |
| Audio Chipset | ALC1200                            |
| OS Disk       | SK Hynix P31 1TB                   |

## Troubleshooting

### SMBIOS Select

MacPro7,1 didn't work for me. Try iMac18,1.

### Shutdown & Reboot Fix

RTC is not the problem. Disable the internal LED Controller by USBMap.

https://www.tonymacx86.com/threads/after-shutdown-or-restart-need-to-unplug-to-boot-asrock-b550m-pro4.305349/

https://www.tonymacx86.com/threads/shutdown-and-reboot-problem-on-amd-b550m-platform.305622/

## What doesn't work

- Internal Michrophone (I use external microphone with USB Audio Interface)
