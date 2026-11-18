# Hi, I'm Vo Ngoc Men 👋

I'm a fourth-year Computer Engineering student at **Ho Chi Minh City University of Technology and Education (HCMUTE)**, interested in **embedded software, microcontrollers, and the connection between hardware and software**.

I enjoy working with real boards: wiring a circuit, testing firmware, reading logs, and figuring out why something doesn't behave as expected. I'm still building my programming fundamentals, and I use this profile to document what I learn and build along the way.

**Current focus:** Embedded systems · C/C++ · STM32 · Algorithms

## Featured projects

### [ESP32 BLE Wireless Sensor Network with Failover](https://github.com/menvo-embedded/esp32-ble-wsn-failover)
An academic prototype using **three ESP32 boards** (Sensor, Relay, Gateway) to transmit data over BLE GATT. When the direct link fails (3 consecutive missed ACKs), the Sensor switches to the relay path and later retries the direct link.

- Tested the direct-link and failover scenarios on physical ESP32 boards.
- Worked on system behavior, testing, Serial-log analysis (RSSI, PDR, sequence numbers), and troubleshooting.
- **Technologies:** ESP32, BLE/GATT, C++, FreeRTOS, PlatformIO.
- [Source code, architecture, and test notes](https://github.com/menvo-embedded/esp32-ble-wsn-failover)

### [AES-128 Encryption Core on Zynq SoC](https://github.com/menvo-embedded/aes128-pipeline-zynq)
A **team coursework project (5 members)** exploring iterative and pipelined AES-128 hardware implementations, with AXI4-Lite integration on Zynq.

- Includes Verilog RTL, simulation testbenches, and verification reports.
- Pipelined core reaches **12.8 Gbps** steady-state throughput; timing met at **100 MHz**.
- **Technologies:** Verilog, Vivado, Zynq SoC, AXI4-Lite.
- [Design and verification documentation](https://github.com/menvo-embedded/aes128-pipeline-zynq)

### [Algorithms in C](https://github.com/menvo-embedded/algorithms)
My ongoing LeetCode practice as part of the **AK Foundation Embedded Training Program**. I keep my own C solutions and problem notes here to track my progress.

- [Week 1 solutions](https://github.com/menvo-embedded/algorithms/tree/main/week-1)
- [AK Foundation Embedded Training Program](https://github.com/the-ak-foundation/embedded-training-program)
- Earlier practice: [300 bài code thiếu nhi](https://github.com/menvo-embedded/300-bai-code-thieu-nhi) – my C++ solutions from 1st–2nd year.

## Technical skills & tools

- **Programming:** C/C++, Verilog; practicing problem-solving in C.
- **Embedded platforms:** ESP32, Raspberry Pi Pico 2 W, Zynq FPGA; currently learning STM32.
- **Communication:** UART, I2C, SPI, BLE, Wi-Fi, MQTT.
- **Tools:** Git/GitHub, VS Code, PlatformIO, Vivado.

## Currently learning

- STM32 and the AK event-driven framework through the AK Foundation training program.
- FreeRTOS concepts and embedded software architecture.
- Algorithms and data structures in C.
- Wireless sensor networks and IoT for my ongoing Project 2 using Raspberry Pi Pico 2 W.

## Find me online

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,arduino,raspberrypi,py,opencv,linux,git,github,vscode" />
</p>

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-learning-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5BA300?style=flat)
![Verilog](https://img.shields.io/badge/Verilog-Vivado-FF6600?style=flat)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat&logo=platformio&logoColor=white)
![BLE](https://img.shields.io/badge/BLE%20%7C%20MQTT%20%7C%20UART%20%7C%20I2C%20%7C%20SPI-555?style=flat)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-menvo--embedded-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/menvo-embedded)
[![Portfolio](https://img.shields.io/badge/Portfolio-menvo--embedded.github.io-222?style=flat&logo=githubpages)](https://menvo-embedded.github.io/)
[![Email](https://img.shields.io/badge/Email-menthcstk%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:menthcstk@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-menvox__-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/menvox_/)
