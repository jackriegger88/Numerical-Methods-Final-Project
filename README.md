# Numerical-Methods-Final-Project
Project Title
Numerical Analysis of a Three-Species Food Chain using the Hastings-Powell Model

## Project Description
This project focuses on the numerical simulation of a three-level food chain consisting of a **Resource** (e.g., vegetation), a **Consumer** (e.g., herbivore), and a **Top Predator** (e.g., carnivore). This biological system is governed by the Hastings-Powell equations, a set of three coupled, non-linear ordinary differential equations (ODEs). Unlike two-species models which often reach a simple equilibrium, three-species systems are known to exhibit complex periodic oscillations and even chaotic behavior depending on the input parameters.

The primary goal of this study is to implement the **4th-Order Runge-Kutta (RK4) method** to solve these equations. This numerical approach is chosen for its high accuracy and stability compared to simpler methods like Euler's. I will investigate how varying the "half-saturation" constants and birth/death rates impacts the long-term survival of the top predator and the overall stability of the ecosystem.

## Planned Directory Structure
* `README.md`: Project proposal, methodology, and final analysis.
* `src/`: Python scripts containing the RK4 solver and model logic.
* `notebooks/`: Jupyter Notebooks for running simulations and visualizing data.
* `results/`: Saved plots including time-series graphs and 3D phase portraits.
* `requirements.txt`: List of necessary Python libraries (NumPy, Matplotlib).

## Resources & References
* **Primary Paper:** Hastings, A., & Powell, T. (1991). *Chaos in a Three-Species Food Chain*. Ecology, 72(3), 896-903.
* **Libraries:** `NumPy` for vector-based numerical integration and `Matplotlib` for 2D and 3D data visualization.
* **Course Material:** Application of Numerical Methods for ODEs.

## Implementation Plan & Timeline
- [ ] **March 23:** Submit Project Proposal (GitHub Repository Setup).
- [ ] **April 5:** Research and define the specific constant parameters (a1, a2, b1, b2, etc.) to ensure a non-trivial simulation.
- [ ] **April 15:** Implement the RK4 solver in Python and verify accuracy against known growth models.
- [ ] **April 25:** Generate population-vs-time plots to visualize species interaction.
- [ ] **May 5:** Produce 3D Phase Portraits and finalize the technical report.

### Reach Goals
* **Sensitivity Analysis:** Create a "Bifurcation Diagram" to show the exact point where the system moves from stable cycles to chaos.
* **Comparison Study:** Implement a simple Euler method to demonstrate through error-plotting why RK4 is the superior choice for this specific problem.

## Collaborators
* **[Your Name]** - Solo Project
