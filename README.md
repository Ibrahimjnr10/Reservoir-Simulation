# Reservoir-Simulation
This project focuses on simulating pressure distribution in a reservoir

### Overview
This project simulates pressure distribution in a 2D reservoir grid, incorporating well configurations and operational conditions. The results help understand reservoir behavior and well interactions.
Link to Documentation on Approach, Advisably for Non Technical Audience https://medium.com/@abdulsalamibrahima017/reservoir-simulation-for-pressure-distribution-4abfcb65989b
### Features
Simulates pressure changes over time for producers and injectors.
Efficient sparse matrix implementation for large grids.
Visualization of pressure distribution at different time steps.

### Reservoir Properties
| Parameter             | Value                          | Description                                  |
|-----------------------|--------------------------------|----------------------------------------------|
| Grid Size             | 99 × 99                       | Number of blocks in X and Y directions.      |
| Length (L)            | 20,000 ft                     | Reservoir length.                            |
| Width (W)             | 20,000 ft                     | Reservoir width.                             |
| Thickness (h)         | 300 ft                        | Reservoir thickness.                         |
| Well Radius (rw)      | 0.25 ft                       | Radius of wells.                             |
| Time Step (dt)        | 1 day                         | Simulation time step.                        |
| Viscosity (μ)         | 1 cP                          | Fluid viscosity.                             |
| Formation Vol. Factor (Bw) | 1                       | Formation volume factor.                     |
| Compressibility (ct)  | 1 × 10⁻⁶ psi⁻¹               | Rock and fluid compressibility.              |
| Initial Pressure (pi) | 3000 psi                      | Initial reservoir pressure.                  |

### Well Configurations
| Well | x-Location (ft) | y-Location (ft) | Type      | Operating Condition           |
|------|-----------------|-----------------|-----------|-------------------------------|
| 1    | 5000           | 5000           | Producer  | 1000 ft³/day                  |
| 2    | 15000          | 5000           | Producer  | 1000 ft³/day                  |
| 3    | 5000           | 15000          | Producer  | 1000 ft³/day                  |
| 4    | 15000          | 15000          | Producer  | 1000 ft³/day                  |
| 5    | 10000          | 10000          | Injector  | 1000 psi                      |


### Setup
Requirements
- Python 3.8+
- NumPy, SciPy, Matplotlib
Installation
- Clone the repository:
git clone https://github.com/Ibrahimjnr10/Reservoir-Simulation.git  
cd Reservoir-Simulation 
- Install dependencies:
pip install -r requirements.txt 

### Usage

- Configure reservoir properties in Res_properties() (grid size, fluid properties, etc.).
- Define well locations, types (producers/injectors), and operating conditions.
- Run the simulation:
python res_simul.ipynb

Visualize results with 3D pressure maps.
Results
Pressure maps for time steps 
t=3,
t=20, and 
t=50.


### License
This project is licensed under the MIT License.

### Contact
For questions, abdulsalamibrahima017@gmail.com

