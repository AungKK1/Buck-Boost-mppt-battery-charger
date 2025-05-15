# Buck-Boost Battery Charger with MPPT

A multi-chemistry buck-boost battery charger PCB with Maximum Power Point Tracking (MPPT), optimized for renewable energy sources such as solar panels. Designed using OrCAD to explore high-current PCB layout, thermal management, and power integrity.

---

## 🧠 Objective

To develop a power-efficient, flexible battery charger with MPPT capabilities for solar energy systems. This design project focuses on power stage layout, EMI control, and thermal considerations in switching converters.

---

## ⚙️ Core Components

- **LT8490** – Buck-boost battery charging controller with MPPT
- Power **MOSFETs** for switching control
- High-current **filter capacitors** and **sense resistors**

---

## 🔋 Battery & Power Management

- **Input Voltage Range:** 6V–80V
- **Output Voltage Range:** 1.3V–80V
- **Output Current:** Up to 20A
- Supports **Li-Ion**, **LiFePO4**, and **Lead Acid** batteries
- Programmable charge voltage, current, and float regulation
- Input/output current limiting and overvoltage protection

---

## 🔌 Interfaces

- **I²C** for charge control and monitoring
- Status **indicator LEDs**
- **MPPT enable/disable** switch

---

## 🚧 Design Highlights

- **MPPT implementation** with real-time solar tracking
- 4-layer PCB designed for **thermal distribution and power flow**
- **High-current trace optimization**
- **Thermal relief** and **heat sink via stitching**
- **EMI/EMC** mitigation strategies
- Simulation for **power integrity** and **heat dissipation**
- Designed with **DFM/DFT** considerations in mind

---

## 📎 Files

- [`/docs`](./docs): Schematic, PCB layout images
- [`/gerbers`](./gerbers): Fabrication files for PCB manufacturing
- [`/odb++`](./odb++): Optional manufacturing format
- [`/bom`](./bom): Bill of materials with key parts and specs

---

## 👨‍🏫 Acknowledgments

Guided by **Kirsch Mackey** as part of the Hasofu Academy Elite Hardware Engineering Accelerator. Built with reference to Linear Technology application notes and open-source documentation.

---

## 🚫 Disclaimer

This board has not been manufactured or tested. For educational demonstration purposes only.
