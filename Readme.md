# Kareem Taha — Electrical Engineering Portfolio

**Electrical Engineering Graduate — Birzeit University**
IC / VLSI Design · Embedded Systems & IoT Hardware · PCB Design · Power Distribution & Building Automation

📍 Ramallah, Palestine · 📧 karimbtaha6@gmail.com · [LinkedIn](#) · [GitHub](https://github.com/karimtaha007)

---

## About Me

I'm an Electrical Engineering graduate from Birzeit University with a hands-on, full-stack view of hardware — from the transistor up to the finished, wired system. My work spans four areas that I'm actively building a career across:

- **Analog & Mixed-Signal / Digital IC Design (VLSI)** — transistor-level circuit design, physical layout, and verification
- **Embedded Systems & IoT Hardware** — microcontroller firmware, sensor integration, wireless communication
- **PCB Design** — schematic capture, layout, and design-rule verification for real, manufactured boards
- **Power Distribution & Building Automation** — panel design, three-phase wiring, protection coordination, and KNX systems

This repository brings together my academic, training, and independent projects across all four areas.

---

## 🧠 Technical Interests

| Domain | Focus |
|---|---|
| **VLSI / IC Design** | Physical design, digital & analog/mixed-signal circuits, design verification (DRC/LVS) |
| **Embedded Systems** | ESP32/ESP32-S3 firmware, sensor fusion, real-time positioning (GNSS/UWB), BLE |
| **PCB Design** | Schematic capture & layout in EasyEDA/KiCad, power regulation, USB-C & USB-UART interfacing |
| **Power Systems** | Load calculation, cable/breaker sizing, protection & relay coordination, load-flow/fault analysis (ETAP, PowerWorld) |
| **Building Automation** | KNX (ETS6) topology, addressing, switching & dimming control |
| **Industrial Control** | PLC programming (Siemens LOGO!, Delta), ladder logic, I/O configuration |

---

## 📂 Featured Projects

| Project | Area | Description |
|---|---|---|
| [PaldiBlind](#-paldiblind--indooroutdoor-navigation-for-the-visually-impaired) | Embedded Systems / PCB | Assistive navigation device integrating ESP32-S3, GNSS, UWB, and IMU for indoor/outdoor positioning |
| [Custom ESP32-WROOM-32 Dev Board](./ESP32%20DEV%20BOARD) | PCB Design | Full schematic-to-layout design of a custom ESP32 development board |
| [SRAM PUF Array Design](./SRAM%20PUF%20ARRAY%20DESIGN) | VLSI / IC Design | 4×4 SRAM-based Physical Unclonable Function — physical layout, DRC/LVS, area & power analysis |
| [Multiplier Design](./MULTIPLIER%20DESIGN) | Digital Design / VLSI | 4-bit × n-bit multiplier (RCA vs. CLA) in Verilog with timing analysis |
| [Microcomputer Architecture Design](./MICROCOMPUTER%20ARCHITECTURE%20DESIGN) | Computer Architecture | Integrated processing, memory, control, and peripheral design |
| [uWave Semiconductor Training](./uWave) | Analog & Mixed-Signal IC Design | Transistor-level amplifier design and simulation (Synopsys Custom Compiler) |
| [Melemco Control & KNX Panels](./Melemco%20Co) | Power & Building Automation | 400 A three-phase distribution board wiring, KNX panel integration |
| [Power System Protection & Relay Coordination](./ETAP) | Power Systems | Relay/fuse/recloser coordination on a 5-bus radial network in ETAP |
| [Power System Analysis](./PowerWorld) | Power Systems | Load-flow, Y-bus modeling, and fault analysis in PowerWorld Simulator |

---

## 🦯 PaldiBlind — Indoor/Outdoor Navigation for the Visually Impaired

**Graduation Project** — a complete assistive navigation device, designed end-to-end: custom PCB, embedded firmware, sensor integration, and a 3D-printed enclosure.

PaldiBlind combines GNSS outdoor positioning with UWB indoor positioning on an ESP32-S3 platform to give visually impaired users reliable, continuous navigation guidance as they move between outdoor and indoor spaces.

<table>
<tr>
<td width="50%">
<img src="./assets/paldiblind_pcb.jpg" alt="PaldiBlind custom PCB - ESP32-S3, GPS, and IMU modules" width="100%"/>
<p align="center"><sub>Custom PCB — ESP32-S3, GPS, and IMU integration</sub></p>
</td>
<td width="50%">
<img src="./assets/paldiblind_device.jpg" alt="PaldiBlind assembled navigation device in 3D-printed enclosure" width="100%"/>
<p align="center"><sub>Assembled device — 3D-printed enclosure</sub></p>
</td>
</tr>
</table>

**Key Contributions**
- Designed the custom PCB from schematic to layout, integrating the ESP32-S3, GPS/GNSS module, and IMU on a single board
- Implemented GNSS-based outdoor positioning and UWB-based indoor positioning
- Developed embedded firmware for sensor fusion and system operation
- Designed and 3D-printed the enclosure for the final field-ready prototype
- Performed full system integration, calibration, and testing

**Technologies:** `ESP32-S3` `GNSS` `UWB` `IMU` `BLE` `Embedded C/C++` `PCB Design` `3D Printing`

[View project on GitHub →](https://github.com/karimtaha007)

---

## ⚡ Melemco Control & KNX Distribution Panels

Practical training in low-voltage power distribution and building automation at Melemco Electrical Co.

**Key Contributions**
- Completed load calculations, cable sizing, and breaker sizing for a 400 A three-phase distribution board
- Assisted with panel design, component installation, and power/control wiring
- Gained hands-on exposure to KNX panels — device installation, wiring, and ETS6-based configuration
- Read and verified single-line diagrams against installed panel wiring

**Technologies:** `Three-Phase Distribution` `Circuit Breaker & Cable Sizing` `KNX / ETS6` `Single-Line Diagrams` `PLC Basics`

---

## 🔌 Custom ESP32-WROOM-32 Development Board

A ground-up PCB design project: schematic capture through layout for a fully functional ESP32-WROOM-32 development board.

**Key Contributions**
- Designed power regulation, USB-to-UART, and USB-C connectivity circuitry
- Selected components and footprints based on manufacturer reference designs and datasheets
- Completed component placement, routing, and design-rule checking (DRC)

**Technologies:** `EasyEDA` `ESP32-WROOM-32` `Power Regulation` `USB-C` `DRC`

---

## 🔬 SRAM PUF Array Design

Digital IC/VLSI project exploring SRAM-based Physical Unclonable Functions for hardware security applications.

**Key Contributions**
- Designed the physical layout of a 4×4 SRAM-based PUF array — floor planning, symmetric transistor placement, VDD/GND routing
- Performed DRC and LVS verification to confirm layout–schematic consistency
- Evaluated area efficiency and power consumption of the final layout

**Technologies:** `CMOS` `SRAM` `PUF` `Electric VLSI` `LTspice` `DRC/LVS`

---

## ⚙️ Multiplier Design

Advanced digital design project comparing multiplier architectures for speed and area trade-offs.

**Key Contributions**
- Designed and verified a 4-bit × n-bit multiplier in Verilog using Ripple Carry Adder (RCA) and Carry Look-Ahead Adder (CLA) architectures
- Built testbenches and ran functional simulation in Active-HDL
- Analyzed propagation delay and critical paths to compare RCA vs. CLA timing performance

**Technologies:** `Verilog` `Active-HDL` `Digital Arithmetic` `Timing Analysis`

---

## 🖥️ Microcomputer Architecture Design

System-level digital design project integrating the core building blocks of a computer system.

**Key Contributions**
- Designed the overall microcomputer architecture, integrating processing, memory, and control units
- Developed and verified digital logic blocks and data-flow/control-signal paths
- Validated system operation through simulation

**Technologies:** `Computer Architecture` `Digital Logic` `Memory & Control Design` `Simulation`

---

## 🔬 Analog & Mixed-Signal IC Design — uWave Semiconductor Training

Transistor-level circuit design and simulation training in analog and mixed-signal IC design.

**Key Contributions**
- Designed and analyzed common-source and common-drain amplifier stages and a differential amplifier at the transistor level
- Performed DC operating-point, transient, AC, and frequency-response analyses using Synopsys Custom Compiler
- Evaluated biasing, voltage gain, and operating regions across circuit variants

**Technologies:** `Synopsys Custom Compiler` `CMOS` `Analog IC Design` `Mixed-Signal Design`

---

## 🔩 Power System Protection & Relay Coordination (ETAP)

**Key Contributions**
- Modeled a 5-bus radial distribution network and analyzed voltage profiles, power losses, and fault-current levels
- Calculated CT ratios and overcurrent relay pickup/time-dial settings using CO-8 inverse-time coordination
- Designed a coordinated primary/backup protection scheme with breakers, fuses, and reclosers, validated through TCC analysis

**Technologies:** `ETAP` `Relay Coordination` `Fault Analysis` `TCC Curves`

---

## 📉 Power System Analysis (PowerWorld Simulator)

**Key Contributions**
- Modeled a transmission and distribution network, deriving per-unit parameters and the Y-bus matrix
- Evaluated transformer loading limits, voltage stability, and system losses
- Applied shunt capacitor compensation and performed three-phase fault analysis for protection design

**Technologies:** `PowerWorld Simulator` `Load Flow` `Y-Bus Modeling` `Fault Analysis`

---

## 🛠️ Engineering Tools

| Category | Tools |
|---|---|
| **IC & VLSI Design** | Synopsys Custom Compiler, Electric VLSI, LTspice, OrCAD PSpice |
| **Digital Design** | Active-HDL, Quartus |
| **Embedded Systems & PCB** | ESP32, Arduino IDE, EasyEDA, KiCad, Proteus |
| **Power Systems** | ETAP, PowerWorld Simulator, AutoCAD, ETS6 |
| **Simulation & Analysis** | MATLAB/Simulink, Cisco Packet Tracer, ArcGIS |

---

## 📫 Contact

Open to graduate engineering opportunities, internships, and collaborations in semiconductor design, VLSI, embedded systems, PCB design, and power/building-automation engineering.

- **Email:** karimbtaha6@gmail.com
- **GitHub:** [karimtaha007](https://github.com/karimtaha007)

---

<p align="center"><sub>This repository is maintained as a living engineering portfolio — updated as new hardware, IC design, PCB, and embedded-systems projects are completed.</sub></p>
