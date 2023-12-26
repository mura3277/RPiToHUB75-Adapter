# Raspberry Pi 4 40 Pin GPIO to HUB75 Adapter Board

This PCB maps the Pi GPIO to the HUB75 header. The remaining pins are mapped to a 8-pin header on the board. It is intended this is used with the [RGB LED Matrix](https://github.com/hzeller/rpi-rgb-led-matrix/tree/master) library.

Pin mapping for the remaining pins from the Pi GPIO:

|Row 1     | Row 2    |
|----------|:--------:|
|3v3 Power |5v Power  |
|GPIO 4    |GND       |
|GPIO 2 I2C|GPIO 3 I2C|
|GPIO 15   |GPIO 14   |
|GPIO 18   |GPIO 17   |
|GPIO GND  |GPIO 27   |
|GPIO 23   |GPIO 22   |
|GPIO 24   |GPIO 10   |
|GND       |GPIO 9    |
|GPIO 25   |GND       |

![](image.png)

# Change Log

## 6.0
-  Went back to the regular HUB75 mapping as outlined by the rpi-rgb-led-matrix repo.
-  Dropped some pins from the GPIO passthrough (extra GND, 3.3v).

## 5.0
-  Added a right angled tilt sensor to the board, connected to a GPIO pin.

## 4.0
-  Added buzzer to the board connected to a GPIO pin.
-  Split off the dedicated input pins to a 6 pin IDC so it can easily be connected to a daughter board.

## 3.0
-  Added 3 pin fan header connected to a GPIO pin for cooling a pi within an enclosure.

## 2.0
-  Added solder jumper pads to support displays with or without the extra data line E.

## 1.0
- Initial Version.