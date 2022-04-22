# 0xB2 - splinky
Pro-Micro/Elite-C replacement with USB-C and RP2040.

Designed for use in custom mechanical (split) keyboards, but many other uses are possible.

## Features:

 * Pro-micro / Sparkfun RP2040 compatible footprint, with 5 extra pins at bottom (Elite-C style)
 * Raspberry Pi RP2040 MCU
 * Up to 16MB flash memory _(depending on component selection and availability)_
 * User LED & USB VBUS detect
 * Low profile USB-C mid-mount connector
 * Designed to be manufactured and assembled by all common PCBA services (including JLCPCB)

## Pinout

The pinout is compatible with the widely available [SparkFun RP2040](https://www.sparkfun.com/products/18288),
with extra GPIO10..14 pins broken out on the lower side.

A user LED is tied to GPIO17, can be used for UF2 bootloader status indication, or any other purpose
(or turned OFF, no annoying always-on power LED).

USB VBUS detection on GPIO25.

## Manufacturing

Releases contain required information (gerbers, bom, pos) for assembly by JLCPCB.

## Credits

 * Raspberry Pi Foundation
   * [RP2040 Datasheet](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf)
   * [Hardware design with RP2040](https://datasheets.raspberrypi.com/rp2040/hardware-design-with-rp2040.pdf)
 * [SparkFun Pro Micro - RP2040](https://www.sparkfun.com/products/18288)
 * [Adafruit kb2040](https://learn.adafruit.com/adafruit-kb2040)
 * [sea-picro](https://github.com/joshajohnson/sea-picro) - _similar project, I borrowed some cheaper component references ^^_
 * ...
