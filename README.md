# 🔧 CNC Laser Engraver Project

> Built by **Siumal Virajith** & **Shalinda Asanka**  
> 40W LaserTree | GRBL Firmware | LightBurn Software | Custom Aluminum Frame

---

## 📌 Overview

This project is a fully custom-built **CNC laser engraving machine**, developed as a personal engineering project. It uses open-source technologies to achieve high-precision engraving and cutting on various materials like wood, acrylic, leather, and cardboard.

---

## 🧰 Technologies Used

- **Hardware:**
  - 40W **LaserTree Diode Laser**
  - **Stepper Motors (NEMA 17)**
  - **V-Slot Aluminum Extrusion Frame**
  - GT2 Timing Belts & V-Wheels

- **Electronics & Firmware:**
  - **Arduino UNO** running **GRBL Firmware**
  - A4988 Stepper Motor Drivers

- **Software:**
  - **LightBurn** for laser control and design
  - **SolidWorks** for mechanical CAD design

---

## 📁 Folder Structure

```bash
CNC-Laser-Engraver/
├── cad/         # SolidWorks and STEP files of the frame and parts
├── firmware/    # GRBL configuration and parameters
├── images/      # Rendered models and real machine photos
├── lightburn/   # LightBurn design files (.lbrn, .lbrn2)
├── printjobs/   # Exported G-code or test print job files
└── README.md    # Project description and setup instructions
