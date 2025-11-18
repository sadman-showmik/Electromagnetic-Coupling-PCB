# Electromagnetic Coupling Analysis & Signal Observation PCB

This repository contains the schematic and PCB layout for a project focused on **measuring and analyzing square-wave generation via coil coupling**, with applications in wireless charging experiments. The board is designed for testing, signal observation, and component-level experimentation in electromagnetic systems.

---

## 🔧 Features

- Square-wave signal generation using NE555 timer
- Electromagnetic coupling via paired coils
- Full component-level analysis and observation points
- Supports signal measurement with test points
- Robust through-hole components for easy prototyping

---

## 📁 Repository Contents

- KiCAD schematic and PCB layout files
- Gerber manufacturing files
- BOM (component list)
- Datasheet references
- Optional test scripts for signal observation

---

## 📦 Component List (BOM)

| Reference | Value | Datasheet | Footprint | Qty |
|-----------|-------|-----------|-----------|-----|
| C1,C2,C3,C4,C5,C7,C9 | 0.1µF | ~ | Capacitor_THT:CP_Radial_Tantal_D6.0mm_P5.00mm | 7 |
| C6 | 470µF | ~ | Capacitor_THT:CP_Radial_Tantal_D7.0mm_P5.00mm | 1 |
| C8 | 0.33µF | ~ | Capacitor_THT:CP_Radial_Tantal_D7.0mm_P5.00mm | 1 |
| C10 | 10nF | ~ | Capacitor_THT:CP_Radial_Tantal_D6.0mm_P5.00mm | 1 |
| C11 | 1nF | ~ | Capacitor_THT:CP_Radial_Tantal_D6.0mm_P5.00mm | 1 |
| D1 | 1N5919BG | [Datasheet](https://www.onsemi.com/pub/Collateral/1N5913B-D.PDF) | 3D_Models:DIOAD1405W86L465D235 | 1 |
| D2,D3,D4,D5 | 1N4148 | [Datasheet](https://www.onsemi.com/pub/Collateral/1N914-D.PDF) | 3D_Models:DIOAD1068W53L380D172 | 4 |
| IC1 | IR2302SPBF | [Infineon](https://www.infineon.com/cms/en/product/power/gate-driver-ics/?) | 3D_Models:SOIC127P600X175-8N | 1 |
| IC2 | LM7805CT | [Datasheet](http://www.ti.com/lit/ds/symlink/lm340.pdf) | 3D_Models:TO254P470X1028X1955-3P | 1 |
| J1,J2,J3,J4,J5 | 282843-2 | [TE Connectivity](https://www.te.com/commerce/DocumentDelivery/DDEController?Action=srchrtrv&DocNm=1-1773458-1_EURO_STYLE_QRG&DocType=Data%20Sheet&DocLang=English&PartCntxt=282843-2&DocFormat=pdf) | 3D_Models:SHDR2W130P0X1016_1X2_1524X900X1550P | 5 |
| Q1,Q2 | IRFZ44NPBF | [Datasheet](https://www.infineon.com/dgdl/irfz44npbf.pdf?fileId=5546d462533600a40153563b3a9f220d) | 3D_Models:TO254P483X1016X1994-3P | 2 |
| R1 | 1kΩ | ~ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1 |
| R2 | 100Ω | ~ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1 |
| R3 | 10Ω | ~ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1 |
| R4 | 9.09kΩ | ~ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1 |
| S1 | EG1218 | [Datasheet](https://configured-product-images.s3.amazonaws.com/2D/specs/EG1218.pdf) | 3D_Models:EG1218 | 1 |
| U1 | NE555P | [Datasheet](http://www.ti.com/lit/ds/symlink/ne555.pdf) | Package_DIP:DIP-8_W7.62mm | 1 |

---

## 🚀 Getting Started

1. Open the `.kicad_sch` and `.kicad_pcb` files in KiCAD.
2. Review PCB layers, components, and coil connections.
3. Export Gerber files using the KiCAD Plot tool.
4. Assemble the PCB using the listed components.
5. Use an oscilloscope or logic analyzer to observe square-wave signals via coil coupling.
6. Optionally, experiment with wireless charging via inductive coupling using the test setup.

---

## 👤 Author

**B M Sadman Showmik**  
Email: sadman.showmik@metropolia.fi

---

