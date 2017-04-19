# MCP1824-ADJ 0.8V-4.5V 300mA LDO Breakout Board

A small breakout board for the MCP1824-ADJ Adjustable LDO from Microchip designed
to deliver 300mA at voltages ranging from 0.8V to 4.5V from its fused USB Micro B
jack. It is laid out to provide power rails to a standard solderless breadboard
with the following characteristics:

* 1A @ 5V fused and clamped (1.8A & 5.1V) direct from the USB Micro B input jack,
* 300mA @ 0.8-4.5V from the MCP1824-ADJ LDO.

![MCP79410](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/3156bc1cd70eb2ba24a671ff53dea241.png) ![Bottom](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/e0bc889c0ae8f9f21f89f404eef6888f.png)

You can [order this board](https://oshpark.com/shared_projects/W8U1qi3h) ready made
from oshpark.com. It's 1 sq. in. so it will cost $5 for 3.

I use these to prototype new projects needing an LDO. Feel free to do the same.
I designed this to be easy to hand solder.

The passives are all 0603 ERJ-3GEYJxxx Panasonic resistors and GRM188xxxxxx
capacitors from muRata. See the BOM for a complete parts list. Everything is
available from Digikey.

There is a jumper (Rev A) or switch (Rev B) to toggle the SHDN control of the
MCP1824-ADJ. An LED on each power rail indicates live power to that rail. The
grounds are all connected at USB potential.

## About the MCP1824-ADJ LDO Linear Voltage Regulator

The [Datasheet](http://ww1.microchip.com/downloads/en/DeviceDoc/22070a.pdf)
is your primary reference.

The MCP1824/MCP1824S is a 300 mA Low Dropout (LDO) linear regulator that provides
high current and low output voltages. The MCP1824 comes in a fixed or
adjustable output voltage version, with an output voltage range of 0.8V to 5.0V.
The 300 mA output current capability, combined with the low output voltage
capability, make the MCP1824 a good choice for new sub-1.8V output voltage LDO
applications that have high current demands.

### Features

* 300 mA Output Current Capability
* Input Operating Voltage Range: 2.1V to 6.0V
* Adjustable Output Voltage Range: 0.8V to 5.0V
* Low Dropout Voltage: 200 mV Typical at 300 mA
* Typical Output Voltage Tolerance: 0.4%
* Stable with 1.0 µF Ceramic Output Capacitor
* Fast Response to Load Transients
* Low Supply Current: 120 µA (typical)
* Low Shutdown Supply Current: 0.1 µA (typical)
* Fixed Delay on Power Good Output
* Short Circuit Current Limiting and Over-temperature Protection
* 5-Lead Plastic SOT-223, SOT-23 Package

## Bugs, Issues and Contributions

If you discover any issues with it or the parts used please let me know by opening
an issue or forking the repo and submitting a pull request with your fix.

Happy hacking!
