# A Numerical Model for Seagrass‑Herbivore Interactions and the Formation of Reef Halos

## Overview
This repository contains the code and data used to reproduce the figures in the manuscript **“A Numerical Model for Seagrass‑Herbivore Interactions and the Formation of Reef Halos”** by Eva Llabrés, Anne A. Innes‑Gold, Bartholomew DiFiore, Tomàs Sintes, and Elizabeth Madin.

## Folder Structure  
Download **`code_halo_model.zip`** and extract it. ​The resulting directory will contain a separate folder for each figure in the manuscript, complete with the model simulations, data and visualization scripts. 

## Numerical Simulations
The seagrass–herbivore interaction simulations are implemented in **Fortran 90** for computational efficiency.  
Compiled Fortran executables generate the simulation results, which are then processed and visualized with **Python** and **gnuplot**.

## Data Handling
Shapefile processing is performed in Python using the **`geopandas`** package before running the numerical simulations, ensuring proper spatial analysis and data preparation.

The field data in this repository were published previously (see References).

## References
- DiFiore B., Queenborough S., Madin E., Paul V., Decker M., & Stier A. (2019). *Grazing halos on coral reefs: predation risk, herbivore density, and habitat size influence grazing patterns that are visible from space.* **Marine Ecology Progress Series 627**, 71–81. <https://doi.org/10.3354/meps13074>  
- Innes‑Gold A. A., McManus L., Lester E., Ong T., Cook‑McNab A., Rahnke S., *et al.* *Coral reef halo dynamics are driven by herbivory and temperature.* **The American Naturalist**, in press.

## Requirements
- **Fortran 90 compiler**
- **Python ≥ 3.9** with:
  - `geopandas`
  - `numpy`
  - `matplotlib`
  - `pandas`

## Usage
1. Process the shapefile with the provided Python scripts.  
2. Navigate to the relevant figure folder.  
3. Run the Fortran code to generate the simulation data.  

For questions or further details, please consult the manuscript or contact the authors.
