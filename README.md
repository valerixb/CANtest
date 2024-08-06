# CANtest
test with CAN interface for MECOS chopper

Standard CAN DB9 pinout:

| DB9 pin | CAN signal | wire color |
|--------:|------------|------------|
|   2     |   CAN L    |   green    |
|   3     |    GND     |            |
|   7     |   CAN H    |   yellow   |

120 Ohm termination on both ends of the bus; 
even better to do a split temination with two 60 ohm resistors a
nd a 4n7 cap to GND.

