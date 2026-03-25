# Non-equilibrium Dynamics of the Dicke-TFIM

A Julia implementation for simulating the non-equilibrium dynamics of the Dicke-Transverse Field Ising Model (TFIM) within the LMG (Lipkin-Meshkov-Glick) framework.


## Dependencies & Packages

This project is written in **Julia**. To run the simulation successfully, you will need the following packages:

* **`QuantumOptics.jl`**: Core library for defining quantum bases, operators, and solving the master equation.
* **`PyPlot.jl` & `PyCall.jl`**: Used for high-quality static plotting and generating dynamic GIF animations.
* **`ProgressMeter.jl`**: For tracking simulation progress in the terminal/notebook.
