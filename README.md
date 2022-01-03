# Tensile-test-of-SWCNT-and-MWCNT
The tensile test of SWCNT &amp; MWCNT using LAMMPS to find the Yield strain, Ultimate strength and Young's modulus.


#### steps
1. open Lammps input script file (.imp) 
2. change fname, Test_temp, Srate, Def_run according to 300 K, 800 K , 1600 K , 2400 K. and strain rate 0.25e-3, 0.5e-3, 0.75e-3 1e-3 ps^-1.
3. Run lammps script file.
4. open lammps trajectory files (.lammpstjr) using VMD or Ovito to visualize MD simulation.
5. Change path (D:\NanoMechanics Project\Graphs) in matlab code into your directory.
6.  Run matlab script (.mlx) to plot graphs.
