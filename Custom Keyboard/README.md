# ⌨️ Custom Mechanical Keyboard: 3D Model & Hardware

This repository features the complete design of a custom mechanical keyboard, integrating a high-fidelity **3D model** for the enclosure and a professional **PCB** layout developed in **KiCad**.

---

## 📂 Project Overview

The project combines mechanical ergonomics with robust electronic engineering. It is designed as a compact input device featuring a tactile rotary encoder and an OLED status display, all controlled by the powerful RP2040 architecture.

---

## 🛠️ Bill of Materials (BOM)

The electronics are centered around the **Seeed XIAO RP2040**, utilizing a diode-protected matrix to ensure high performance and zero ghosting.

| Qty | Component | Technical Specification | Reference |
| :---: | :--- | :--- | :--- |
| **x9** | **Keyswitches** | SW_Cherry_MX_1.00u_PCB | Mechanical Switches |
| **x10** | **Diodes** | Diode_DO-35 | Switching Matrix |
| **x1** | **OLED Display** | 128x32 I2C | System Status (J1) |
| **x1** | **Rotary Encoder** | Alps EC11E (Vertical H20mm) | Input Control (SW1) |
| **x1** | **MCU** | **Seeed XIAO RP2040** | Controller (U1) |

---

## 📐 Design Details

### 🔌 Electronic Design (KiCad)
* **Microcontroller:** Powered by the **Dual-core Arm Cortex M0+** (RP2040).
* **Matrix Logic:** Includes 10 signaling diodes to handle the 9-key grid efficiently.
* **Peripheral Support:** Dedicated I2C headers for the OLED module and GPIO mapping for the rotary encoder switch.

### 📦 3D Modeling
* **Enclosure:** Custom-designed chassis to house the PCB securely.
* **Compatibility:** Precise mounting holes for Cherry MX style switches and vertical encoder clearance.



---
*Designed by [mmaxirod8](https://github.com/mmaxirod8)*
