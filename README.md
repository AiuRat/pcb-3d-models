# 3D CAD Library for Electronic Components

High-accuracy 3D CAD models of electronic components modeled strictly from manufacturer datasheets.

## ECAD & MCAD Integration

All models in the `components` directory are optimized for direct import into ECAD suites for PCB design (**Altium Designer**, **KiCad**, **EasyEDA**) as well as mechanical CAD packages (**SolidWorks**, **Autodesk Inventor**, **KOMPAS-3D**).

## Software and Formats

Models are created using **Autodesk Fusion**. Each component folder contains:

* **STEP (`.step` / `.stp`)**: Universal, lossless 3D files for ECAD/MCAD import.
* **F3D (`.f3d`)**: Native Autodesk Fusion parametric source files.
* **PDF (`.pdf`)**: Official manufacturer datasheets for reference.
* **PNG (`.png`)**: High-resolution renders and outline drawing previews.

## License

Copyright (c) 2026 Airat Yalaletdinov

This source describes Open Hardware and is licensed under the CERN-OHL-P v2. 
You may redistribute and modify this source and make products using it under 
the terms of the CERN-OHL-P v2 (https://cern.ch/cern-ohl).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, 
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A 
PARTICULAR PURPOSE. Please see the CERN-OHL-P v2 for applicable conditions.
