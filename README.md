# Physics-Informed Neural Network for the Free Schrödinger Equation

## Overview

This project demonstrates how to solve the one-dimensional, free-particle Schrödinger equation  
\[
i \frac{\partial \psi}{\partial t} + \frac{1}{2} \frac{\partial^2 \psi}{\partial x^2} = 0
\]  
using a **Physics-Informed Neural Network (PINN)**. In natural units (ℏ = m = 1), the network learns the complex wavefunction ψ(x, t) over a spatio-temporal grid by enforcing:

1. **Physics constraint**: the Schrödinger PDE at collocation points  
2. **Data constraint**: the initial condition  
   \[
   \psi(x,0) = e^{-x^2}\,e^{\,i k x},\quad k = 2.0
   \]


**Language & Libraries:** Python, TensorFlow 2.x, NumPy, Matplotlib 

The main idea behind this is to familiarize myself with PINNs
