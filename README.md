# SR Air Quality

Air quality device based on [Wemos D1 mini](https://www.wemos.cc/en/latest/d1/d1_mini.html) Wi-Fi board, [MH-Z19B](https://revspace.nl/MH-Z19B) CO₂ sensor and [PMSA003](datasheets/PMSA003.pdf) particle concentration sensor.

## Firmware: 
Compiled using [ESPHome](https://esphome.io/). For easy integration into [Home Assistant](https://www.home-assistant.io/).

Instructions on how to compile `base.yaml` into firmware: https://esphome.io/guides/getting_started_command_line.html#first-uploading.

## Measures:
- CO₂ in ppm
- PM 1.0 in µg/m³	
- PM 2.5 in µg/m³	
- PM 10.0 in µg/m³	
- Temperature. I'd not trust it too much, it's from internal temperature sensor of MH-Z19B

## Price 
As of 17 July 2021:
- Wemos D1 mini: 2.61$
- MH-Z19B: 18.96$
- PMSA003: 14.9$

Total: *$36.47*
