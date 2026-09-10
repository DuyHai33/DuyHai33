## Nguyen Duy Hai

Final-year Electronics & Telecommunications Engineering student at Ho Chi Minh City University of Technology (HCMUT) — graduating January 2027.

I build firmware for resource-constrained hardware: bare-metal C on STM32 (Cortex-M4), ESP-IDF/Arduino on ESP32, and the protocol layer — I2C, SMBus, UART, MQTT, Matter — that gets a sensor reading off a board and into something a system can act on. Looking toward automotive embedded software, semiconductor, or embedded Linux roles, in Vietnam and Japan.

Currently deepening RTOS fundamentals and studying Japanese (JLPT N2).

---

### Projects

**[stm32-vitals-monitor](https://github.com/DuyHai33/stm32-vitals-monitor)**
Two-MCU vital-signs monitor. STM32F401 edge node runs the full PPG/SpO2 signal chain on bare metal (no RTOS); ESP32 gateway streams to ThingsBoard Cloud. 125 host-side tests against the real firmware source, documented failure analysis (100 Hz lighting aliasing, subharmonic HR lock at high heart rate).

**[matter-smart-home](https://github.com/DuyHai33/matter-smart-home)**
ESP32-C6 Matter end device commissioned into 5 independent fabrics at once (Home Assistant + 4 chip-tool controllers). Measured commissioning time, invoke latency, Wi-Fi range, and where the fabric limit actually breaks.

**[esp32-digital-clock](https://github.com/DuyHai33/esp32-digital-clock)**
ESP32 IoT clock on a custom PCB — schematic and layout designed from scratch, hand-soldered. Non-blocking cooperative scheduler, MQTT telemetry, local web dashboard, OTA updates, Telegram alerts.

**[smart-farm-iot-monitor](https://github.com/DuyHai33/smart-farm-iot-monitor)**
Raspberry Pi irrigation system — soil/air sensing via ADS1115, automatic pump control with manual override, MQTT telemetry, Flask dashboard, ThingsBoard integration.

---

nguyenduyhaivt0303@gmail.com
