<p align="center">
  <b>English</b> | <a href="README.ru.md">Русский</a>
</p>

High-precision 3D CAD model of the Mitsubishi MGF0918A High-Power GaAs FET (L & S Band, 0.5W/4.5W class), modeled strictly according to the official manufacturer's datasheet dimensions.

> **Note:** Mounting holes were not modeled because their dimensions and exact locations are not specified in the official datasheet drawing.

### Tools Used
Autodesk Fusion

### Datasheet Drawing

<p align="center">
  <img src="images/drawing.png" alt="MGF0918A Outline Drawing">
</p>

### Visual Previews

| Top View | Bottom View |
| :---: | :---: |
| ![MGF0918A Top View](images/top.png) | ![MGF0918A Bottom View](images/bot.png) |

### File Inventory

* `MGF0918A.step`: Lossless, high-compatibility STEP format for PCB layout (KiCad, Altium, etc.) and mechanical CADs.
* `MGF0918A.f3d`: Native Autodesk Fusion project file with parametric sketches and timeline.
* `datasheet.pdf`: Official technical datasheet (Mitsubishi Electric, Dec 2014).
* `images/`: Directory containing PNG render previews and drawing.

### Component Specifications

* **Package:** SMD Hermetic (non-matched).
* **Dimensions:** Body 4.00 x 4.20 mm, thickness 1.05 mm.
* **Pinout:** (1) Gate, (2) Drain, (3) Source (Backside Pattern).
