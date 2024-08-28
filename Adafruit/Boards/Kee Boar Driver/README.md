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

The KB2040 board has a total of 26 pins, including GPIO pins, ground pins, and various special function pins. Below is a detailed list of the pinout based on the [KB2040 Pinouts page](https://learn.adafruit.com/adafruit-kb2040/pinouts).

### Left Side Pinout

| Pin | Name  | Function                          | Description                                                    |
|-----|-------|-----------------------------------|----------------------------------------------------------------|
| 1   | D+    | USB Data +                        | USB positive data line                                         |
| 2   | D0    | GPIO, I2C1_SDA, SPI0 RX           | General-purpose I/O, I2C1 Data, SPI0 Receive                   |
| 3   | D1    | GPIO, I2C1_SCL, SPI0 SCK          | General-purpose I/O, I2C1 Clock, SPI0 Clock                    |
| 4   | GND   | Ground                            | Common ground pin                                              |
| 5   | GND   | Ground                            | Common ground pin                                              |
| 6   | D2    | GPIO, SPI0 TX                     | General-purpose I/O, SPI0 Transmit                             |
| 7   | D3    | GPIO, I2C0_SDA, PWM               | General-purpose I/O, I2C0 Data, PWM                            |
| 8   | D4    | GPIO, I2C0_SCL, PWM               | General-purpose I/O, I2C0 Clock, PWM                           |
| 9   | D5    | GPIO, UART1 TX                    | General-purpose I/O, UART1 Transmit                            |
| 10  | D6    | GPIO, UART1 RX                    | General-purpose I/O, UART1 Receive                             |
| 11  | D7    | GPIO, UART0 TX                    | General-purpose I/O, UART0 Transmit                            |
| 12  | D8    | GPIO, UART0 RX                    | General-purpose I/O, UART0 Receive                             |
| 13  | D9    | GPIO, PWM                         | General-purpose I/O, PWM                                       |

### Right Side Pinout

| Pin | Name  | Function                          | Description                                                    |
|-----|-------|-----------------------------------|----------------------------------------------------------------|
| 14  | D10   | GPIO                              | General-purpose I/O                                            |
| 15  | MOSI  | SPI Data Out                      | SPI Master Out, Slave In (MOSI)                                |
| 16  | MISO  | SPI Data In                       | SPI Master In, Slave Out (MISO)                                |
| 17  | SCK   | SPI Clock                        | SPI Clock                                                      |
| 18  | A0    | GPIO, Analog Input                | General-purpose I/O, Analog Input                              |
| 19  | A1    | GPIO, Analog Input                | General-purpose I/O, Analog Input                              |
| 20  | A2    | GPIO, Analog Input                | General-purpose I/O, Analog Input                              |
| 21  | A3    | GPIO, Analog Input                | General-purpose I/O, Analog Input                              |
| 22  | 3.3V  | 3.3V Output                       | Provides 3.3V from regulator                                   |
| 23  | RESET | Reset                             | Reset pin                                                      |
| 24  | GND   | Ground                            | Common ground pin                                              |
| 25  | RAW   | Raw Voltage Input                 | Input for unregulated voltage                                  |
| 26  | D-    | USB Data -                        | USB negative data line                                         |

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

This documentation now accurately reflects the correct pinout order for the KB2040, providing a clear and useful guide for users working with the board.
