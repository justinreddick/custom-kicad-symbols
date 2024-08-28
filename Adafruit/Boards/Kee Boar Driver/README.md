# KB2040 Kee Boar Driver Board Documentation

## Overview

The KB2040 is a compact development board by Adafruit, designed for custom keyboard projects. It is powered by the RP2040 microcontroller, providing a robust and versatile platform for DIY electronics and embedded systems.

## Features

- **Microcontroller:** RP2040
- **Flash Memory:** 8MB
- **USB:** USB-C connector for power and data
- **Debugging:** SWD pads available
- **Power Supply:** 3.3V regulator, capable of up to 500mA
- **Dimensions:** 22.9mm x 50.8mm
- **Additional Features:** Boot button, reset button, and user-controllable LED

## Pinout Diagram

The KB2040 board has a total of 26 pins, including 22 GPIO pins, 3 ground pins, and USB D+ and D- pins. Below is a detailed list of the pinout based on the [KB2040 Pinouts page](https://learn.adafruit.com/adafruit-kb2040/pinouts).

| Pin | Name  | Function           | Description                                                    |
|-----|-------|--------------------|----------------------------------------------------------------|
| 1   | GND   | Ground             | Common ground pin                                              |
| 2   | 3V3   | 3.3V Output        | Provides 3.3V from regulator                                   |
| 3   | A0/D0 | GPIO, ADC0, I2C1_SDA, SPI0 RX | General-purpose I/O, Analog input 0, I2C1 Data, SPI0 Receive  |
| 4   | A1/D1 | GPIO, ADC1, I2C1_SCL, SPI0 SCK | General-purpose I/O, Analog input 1, I2C1 Clock, SPI0 Clock   |
| 5   | A2/D2 | GPIO, ADC2         | General-purpose I/O, Analog input 2                            |
| 6   | A3/D3 | GPIO, ADC3         | General-purpose I/O, Analog input 3                            |
| 7   | D4    | GPIO, SPI0 TX      | General-purpose I/O, SPI0 Transmit                             |
| 8   | D5    | GPIO, I2C0_SDA, PWM0 | General-purpose I/O, I2C0 Data, PWM channel 0                  |
| 9   | D6    | GPIO, I2C0_SCL, PWM1 | General-purpose I/O, I2C0 Clock, PWM channel 1                 |
| 10  | D7    | GPIO, UART1 TX     | General-purpose I/O, UART1 Transmit                            |
| 11  | D8    | GPIO, UART1 RX     | General-purpose I/O, UART1 Receive                             |
| 12  | D9    | GPIO, PWM2         | General-purpose I/O, PWM channel 2                             |
| 13  | D10   | GPIO, PWM3         | General-purpose I/O, PWM channel 3                             |
| 14  | D11   | GPIO, SPI0 TX      | General-purpose I/O, SPI0 Transmit                             |
| 15  | D12   | GPIO, SPI0 RX      | General-purpose I/O, SPI0 Receive                              |
| 16  | D13   | GPIO, SPI0 SCK     | General-purpose I/O, SPI0 Clock                                |
| 17  | D14   | GPIO, I2C0_SDA     | General-purpose I/O, I2C0 Data                                 |
| 18  | D15   | GPIO, I2C0_SCL     | General-purpose I/O, I2C0 Clock                                |
| 19  | D16   | GPIO               | General-purpose I/O                                            |
| 20  | D17   | GPIO               | General-purpose I/O                                            |
| 21  | D18   | GPIO               | General-purpose I/O                                            |
| 22  | D19   | GPIO               | General-purpose I/O                                            |
| 23  | D20   | GPIO               | General-purpose I/O                                            |
| 24  | D21   | GPIO               | General-purpose I/O                                            |
| 25  | D-    | USB Data -         | USB negative data line                                         |
| 26  | D+    | USB Data +         | USB positive data line                                         |

## Dimensions

The KB2040 shares the same dimensions as the SparkFun Pro Micro but with two additional pins, resulting in a size of **22.9mm x 50.8mm**.

[KB2040 Dimensions](https://cdn.sparkfun.com/assets/parts/1/4/7/0/0/15795-ProMicrov13-Dimensions.png)

*Source: [SparkFun Pro Micro](https://www.sparkfun.com/products/15795)*

## CAD Files

To integrate the KB2040 into your own designs, the following resources are available:

- **STEP File:** [Download from GrabCAD](https://grabcad.com/library/adafruit-kb2040-1)

## Reference Table

Below is a table outlining where specific information about the KB2040 was sourced from:

| Information Type         | Source                                                              | Reference Link                                                                                                   |
|--------------------------|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| KB2040 Datasheet          | Adafruit                                                           | [Link to Datasheet](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://cdn-learn.adafruit.com/downloads/pdf/adafruit-kb2040.pdf) |
| Module Dimensions         | SparkFun Pro Micro                                                 | [Link to SparkFun Product](https://www.sparkfun.com/products/15795)                                              |
| Pinouts Information       | Adafruit KB2040 Pinouts Page                                       | [Link to Pinouts Page](https://learn.adafruit.com/adafruit-kb2040/pinouts)                                       |
| CAD .STEP File            | GrabCAD                                                            | [Link to GrabCAD](https://grabcad.com/library/adafruit-kb2040-1)                                                 |

## Usage Notes

When using the KB2040 in your own projects, consider the following:

1. **Pinout Compatibility:** Ensure that your design correctly maps the pins to their intended functions.
2. **Power Requirements:** The onboard 3.3V regulator can supply up to 500mA, so plan your power budget accordingly.
3. **USB Data Lines:** The D+ and D- pins are used for USB communication and should be connected appropriately if your project involves USB data transfer.

---

This template should now accurately reflect the correct pinout and provide a comprehensive guide for users working with the KB2040.
