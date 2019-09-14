# GPIO Expander
An I2C controlled, breadboard friendly GPIO exansion board based on the Texas Instruments PCF8574 with builtin buttons and LED's for prototyping.
## PCB Layout
![GPIO Expander Board Image](https://github.com/AdamKeher/GPIO-Expander/blob/master/files/GPIO_Front.png)
![GPIO Expander Board Image](https://github.com/AdamKeher/GPIO-Expander/blob/master/files/GPIO_Back.png)
![GPIO Expander Board Image](https://github.com/AdamKeher/GPIO-Expander/blob/master/files/board.png)
## About
The PCF8574 device provides general-purpose remote I/O expansion for most microcontroller families by way of the I2C interface (serial clock(SCL), serial data (SDA)].
The device features an 8-bit quasi-bidirectional I/O port (P0–P7), including latched outputs with highcurrent drive capability for directly driving LEDs. Each quasi-bidirectional I/O can be used as an input or output without the use of a data-direction control signal. At power on, the I/Os are high. In this mode, only a current source to VCC is active.

The board has builtin buttons and LED's to help quickly prototype solutions and is able to be mounted either vertically or horizontally.

A switchable jumper is provided to connect all tactiles switches to VCC or to GND.
## Features
* 2.5V to 6.0V operation
* Arduino Library
* 8 Builtin tactile switches
* 8 Builtin controllable LED's
* Breadboard friendly
* Based on the popular PCF8574 I2C IC
* Low Standby-Current Consumption of 10 μA Max
* Open-Drain Interrupt Output
* Compatible With Most Microcontrollers
* Latched Outputs With High-Current Drive
* Single Maskable output register for all IO ports
