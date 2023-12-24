# Raspberry Pi 4 40 Pin GPIO to HUB75 Adapter Board

This PCB converts pins 23-40 to the HUB75 header. The remaining pins 1-22 are mapped to the remaining 20-pin header. It is intended this is used with the [RGB LED Matrix](https://github.com/hzeller/rpi-rgb-led-matrix/tree/master) library with a custom mapping as this adapter accesses different GPIO from the regular pin mapping. The mapping is as follows:

|Row 1        | Row 2       |
|-------------|:-----------:|
|GPIO 8 (G1)  |GPIO 11 (R1) |
|GND          |GPIO 0 (B1)  |
|GPIO 7 (G2)  |GPIO 5 (R2)  |
|GPIO 1 (E)   |GPIO 6 (B2)  |
|GPIO 12 (B)  |GPIO 13 (A)  |
|GPIO 16 (D)  |GPIO 19 (C)  |
|GPIO 20 (STB)|GPIO 26 (CLK)|
|GND          |GPIO 21 (OE-)|

![](image.png)
