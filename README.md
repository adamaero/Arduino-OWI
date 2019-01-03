# Quick & Dirty
Download "Arduino-GPIO" (and when extracting take the master folders out of their same name folders).

# Arduino-OWI
The OWI library has been developed to support the implementation of
1-wire bus managers and device drivers. The library includes a GPIO
based software and DS2482 based hardware bus manager, Slave device
support class (emulation), and device driver for DS18B20.

Version: 1.8

## Example Sketch

* [DS18B20, Slave](./examples/Slave/DS18B20)

[ATtiny](./examples/ATtiny) and [DS2482](./examples/DS2482)
variants.

## Dependencies

* [Arduino-GPIO](https://github.com/mikaelpatel/Arduino-GPIO)

## Classes

* [Abstract One-Wire Bus Manager and Device Interface, OWI](./src/OWI.h)
* [Software One-Wire Bus Manager, GPIO, Software::OWI](./src/Software/OWI.h)
* [Hardware One-Wire Bus Manager, DS2482, Hardware::OWI](./src/Hardware/OWI.h)
* [Software One-Wire Slave Device, Slave::OWI](./src/Slave/OWI.h)
* [Programmable Resolution 1-Wire Digital Thermometer, DS18B20](./src/Driver/DS18B20.h)
* [One-Wire Remote Arduino, Master](./src/Driver/Arduino.h)
