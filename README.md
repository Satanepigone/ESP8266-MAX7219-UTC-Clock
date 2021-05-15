# ESP8266-MAX7219-UTC-Clock

## Background
A few days ago, I was seraching the Internet/Online Shops for a simple, accurate desktop clock with good looking.
But, these clocks are all not very satisfying nor meet my demand:
Radio Wave/GPS/NTP synchronized, accurate, displaying the seconds, be able to selecet and switch between time zones, auto DST, (and good looking).
Thus I decide to DIY it.

This project is based on [max7219_matrix_clock3](https://github.com/tehniq3/max7219_matrix_clock3) by [Nicu FLORICA (niq_ro)](https://github.com/tehniq3).

## Install
### Preparation
#### Hardware
- one NodeMCU Board (ESP8266)
- 4 MAX7219 dot LED 8x8 Matrix display (so acutally 32x8)
- one DS3231 RTC(Real Time Clock) Module (requires one CR2032 battery)
- a few Dupont Cable (jump wire) 
#### Software
- latest release of .ino file
- Arduino IDE
- CP2102 driver

### Steps
1.Download and install [CP2102 driver](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers).
2.Download and install [Arduino IDE](https://www.arduino.cc/en/software).
3.Add ESP8266 support for the Arduino IDE
4.Select Board as "NodeMCU" in Arduino IDE
5.Open the latest release of .ino file by Arduino IDE
6.Connect the NodeMCU Board (ESP8266) to your computer using a micro-usb cable.
7.Check the COM port it uses and select it in Arduino IDE
8.Flash the codes on your NodeMCU.

## Usage

## Todo

## License
