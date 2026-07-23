<div align="center">
  <h1>Effect of FDM Parameters on TPU</h1>
  <p><i>Analyzing the impact of FDM 3D printing parameters on the thermal and material properties of Thermoplastic Polyurethane (TPU).</i></p>
</div>

<hr />

## At a Glance

This repository contains experimental data and analysis investigating how variations in Fused Deposition Modeling (FDM) parameters affect the material properties of TPU. The findings are evaluated using thermal characterization techniques and compared against standard PLA baselines.

| Parameters Evaluated | Characterization Methods | Baselines |
| :--- | :--- | :--- |
| Infill Density | Differential Scanning Calorimetry (DSC) | Standard PLA |
| Print Speed | Thermogravimetric Analysis (TGA) | |
| Nozzle Temperature | | |
| Bed Temperature | | |

<hr />

## Repository Structure

The project structure is organized to separate literature, baseline references, and experimental datasets for clarity.

```text
Effect-of-FDM-parameters-on-TPU/
├── Literature/
│   └── Research papers and references
├── PLA_Baselines/
│   └── Baseline property analysis for PLA
└── TPU_Experimental_Data/
    ├── DSC_and_TGA/
    │   └── Contains .tif micrographs and .txt raw data for variations
    └── Mass_Data/
        └── Sample mass datasets
```

<hr />

## Data Guide

The experimental dataset is structured to facilitate straightforward analysis and comparison of thermal properties. 

The `TPU_Experimental_Data/DSC_and_TGA/` directory contains individual subfolders for each FDM parameter tested (Infill Density, Print Speed, Nozzle Temperature, and Bed Temperature). Within each parameter subfolder, you will find variations categorized as **MIN**, **MID**, and **MAX**. 

Each variation includes:
- **Raw Data (`.txt`)**: Exported thermal analysis data from the DSC and TGA equipment.
- **Micrographs (`.tif`)**: High-resolution imagery associated with the samples.

For comparison, baseline measurements on standard Polylactic Acid (PLA) prints are available in the `PLA_Baselines/` directory.
