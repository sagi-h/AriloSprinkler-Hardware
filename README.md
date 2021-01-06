# AriloSprinkler-Hardware
OpenSprinkler ESP32-WROOM Hardware Design variant including a Lora E22-900M30S-SX1262 and made in Kicad software.

HW features:
- 8 valve AC driver compatible with OpenSprinkler Zone Expanders
- Lora E22-900M30S-SX1262 long range transceiver (up to 30dBm)
- USB interface for debugging/flashing
- Ethernet interface (Exemplary module: https://de.aliexpress.com/item/2042562851.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- RF Transmitter interface (Exemplary module: https://de.aliexpress.com/item/4001119703303.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- Compatible with DIN rails (Used holding system: https://de.aliexpress.com/item/32827395562.html?spm=a2g0s.9042311.0.0.27424c4daFHBJU)
- Reworked current measurement with inverted precision rectifier required due to the ADC of the ESP32
- RTC
- Button switches

Tested features:
- Opensprinkler SW features work
- Lora transceiver works
– Current measurement works
– Valve control works
– RTC works
– Button switches work

The compatible SW can be found in the following OpenSprinkler Firmware branch:
https://github.com/arijav/AriloSprinkler-Firmware

For questions send a message to:
gmail email: arijav2020
