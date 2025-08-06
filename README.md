# RocketNozzles_SimCham

# 🚀 Rocket Thruster Nozzle Simulation (1D Isentropic Flow)

This project simulates a rocket thruster nozzle using **1D compressible flow theory** (isentropic approximation). It visualizes how flow properties like Mach number, pressure, temperature, and velocity evolve through a **converging-diverging nozzle**.

## 🔬 Physics Used
- **Isentropic flow** (adiabatic & reversible)
- **Ideal gas behavior**
- Mach number vs. area ratio solved numerically
- Properties derived from isentropic equations

## 📊 Visualized Results
- Mach Number distribution
- Pressure drop across the nozzle
- Temperature variation
- Velocity (accelerated to supersonic)

## 🛠 Parameters (default)
- Chamber Pressure: 2 MPa
- Chamber Temperature: 3000 K
- Nozzle: Parabolic, symmetric
- Throat Area: 0.01 m²

## ▶️ Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com)
2. Paste the code from `nozzle_simulation.ipynb`
3. Run the cell to view plots

## 🚀 Future Improvements
- Add thrust calculation
- Include shock modeling (non-isentropic flow)
- Real gas behavior for high temperatures
- 2D/3D CFD extension

## 📸 Sample Output

![Sample Plot](sample_output.png) *(Add image if hosted on GitHub)*

## 📚 References
- Anderson, J. D. *Modern Compressible Flow*
- NASA Glenn Compressible Flow Calculator
