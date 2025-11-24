# Genesis F7 – Flight Controller

Genesis F7 is the first custom-built flight controller powered by the STM32F7 series, engineered entirely from the ground up. Designed with a focus on stability, performance, and reliability, it offers a compact yet powerful PCB layout—featuring USB-C programming, a robust 3.3V power system, and high-precision gyro sensing.

---

## Features

- **STM32F722RET6** microcontroller  
- **ICM-42688-P** IMU via SPI1  
- **USB-C** port for programming/communication  
- **VBAT monitoring** (PA0 ADC)  
- **4× Motor Outputs** (PB4–PB7)  
- **On-board status LEDs**  
- **3.3V regulator (AMS1117)**  
- **SWD programming header**  
- **25 MHz crystal oscillator**  
- **2-layer PCB design**


## Schematics


## 📐 Pinout Summary

| Function | MCU Pin |
|---------|---------|
| IMU SCK | PA5 | 
| IMU MISO | PA6 | 
| IMU MOSI | PA7 |
| IMU INT |     |
| VBAT | PA0 | 
| USB D– | PA11 | 
| USB D+ | PA12 | 
| Motor 1 | PB4 | 
| Motor 2 | PB5 | 
| Motor 3 | PB6 | 
| Motor 4 | PB7 | 
| SWCLK | PA14 |
| SWDIO | PA13 |
| NRST | NRST | 

---

