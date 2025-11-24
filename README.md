## GenesisF7 - FlightController
Genesis F7 is the first custom build flight controller , code powered by STM32F7 series build from scratch. This board can provide 3.3v power supply. Usb c programming. This controler is mostly focus kn stabilty and performance in a compact PCB


## FEATURES 

STM32F722RET6 (Brain)
ICM-42688-P IMU (Gyro)
USB-C
VBAT monitoring (PA0 ADC)
4× Motor outputs (PB4–PB7)
On-board LEDs
3.3V regulator (AMS1117)
SWD programming
25 MHz crystal clock
Compact 2-layer design


# Hardware Overview

> **Microcontroller**
>
> STM32F7
>
> **IMU**
>
> ICM-42688-P (SPI1)
>
> INT pin connected for gyro signaling
>
>
> **Motor Outputs**
>
> PB4 -> Motor 1
>
> PB5 -> Motor 2
>
> PB6 -> Motor 3
>
> PB7 -> Motor 4
> (Each output drives an ESC signal pin.)


Power

5V from ESC BEC → AMS1117 → 3.3V rail

VBAT input divider → PA0 (battery monitoring)


Clock

25 MHz main crystal (PH0, PH1)

Load capacitors placed close to the MCU


USB-C

Connected to PA11/PA12 (USB_FS)

CC resistors for proper detection


Programming

SWD header with SWCLK, SWDIO, NRST, 3V3, GND
