## Genesis F7 – Flight Controller

Genesis F7 is the first custom-built flight controller powered by the STM32F7 series, engineered entirely from the ground up. Designed with a focus on stability, performance, and reliability, it offers a compact yet powerful PCB layout—featuring USB-C programming, a robust 3.3V power system, and high-precision gyro sensing.




## FEATURES

- STM32F722RET6 microcontroller
- ICM-42688-P IMU (Gyro) via SPI1
- USB-C port for programming and communication
- VBAT monitoring through PA0 (ADC)
- 4× Motor Outputs 
- On-board status LEDs
- 3.3V regulator (AMS1117)
- SWD programming header
- 25 MHz crystal
- 2-layer PCB design




## Hardware Overview



> **MICROCONTROLLER**
> - STM32F7 series
> - 25 MHz crystal connected on PH0 / PH1
> - SWD for firmware flashing
> 
> **IMU**
> - ICM-42688-P
> - INT pin routed to MCU
> 
> 
> **MOTORS CONNECTIONS**
> - PB4 → Motor 1
> - PB5 → Motor 2
> - PB6 → Motor 3
> - PB7 → Motor 4
> 
> **POWER CONNECTION**
> - 5V → from ESC BEC
> - AMS1117 → 3.3V rail
> - VBAT → PA0
> 
> **USB-C INTERFACE**
> - PA11
> - PA12
> 
> **PROGRAMING / DEBUGGING**
> 
> Standard SWD header:
> - SWCLK
> - SWDIO
> - NRST
> - 3V3
> - GND
> 
> **CLOCK SYSTEM**
> 
> - 25 MHz crystal oscillator.
> 
> **USB-C**
> 
> - PA11
> - PA12
> 
> **PROGRAMMING**
> 
> SWD header:
> - SWCLK
> - SWDIO
> - NRST
> - 3V3
> - GND
