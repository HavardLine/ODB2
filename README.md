# ODB2 connection notes

using a ELM327 WIFI interface

### WIFI hotspot information
IP 192.168.0.10, port 35000


### Commands
* 0100 list valid commands
* 010C return motor RPM (hex, needs to be divided by 4)

### Useful links
https://learn.sparkfun.com/tutorials/obd-ii-uart-hookup-guide/obd-commands
https://en.wikipedia.org/wiki/OBD-II_PIDs

### Car comunications
```
TX 0100
RX 41 00 BF 9F F9 91
RX 41 00 80 00 00 00

TX 010c
RX 41 0C 0B 30 ;this is 716rpm
```
