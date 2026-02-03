# MHIT36

Multi-GPU code for intreface-resolved simulations of multiphase turbulence in homogeneous isotropic turbulence and channel flow configurations.
The code relies on direct numerical simulation of Navier-Stokes equations coupled with a phase-field method (ACDI) for interface description.
Tracking of Lagrangian particles (tracers) is also supported.
The code parallerelization relies on the cuDecomp library.
Variable viscosity version for PRIN simulations.


~~~text
███    ███ ██   ██ ██ ████████ ██████   ██████       
████  ████ ██   ██ ██    ██         ██ ██              
██ ████ ██ ███████ ██    ██     █████  ███████   
██  ██  ██ ██   ██ ██    ██         ██ ██    ██     
██      ██ ██   ██ ██    ██    ██████   ██████        
~~~


If you use this code, please cite the following works: 
```bibtex
  @article{roccon2025,
  title   = {MHIT36: A Phase-Field Code for Gpu Simulations of Multiphase Homogeneous Isotropic Turbulence},
  author  = {Roccon, A. and Enzenberger, L. and Zaza, D. and Soldati, A.},
  journal = {Computer Physics Communications},
  year    = {2025},
  volume  = {314},
  issue   = {109804},
  doi     = {https://doi.org/10.1016/j.cpc.2025.109804}
}
```

```bibtex
  @article{roccon2026,
  title   = {MHIT36: Extension to wall-bounded turbulence and scalar transport equation},
  author  = {Roccon, A.},
  journal = {Computer Physics Communications},
  year    = {2026},
  volume  = {---},
  issue   = {109956},
  doi     = {https://doi.org/10.1016/j.cpc.2025.109956}
}
```
