STM32F446RE - I2C Master Testing
================================

This repository host the firmware for NUCLEO F446RE board that utilizes STM32F446RE microcontroller to read data from an I2C slave.
This firmware is used to test the communication with the firmware on [alwint3r/esp32-ultrasonic-i2c-slave](https://github.com/alwint3r/esp32-ultrasonic-i2c-slave).

## How It Works

The STM32 device reads the distance measurement from the ESP32 device every 30 seconds and then print the result to the UART2 connected to the on-board ST-LINK.

## Wiring Information

Pin | Function
----|-----------------
PB9 | I2C SDA
PB8 | I2C SCL
PA2 | "Debug" UART TX
PA3 | "Debug" UART RX


