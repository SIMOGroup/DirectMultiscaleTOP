# Introduction
We propose a new multiscale topology optimization approach for the direct and simultaneous design of lattice materials, 
without material homogenization at the microscale, using adaptive geometric components. 
The adaptive geometric components are projected onto macro- and micro-element density fields to calculate the effective densities 
of grid elements. Macro-and microstructures are simultaneously optimized, considering the load and boundary conditions 
of the overall structure without any additional constraints. 3D prototypes can be made by 3D printed machine after smoothing technique is solved.  

Structure of DirectMultiscaleTOP package: 
1. mainProgram: main program for running topology optimization problems. 
2. Other functions are given in subfolders. 
3. How to run DirectMultiscaleTOP 
  - Define a new problem following code structures 
  - Run mainProgram.m 
  - Get output
  - Call program for smoothing boundaries of final design to print out 3D prototypes

# Contributors
- Van-Nam Hoang
- Phuong Tran
- Van-Tuyen Vu
- Hung Nguyen-Xuan

# Funding Agency
Vingroup Innovation Foundation (VINIF) in project code VINIF.2019.DA04

# References
Van-Nam Hoang, Phuong Tran, Van-Tuyen Vu, H. Nguyen-Xuan, Design of lattice structures with direct multiscale topology optimization, Composite Structures, 252, 112718, 2020 https://www.sciencedirect.com/science/article/pii/S0263822320326441

