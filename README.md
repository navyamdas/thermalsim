# Thermal Performance Simulation of Buildings

## Objective
This project uses a physics-based simulation in Python to model the thermal performance of a simplified building in two distinct climates:  
- **Temperate climate:** Berlin  
- **Tropical climate:** Kuala Lumpur  

The primary goal is to demonstrate the energy and cost savings achieved by effective insulation, illustrating its value in both heating- and cooling-dominant environments.

---

## Technical Approach
The simulation is built within a Jupyter Notebook to combine code, technical documentation, and visual output into a single, cohesive document.

- **Physics-Based Modeling:**  
  The core of the simulation relies on the fundamental heat transfer equation:  

  \[
  Q = U \cdot A \cdot \Delta T
  \]

  It calculates the hourly heating and cooling loads by modeling thermal resistance (R-value) and the overall heat transfer coefficient (U-value).

- **Data Simulation:**  
  Synthetic hourly temperature data is generated for both climates using a negative cosine function to model seasonal and daily cycles, placing the warmest period in July and the coldest in January.

- **Data Analysis & Visualization:**  
  Python libraries such as **Pandas** and **Matplotlib** are used to process the simulated data and generate time-series visualizations. These graphs clearly show the difference in energy loads between poorly and well-insulated buildings over a full year.

- **Cost Analysis:**  
  The simulation quantifies the energy savings in kilowatt-hours (kWh) and translates them into annual cost savings in Euros (€), providing a clear financial justification for good insulation.

---

## Key Findings
- **Temperate Climate (Berlin):**  
  Effective insulation drastically reduces both heating loads in winter and cooling loads in summer, resulting in significant year-round energy savings.

- **Tropical Climate (Kuala Lumpur):**  
  In a climate with no heating needs, proper insulation is crucial for minimizing heat gain, directly lowering the demand on air conditioning and leading to substantial cost reductions.

---

## Skills Demonstrated
This project showcases skills in:  
- Applied physics  
- Data simulation  
- Data visualization  
- Energy efficiency analysis  

It demonstrates a practical understanding of energy efficiency principles and their real-world impact.

---

## How to Run the Project
This project can be run in any environment that supports Jupyter Notebooks, such as Anaconda.

1. Ensure the following libraries are installed:  
   - `numpy`  
   - `pandas`  
   - `matplotlib`  

2. Open the file `insulation_simulation.ipynb` in Jupyter Notebook.  

3. Run each cell in order from top to bottom.  
