# Embedded Hardware & Firmware Portfolio

**Phung Huu Gia Hung**  
Junior Embedded Engineer | STM32 | TI C2000 | PCB Design | Hardware Bring-Up | Power Electronics

This repository presents selected embedded hardware and firmware projects, with a focus on schematic design, multi-layer PCB development, MCU firmware, hardware bring-up, and laboratory validation.

**Full PDF portfolio:** [Phung_Huu_Gia_Hung_Embedded_Hardware_Portfolio.pdf](docs/Phung_Huu_Gia_Hung_Embedded_Hardware_Portfolio.pdf)

---

## 1. Three-Phase IGBT Inverter for Voltage Sag Compensation

**Platform:** TI C2000 F28379D | Altium Designer | Three-Phase IGBT Inverter

- Designed and brought up a **1200 V / 75 A IGBT inverter** with DC-link/precharge, isolated gate drivers, sensing circuits, auxiliary supplies, and LCL filtering.
- Designed a **multi-layer PCB** with power/signal partitioning, ground/power planes, decoupling, pin mapping, and ADC signal conditioning.
- Developed **F28379D firmware** for ADC-based voltage/current feedback, 16 kHz SVPWM, dual-loop d-q control, PLL synchronization, and FSM-based operation.
- Performed **48 VDC hardware validation**, including gate-drive verification, deadtime checks, and balanced three-phase 50 Hz output testing.

### Hardware

| PCB Layout | Fabricated Inverter Board |
| --- | --- |
| ![Inverter PCB Top](assets/inverter-pcb-top.jpg) | ![Inverter Real Board](assets/inverter-real-board.jpg) |

| Gate Driver Circuit | Laboratory Test Setup |
| --- | --- |
| ![Inverter Gate Driver](assets/inverter-gate-driver.jpg) | ![Inverter Test Setup](assets/inverter-test-setup.jpg) |

Additional PCB views: [GND plane](assets/inverter-pcb-gnd.jpg) · [3D top view](assets/inverter-3d-top.jpg)

---

## 2. SPI Master-Slave Closed-Loop Boost Converter

**Platform:** STM32F103C8T6 | Embedded C | SPI | ADC | PWM | PID Control

- Developed register-level STM32 firmware using **ADC feedback, 20 kHz PWM, PID control, interrupts, and SPI Master-Slave communication**.
- Selected power components and developed the prototype from **breadboard to soldered PCB**, validating PWM, gate-driver, MOSFET switching, ADC feedback, and SPI communication.

| PCB Layout | Hardware Prototype |
| --- | --- |
| ![Boost PCB](assets/boost-pcb.jpg) | ![Boost Real Board](assets/boost-real-board.jpg) |

---

## Additional Embedded Projects

### Multi-Node Attendance System Using CAN & Local Storage
- STM32F103C8T6 register-level firmware using **CAN, SPI, I2C, and USART**.
- Integrated **RFID RC522, LCD1602, MicroSD storage, and MCP2551 CAN transceivers** for multi-node identification and local data storage.

### IoT System for Power Quality Monitoring
- Developed an STM32-based monitoring board with **RS485, LoRaWAN, SD logging, and isolated I/O**.
- Led the team to **First Prize (Top 1/186 teams)** at VietFuture National Innovation and Startup Competition 2024.

---

## Technical Skills

**Embedded:** C, STM32F103C8T6, TI C2000 F28379D, CAN, UART/USART, SPI, I2C, RS485, GPIO, ADC, PWM, Timers, Interrupts  
**Hardware & PCB:** Schematic/PCB Design, Component Selection, Analog/Digital & Sensing Circuits, Gate Drivers, 2–4 Layer PCB, Power/Signal Routing, Ground/Power Planes, Decoupling, Signal Integrity, DFT/DFA  
**Tools & Lab:** Altium, KiCad, Code Composer Studio, STM32CubeIDE, Keil MDK, LTspice, SIMPLIS, Proteus, Git/GitHub, Oscilloscope, DMM, Logic Analyzer, DC Power Supply, Soldering/Rework

---

## Publication

**Phung, H. G.**, *et al.*, “Application of a Dual Active Bridge Converter in Charging and Discharging Supercapacitors Using the Closed-Loop Triple Phase Shift Algorithm,” **IEEE, 2026**.  
[IEEE Xplore](https://ieeexplore.ieee.org/document/11628104)

---

## About This Repository

This repository is intended as a concise visual engineering portfolio. It contains selected project images and a full PDF portfolio; source code and complete design files are not included in this public version.
