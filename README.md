# STM32 LWB+ / LWB5+ Orion Integration on Nucleo-H723ZG

## TL;DR
Integrated **Ezurio LWB+ / LWB5+ Wi-Fi & Bluetooth modules** on  **STM32 Nucleo-H723ZG** using **STM32CubeIDE**, **Infineon AIROC expansion pack**, and **FreeRTOS**.  
Validated Wi-Fi, Bluetooth LE, and manufacturing test applications on real hardware.

---

## Documentation

📘 **Full step-by-step application note (public)**  
The complete configuration, build, flash, and test procedure (with screenshots)
is available here:

https://lairdcp.github.io/guides/lwbx-orion-nucleo-docs/1.0/Integrating%20LWB+%20and%20LWB5+%20Future%20Orion%20on%20Nucleo_H723ZG.html

A summarized step-by-step checklist is also provided in this repository:

- [docs/lwbx-orion-nucleo.md](docs/lwbx-orion-nucleo.md)

---

## Overview
This repository documents my hands-on experience integrating the  **LWB+ / LWB5+ Orion board** (Future Electronics) with the  
**STM32 Nucleo-H723ZG** platform.

The work covers STM32 software setup, third-party expansion pack configuration, application build and flash, and validation of Wi-Fi and Bluetooth functionality using provided demo and test applications.

The integration flow applies to **both [LWB+](https://www.ezurio.com/wireless-modules/wifi-modules-bluetooth/sterling-lwb-wifi-4-and-bluetooth-52-modules) and [LWB5+](https://www.ezurio.com/wireless-modules/wifi-modules-bluetooth/sterling-lwb5-plus-wifi-5-bluetooth-5-module)** modules.

---

## What This Project Demonstrates
- Integration of external **Wi-Fi / Bluetooth modules** on STM32 platforms
- Use of **Infineon AIROC Wi-Fi & Bluetooth STM32 Expansion Pack**
- STM32CubeMX configuration and code generation
- Application build and flash using **STM32CubeIDE**
- Validation of:
  - Wi-Fi connectivity and throughput (iperf)
  - Bluetooth LE applications (GATT services)
  - Manufacturing / RF test workflows
- Working with **FreeRTOS-based embedded applications**

---

## Platform & Tools

### Hardware
- STM32 Nucleo-H723ZG
- Ezurio LWB+ / LWB5+ Orion board (Future Electronics)

### Software
- STM32CubeMX  
- STM32CubeIDE  
- STM32CubeProgrammer  
- Infineon AIROC Wi-Fi-Bluetooth STM32 Expansion Pack  
- FreeRTOS  
- Teraterm, iperf, AIROC Bluetooth Connect App  

