# Arduino (True Core) - Mediatek MT2625 - Quectel BC66

PROJECT IS MOVED TO: https://github.com/Wiz-IO/Arduino-Quectel-BC66

**A few words in the beginning**
* This project not an official product of Mediatek / Quectel
* The project is based on Quectel OpenCPU and **Reverse Engineering** ( a lot of time )
* The port is bound to the firmware version


**Chipset Mediatek MT2625 SoC**
Ultra-low power, 3GPP Release-14 enabled NB-IoT platform for wide-ranging home, civic, industrial or mobile applications
https://www.mediatek.com/products/nbIot/mt2625
* Applications CPU: ARM Cortex-M 156 MHz (26MHz, 78MHz, 104MHz, 156MHz)
* Modem DSP: unknown, NB / CAT1
* RAM: 4M
* ROM: 4M
* IO: GPIO, SPI, I2C, I2S, PCM, SDIO, UART, USB
* OS: FreeRTOS
* NET: LwIP
* SSL: mbedtls
* Clinets: HTTP/S, MQTT, COAP, LWM2M 


**Module: Quectel BC66**
is a high-performance, multi-band NB-IoT module...
https://www.quectel.com/product/bc66.htm
* Test Board for the project: BC66-TE-B ( it is shield Arduino, unfortunately... )
* Module at board BC66NA... is obsolete, will replase BC66NB... and firmvare for NB
* Firmware: waithing for new version
* API: OpenCPU, native C, EAT (Embedded AT) oriented (70 function), static lib
* My Extended API, native C/C++, more than 300 function, static lib
* User Application Size: ROM (BIN) 200k, RAM 100k


![ScreenShot](https://raw.githubusercontent.com/Wiz-IO/Arduino_MT2625_BC66/master/board.jpg)

**Tools**
* Arduino IDE:
https://www.arduino.cc/
* GCC Linaro - last version
https://releases.linaro.org/components/toolchain/gcc-linaro/latest/
* Firmware / Application Uploader: Quectel IoT Flash Tool


**Arduino Port** (in progress, GCC+Eclipse IDE)
 * Standart C/C++ Core
 * Multitasking
 * Periphery: 
    * GPIO: 17 pins
    * ADC: 1
    * PWM: 1    
    * UART: 3
    * SPI: 1
    * I2C: 1
    * USB
* Libraries:
   * Peripheries 
   * RIL, AT commands
   * EEPROM
   * TCP Clent Socket
   * SSL/TLS Client
   * HTTP/S Client
   * MQTT CLient
   * CoAP (feature)
   * LWM2M (feature)
   * Other...
  
  

**PC Operating system:** 
Windows, Linux... whatever you choose... Arduino IDE + GCC

![ScreenShot](https://raw.githubusercontent.com/Wiz-IO/Arduino_MT2625_BC66/master/Arduino.jpg)

It`s working...
 * Core [ready]
 * HardwareSerial [ready]
 * GPIO [ready]
 * API [in progress]
    * STDLIB
    * FreeRTOS
    * lwip, ssl, http, mqtt
    * RIL
    * Other...

**If you want to help / support - contact me**

# Comming soon...
