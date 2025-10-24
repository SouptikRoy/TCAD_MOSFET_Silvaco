# TCAD Silvaco MOSFET Simulation

This repository documents the process and scripts for simulating MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) structures using the TCAD Silvaco software suite, including ATHENA (process simulation), ATLAS (device simulation), and visualization with TonyPlot.

## Table of Contents

- Overview
- Features
- Requirements
- Directory Structure
- Getting Started
- Example Workflow
- Output Interpretation
- Screenshots
- Contributing
- License

---

## Overview

This project provides a step-by-step guide and example input files for simulating silicon MOSFET devices. The workflow covers process simulation, device simulation, and graphical analysis of doping and material profiles.

## Features

- MOSFET process simulation (ATHENA)
- Device electrical simulation (ATLAS)
- Visualization with TonyPlot
- Layer and doping profile analysis
- Example screenshots of output plots

## Requirements

- **Silvaco TCAD Suite** (ATHENA, ATLAS, TonyPlot)
- A licensed installation of Silvaco software (not included)
- Windows or Linux environment (tested on Windows 10)
- Example `.inp` and `.str` files from this repository

## Directory Structure



## Getting Started

Clone the repository or download the ZIP, then ensure Silvaco is installed and licensed on your machine.

1. Place your `.inp` scripts into `/scripts`.
2. Make sure `mosfet_process.inp` and `mosfet_device.inp` match your simulation needs.

## Example Workflow

### 1. Process Simulation (ATHENA)

Simulate the MOSFET fabrication using ATHENA:


Output: ATHENA will generate a structure file (e.g., `mosfet.str`).

### 2. Device Simulation (ATLAS)

Run the electrical simulation using ATLAS:


Output: Device simulation results (IV curves, etc.).

### 3. Visualization (TonyPlot)

Display output structure and doping profiles with TonyPlot:

- Use menu options to visualize net doping, active dopants, or mesh.
- Adjust color scales and perspectives as needed for clarity.

## Output Interpretation

- **Abs Net Doping (3D/2D):** Shows spatial doping concentrations in units of cm⁻³.
- **Active Boron:** Displays active dopant distribution (for p-type doping).
- **Layer Colors:** Refer to the legend—blue (Silicon), yellow (SiO₂), black (Polysilicon), pink (Aluminum).

## Screenshots

Below are some typical results you will observe. See `/results` for full-resolution images.

| Visualization           | Description                                  |
|-------------------------|----------------------------------------------|
| Abs Net Doping (3D)     | 3D surface map of doping profile             |
| Abs Net Doping (2D)     | Contour plot showing net doping cross-section|
| Active Boron (2D)       | Layered plot of boron distribution           |

(Example TonyPlot screenshots are provided in this repository.)

![Simulation](Screenshot(272).png)
![Simulation](Screenshot(273).png)
![Simulation](Screenshot(274).png)
![Simulation](Screenshot(275).png)
![Simulation](Screenshot(276).png)
![Simulation](Screenshot(277).png)
![Simulation](Screenshot(278).png)
![Simulation](Screenshot(279).png)
![Simulation](Screenshot(280).png)
![Simulation](Screenshot(281).png)
![Simulation](Screenshot(282).png)
![Simulation](Screenshot(283).png)
![Simulation](Screenshot(284).png)
![Simulation](Screenshot(286).png)
![Simulation](Screenshot(287).png)
![Simulation](Screenshot(288).png)

## Contributing

- Issues and pull requests for new device structures, improved scripts, or documentation updates are welcome.
- Please document any changes and follow the directory structure.

## License

This repository is for academic and research use only. All sample scripts presume the user has access to properly licensed Silvaco TCAD software. No proprietary code is distributed.

---

**Note:** For details on each step, script comments, and best practices, refer to example `.inp` files and the official Silvaco manuals.



