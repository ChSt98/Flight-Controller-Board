# Flight-Controller-Board
Flight Controller board for the Flightsystems software. This board is not needed to run the software but is usefull for a compact package with all needed sensors.
### Built in sensors:
- MPU9250 (with magnetometer) or MPU6500 (without magnetometer)
- BME280
- QMC5883 (Not needed and can be omitted if MPU9250 is used or a compass on a GPS unit is used)
- WS2812B
- Buck DC-DC regulator that supplys 5V to Teensy 4.0 and 3.3V to sensors
- EByte E28 2G4MxxS (xx is for the power in dB. 12 is 15mW, 20->100mW and 27->500mW. This must be chosen or limited to the regions max allowed transmit power. EU is max 10mW for non spreadspectrum and 100mW for spreadspectrum. Our link system will probably use non spreadspecturm at first.)
### Outputs:
The board has almost all free pins broken out for use with other sensors, outputs and inputs.

