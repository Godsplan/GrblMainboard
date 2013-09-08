GrblMainboard - v3.1
=============

A new Solution with Grbl Firmware to use cnc mills or 3d printers.

created by Christoph Kielhorn (Godsplan), Frank Herrmann (xpix)

---------------

The GrblMainboard includes the following features:

- ATMega328u (DIL Package)
- USB Connection using USB-FTDI
- Opto-Couplers for USB Connection
- ICSP-Connector for flashing the firmware
- GRBL Firmware (v0.8) and GRBL Pinout
- Connector for External Buttons for spindle, reset, etc...
- Support for four Pololu A4988 or Pololu DRV8825 Modules
- Supports dual-Y motion
- Supports cooling fan
- Supports XYZ-Limit in extra pinheader
- LED's for every axis
- LED's for every Limit
- Power LED
- AK500 Screw terminal for Steppers
- Connector for Bluetooth TTL Modules


---------------
v3.1
- Added Hall Sensor Pinout

v3.0 - GrblMainboard Backfork
- Added Pin Locations
- Added I2C Connectors for Sensors

v0.9.1 - XStepper Development

- add optional pullup resistors (1k/5V) for Hallo Sesnor switches (Cherry MP101401)
   http://www.cherrycorp.com/english/sensors/pdf/MP1014_Series.pdf


v0.9 - Initial Development

- created schema files
- created .brd
