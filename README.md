# devkit-neopixel-lib
Thhis is the Neopixcel driver for [MXChip IoT DevKit](aka.ms/iot-devkit), which can control a strip of [Adafruit NeoPixcel](https://www.adafruit.com/category/168) , addressable RGB LEDs.

The main MCU of IoT DevKit board is [STM32F412G](https://www.st.com/en/microcontrollers/stm32f412.html) @ 100 MHz, so should be compatible with any STM32 only need to tune the timing in [neopixel.cpp](./neopixel.cpp).

