# Vignesh Sriram — Embedded Software Developer

MSc Embedded Systems @ Universität des Saarlandes  
Building real-time embedded systems in C on STM32 and ESP32 — Zephyr RTOS, BLE, and CI/CD.

---

## What I work on

**Research Assistant @ ZeMA GmbH** *(Mar 2024 – Present)*

- TCP/IP control of a laser projection system handling real-time positional and process data across system components
- Low-level driver development for sensors and actuators over UART, SPI, I²C; system validation under real-time conditions
- Multithreaded vision pipelines and stereo camera calibration tools for industrial assembly workstations
- Interface layer integrating a .NET/C# API into a Python application for torque tool data acquisition and validation

**M.Sc. Thesis** — Gripping area optimisation with in-process hand detection; real-time camera-based system for industrial assembly with CLAHE preprocessing under laser projection interference.

---

## Skills

| Area | Details |
|---|---|
| **Languages** | C (primary), Python, C++ |
| **Microcontrollers** | STM32 (ARM Cortex-M), ESP32 |
| **Interfaces** | UART, SPI, I²C, ADC, PWM, GPIO, TCP/IP |
| **RTOS** | Zephyr RTOS (Devicetree, Kconfig, drivers), FreeRTOS |
| **Wireless** | BLE — GATT service design, SMP pairing, NVS bonding |
| **Security** | mbedTLS, HMAC-SHA-256, NVS secure storage, flash partitioning |
| **Toolchain** | Git, GitHub Actions, CMake, GCC, ST-Link, OpenOCD |

---

## Featured Projects

### [WiFi Radar System](https://github.com/Vignesh-Sriram7/Zephyr/tree/main/Wifi_Radar)
Real-time radar on ESP32 — HC-SR04 ultrasonic sensor + servo sweep, distance data streamed live to a web interface over WiFi.  
`ESP32` `C` `Zephyr RTOS` `HC-SR04` `Servo` `Web Server` `HTML/CSS/JS`

<p align="center"><img src="Screenshot 2026-02-15 223704.png" width="300"></p>

---

### [BLE Smart Lock](https://github.com/Vignesh-Sriram7/Zephyr/tree/main/Smart_Access_Control)
Bluetooth-controlled locking system with custom GATT service, SMP encrypted pairing, persistent NVS bonding, and servo actuation via PWM. Accessible from a paired mobile device or browser-based BLE-to-HTTP bridge — no native app required.  
`ESP32` `Zephyr RTOS` `BLE` `GATT` `SMP` `NVS` `PWM`

<p align="center"><img src="Screenshot 2026-02-24 132501.png" width="800"></p>

---

### [BLE Beacon + CI Pipeline](https://github.com/Vignesh-Sriram7/Zephyr/tree/main/BLE_Beacon)
Periodic BLE beacon with Kalman filter RSSI smoothing for stable proximity estimation from noisy raw RSSI. Authenticated IAS alerts via Zephyr GATT stack. Full GitHub Actions CI pipeline — automated build, static analysis, reproducible flashable binary artifact. [Documented end-to-end on Medium.](https://medium.com/@vigneshsriram2603/esp32-devops-ci-cd-with-zephyr-rtos-36dd35c2b3e6)  
`ESP32` `Zephyr RTOS` `BLE` `Kalman Filter` `GitHub Actions` `CI/CD`

<p align="center"><img src="Screenshot 2026-04-08 223643.png" width="800"></p>

---

### [STM32 Secure Telemetry Logger](https://github.com/Vignesh-Sriram7/Zephyr/tree/main/STM32_Secure_Telemetry_Logger)
Sensor readings acquired, encrypted with mbedTLS before leaving RAM, and stored in a dedicated flash partition alongside random sequence IDs for tamper detection. NVS handles persistent metadata across power cycles. Custom partition table cleanly separates telemetry from firmware.  
`STM32` `Zephyr RTOS` `mbedTLS` `HMAC-SHA-256` `NVS` `I²C` `UART`

---

### [STM32 Weather Station](https://github.com/Vignesh-Sriram7/Hackathon_2025/tree/main/weather_station)
Cooperative task scheduler driving simulated multi-sensor weather data, JSON-formatted and transmitted over UART. Built at a Smart Agricultural Systems hackathon.  
`STM32` `C` `HAL` `UART` `Cooperative Scheduling`

---

### [Message Authenticator](https://github.com/Vignesh-Sriram7/Message-Authenticator)
HMAC-SHA-256 authentication on bare-metal ARM Cortex-M — ESP32 sends, STM32F303RE authenticates over UART3.  
`STM32` `ESP32` `C` `HMAC-SHA-256` `HAL` `ESP-IDF`

---

### [IoT Pill Dispenser](https://github.com/Vignesh-Sriram7/Medicine_Dispenser)
ESP8266 + NFC + Slack API — medication tracking and dispensing system for elderly users.  
`ESP8266` `C` `NFC` `Slack API`

---

## Contact

[vigneshs2603@gmail.com](mailto:vigneshs2603@gmail.com) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/vignesh-s2603) &nbsp;|&nbsp; [Medium](https://medium.com/@vigneshsriram2603)
