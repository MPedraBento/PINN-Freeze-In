# Introduction

We parametrically solve the Boltzmann equations (BEs) governing freeze-in dark matter (DM) in alternative cosmologies with Physics-Informed Neural Networks (PINNs). Through inverse PINNs, using a single DM experimental point – observed relic density – we determine the physical attributes of the theory, namely power-law cosmologies, inspired by braneworld scenarios, and particle interaction cross sections.

<p align="center">
  <img src="https://github.com/MPedraBento/PINN-Freeze-In/blob/main/plots/ParametricRS.png" width="300" />  &nbsp  &nbsp &nbsp
  <img src="https://github.com/MPedraBento/PINN-Freeze-In/blob/main/plots/SwitchVsSmooth.png" width="300" /> 
</p>

# Notebooks
utils.py

## Forward problem: parametric PINN solution
pinn_forward_parametric.ipynb

## Solving inverse problems with PINNs
pinn_inverse_C.ipynb <br>
pinn_inverse_gamma.ipynb <br>
pinn_inverse_transition.ipynb <br>
pinn_inverse_bayesian.ipynb <br>

All the aforementioned notebooks generate the necessary files to draw the plots in plots.ipynb.
