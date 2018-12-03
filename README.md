# "End Cap" PCBs for OreSat

These are the "end cap" PCBs that attach to the +Z and -Z ends of the satellites. It's not clear what exactly
we're going to put on these boards besides magnetometers; there may be more in the future?

## Features

- Single vertical 10mm tall 1.27 mm connector that plugs into the "end card" card.
- No available RF connectors.
- Standard TPS63070-bsaed buck/boost SPS (Vin = 2.5 to 7 V, Vout = 3.3V)
- Has our standard/favorite STM32F042K6 microcontroller.
   - With SWD, UART (FTDI), and CAN (to the backplane).

![OreSat +Z End Cap Picture](https://github.com/oresat/oresat-endcaps/blob/master/oresat-zpos-endcap.png)

## Connector information

- TBD.

## LICENSE

Copyright Portland State Aerospace Society 2018.

This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the CERN OHL v.1.2. [http://ohwr.org/cernohl](http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable conditions.

## Version Information

Version | Date       | Notes
--------|------------|-------------------------
1.0     | 2018/12/03 | First boards based off of Joe's updated CAD.


