# Reservoir-Simulation
This project focuses on simulating pressure distribution in a reservoir

### Overview
This project simulates pressure distribution in a 2D reservoir grid, incorporating well configurations and operational conditions. The results help understand reservoir behavior and well interactions.

### Features
Simulates pressure changes over time for producers and injectors.
Efficient sparse matrix implementation for large grids.
Visualization of pressure distribution at different time steps.

### Setup
Requirements
Python 3.8+
NumPy, SciPy, Matplotlib
Installation
Clone the repository:
bash
Copy
Edit
git clone https://github.com/Ibrahimjnr10/reservoir-simulation.git
cd reservoir-simulation
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt

### Usage

- Configure reservoir properties in Res_properties() (grid size, fluid properties, etc.).
- Define well locations, types (producers/injectors), and operating conditions.
- Run the simulation:
bash Copy Edit res_simul.ipynb

  Visualize results with 3D pressure maps.
Results
Pressure maps for time steps 
𝑡
=
3
t=3, 
𝑡
=
20
t=20, and 
𝑡
=
50
t=50.
Insight into flow dynamics near wells.

### License
This project is licensed under the MIT License.

### Contact
For questions, Ibrahim Abdulsalam

