# RP2040-Shim
Dual-core ARM Cortex M0+ shim for PoE-FeatherWing, functionally equivalent to Feather RP2040.

With parts for the [M4-Shim](https://www.tindie.com/products/silicognition/m4-shim/) scarce, it seemed wise to come up with a well-supported alternative.

### Description

This is an adaptation of the excellent
[Adafruit Feather RP2040](https://github.com/adafruit/Adafruit-Feather-RP2040-PCB),
redesigned specifically for use with the equally excellent
[PoE-FeatherWing](https://hackaday.io/project/168356-poe-featherwing).

The goal was to create a compact system with Power over Ethernet, Ethernet connectivity and
a powerful processor capable of supporting [CircuitPython](https://circuitpython.org/).
Because of the bulky RJ45 jack and flyback transformer on the PoE-FeatherWing, it was not
possible to mount a traditional Feather on top.  This redesign takes the relevant circuitry
of the Adafruit Feather RP2040 and shapes it so it fits in the gaps between the
tall components of the PoE-FeatherWing.  This way it can be mounted on top for an extremely
compact solution.

The only thing missing versus the Feather RP2040 is the battery support circuitry,
which did not seem necessary in a PoE design, the Qwiic / STEMMA QT connector, and only 2MB of flash.

The hardware is sold with [CircuitPython](https://github.com/adafruit/circuitpython) pre-installed.

### License

This redesign by Silicognition LLC is licensed as Creative Commons Attribution/Share-Alike,
just like the Adafruit Feather RP2040 it is based on.

Original Adafruit license statement:

Feather RP2040

Open source PCB files for Feather RP2040

PCB format is EagleCAD schematic and board layout

For more details, check out the product pages at

    https://www.adafruit.com/products/4884

We are releasing these files so folks can start creating custom designs based on the RP2040 chip. This design has been built and tested successfully

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Designed by Adafruit Industries.
Creative Commons Attribution, Share-Alike license, check license.txt for more information All text above must be included in any redistribution