# stochastic-diffusion-simulator
A Python-based stochastic simulator for heat and particle diffusion in complex geometries (Wedges and Rings). Features analytical solutions, numerical modeling via Google Colab, and automated visual exports (.mp4/.gif).

# Stochastic Diffusion Simulator: Wedges & Rings

A high-performance stochastic simulator to model heat and particle diffusion in complex geometries. This project bridges theoretical physics with numerical modeling, providing visual and analytical insights into diffusion processes.

## 🚀 Quick Access
* **Interactive Code:** [Open in Google Colab](https://colab.research.google.com/drive/15l8qwfbsedoGXcBStuctSXT2Py14anlr?usp=sharing)
* **Detailed Theory:** `Theory_Stochastic_Diffusion.pdf` (Included in this report)

## 🧠 Mathematical Background
The project solves the **Fokker-Planck Equation** (Diffusion Equation) for two specific cases:

1. **The Wedge Geometry:** Brownian particle diffusion with absorbing boundaries. Solved using separation of variables in polar coordinates and Bessel functions.
2. **The Ring/Torus:** Diffusion in a circular tubular domain of circumference $2l$ with periodic boundary conditions.

## 🛠️ Features
* **Flexible Parameters:** Easily adjust the ring radius or wedge angle.
* **Automated Visualization:** Generates `.mp4` or `.gif` animations showing probability dispersion over time.
* **Analytical Validation:** Compares numerical results with the theoretical series solutions derived in the documentation.

## 📁 Repository Structure
* `/simulations`: Exported animations of the diffusion process.
* `Stochastic_Diffusion.ipynb`: Python implementation (Numerical methods + Plotly/Matplotlib).
* `Theory_Stochastic_Diffusion.pdf`: Full mathematical derivation (Spanish).

## 🧰 Tech Stack
* Python (NumPy, SciPy, Matplotlib)
* Google Colab
* LaTeX (for theoretical modeling)

---
*Developed as part of a Stochastic Processes research project.*
