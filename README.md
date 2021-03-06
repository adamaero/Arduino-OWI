# Quick & Dirty
Download "Arduino-GPIO" below (and when extracting take the master folders out of their same name folders).

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

## Classes

* [Software One-Wire Slave Device, Slave::OWI](./src/Slave/OWI.h)
* [Programmable Resolution 1-Wire Digital Thermometer, DS18B20](./src/Driver/DS18B20.h)

## Dependencies

* [Arduino-GPIO](https://github.com/mikaelpatel/Arduino-GPIO)
