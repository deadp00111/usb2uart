# HT42B534 USB 2 UART Board

A simple USB to UART board. Designed with KiCad. Manufactured and tested.

![Front](Front.png)
![Back](Back.png)

## How to use

1. Plug USB to your PC
2. Wire VIO to either V33O(3.3V) or VDD(5V)
3. Connect TX, RX & GND (optionally VIO) to other devices

The voltage of RX/TX should match VIO.



## USB Device Info

`lsusb` output:

```shell
$ lsusb
Bus 000 Device 001: ID 04d9:b534 Holtek Semiconductor, Inc. USB TO UART BRIDGE  Serial: 0000
```

System Information:

```
USB TO UART BRIDGE:

  Product ID:	0xb534
  Vendor ID:	0x04d9  (Holtek Semiconductor, Inc.)
  Version:	2.10
  Serial Number:	0000
  Speed:	Up to 12 Mb/s
  Manufacturer:	HOLTEK
  Location ID:	0x00142000 / 12
  Current Available (mA):	500
  Current Required (mA):	100
  Extra Operating Current (mA):	0
```
