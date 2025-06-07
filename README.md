# Physics-Informed Neural Network for the Free Schrödinger Equation

## Overview

This project demonstrates how to solve the one-dimensional, free-particle Schrödinger equation  

using a **Physics-Informed Neural Network (PINN)**. In natural units (ℏ = m = 1), the network learns the complex wavefunction ψ(x, t) over a spatio-temporal grid by enforcing:

1. **Physics constraint**: the Schrödinger PDE at collocation points  
2. **Data constraint**: the initial condition  


**Language & Libraries:** Python, TensorFlow 2.x, NumPy, Matplotlib 

The main idea behind this is to familiarize myself with PINNs
