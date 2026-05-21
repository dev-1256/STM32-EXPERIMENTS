# STM32 IoT Lab Experiments Repository

![STM32 Setup](images/oled_display.jpg)

## Project Overview

This repository contains a collection of STM32-based IoT laboratory experiments implemented using STM32CubeIDE and STM32CubeMX.

The project demonstrates embedded system development concepts including GPIO interfacing, USART communication, I2C and SPI sensor integration, OLED display interfacing, PWM motor control, telemetry frame generation, Wi-Fi communication, and BLE advertising.

All experiments were developed and tested on the STM32 Discovery Kit as part of IoT and embedded systems learning.

---

# Objectives

- Understand STM32 peripheral configuration
- Learn real-time sensor interfacing
- Implement serial communication protocols
- Develop embedded IoT applications
- Generate telemetry data frames
- Explore wireless communication technologies

---

# Hardware Used

- STM32 Discovery Kit
- HTS221 Temperature & Humidity Sensor
- LPS22HB Pressure Sensor
- LSM6DSL Accelerometer Sensor
- SSD1306 OLED Display
- Servo Motor
- Wi-Fi Module
- BLE Module
- USB UART Interface
- Connecting Wires

---

# Software Used

- STM32CubeIDE
- STM32CubeMX
- RealTerm Serial Terminal

---

# IoT Protocols and Interfaces Used

| Protocol / Interface | Purpose |
|---|---|
| GPIO | LED and Button Interfacing |
| USART | Serial Communication |
| I2C | Sensor and OLED Communication |
| SPI | Accelerometer Communication |
| PWM | Servo Motor Control |
| HTTP | Wi-Fi Data Transmission |
| BLE | Wireless Sensor Broadcasting |

---

# Repository Structure

```text
STM32-IoT-Lab-Experiments/
│
├── README.md
├── LICENSE
├── src/
├── docs/
├── images/
└── results/
```

---

# Lab Experiments

| Experiment No | Experiment Title |
|---|---|
| 01 | LED Blinking using GPIO |
| 02 | Push Button and LED Interfacing |
| 03 | USART Serial Communication |
| 04 | HTS221 Temperature and Humidity Sensor |
| 05 | LPS22HB Pressure Sensor |
| 06 | LSM6DSL Accelerometer using SPI |
| 07 | SSD1306 OLED Display Interfacing |
| 08 | PWM Servo Motor Control |
| 09 | Multi-Sensor Telemetry Frame |
| 10 | Wi-Fi HTTP Data Transmission |
| 11 | BLE Sensor Beacon |

---

# Hardware Setup

The STM32 Discovery board was interfaced with onboard and external peripherals using GPIO, USART, I2C, SPI, PWM, Wi-Fi, and BLE communication interfaces.

---

# Project Images

## OLED Display Output

![OLED Display](images/oled_display.jpg)

---

## Sensor Data Output

![Telemetry Output](images/telemetry_frame_output.png)

---

# Results

All experiments were successfully implemented and tested using STM32CubeIDE and RealTerm serial monitoring software.

The project demonstrates practical implementation of embedded IoT concepts including sensor acquisition, actuator control, telemetry generation, and wireless communication.

---

# Future Improvements

- Cloud dashboard integration
- MQTT communication support
- Real-time data visualization
- Edge AI implementation
- Mobile monitoring application

---

# Author

Dev Banerjee

---

# License

This project is licensed under the MIT License.