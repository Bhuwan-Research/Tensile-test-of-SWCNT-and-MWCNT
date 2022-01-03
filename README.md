# Tensile-test-of-SWCNT-and-MWCNT
The tensile test simulation was performed on LAMMPS to get acquainted with the MD simulation. It is a class-based project for the fulfillment of the Nanomechanics course.
The tensile test of SWCNT &amp; MWCNT using LAMMPS to find the Yield strain, Ultimate strength, and Young's modulus.


#### ---------------------------------steps to perform test------------------------------------
1. open Lammps input script SWCNT (10,0) Pulling.lmp , SWCNT (20,0) Pulling.lmp  , MWCNT (20,0),(10,0) Pulling.lmp 
2. 
change fname: MWCNT.20.0.10.0.60.data , CNT.10.0.60.data , CNT.20.0.60.data
simname index CNT.10.0.60.300K.1
 Test_temp : 
, Srate, Def_run according to 300 K, 800 K , 1600 K , 2400 K. and strain rate 0.25e-3, 0.5e-3, 0.75e-3 1e-3 ps^-1.
3. Run lammps script file.
4. open lammps trajectory files (.lammpstjr) using VMD or Ovito to visualize MD simulation.
5. Change path (D:\NanoMechanics Project\Graphs) in matlab code into your directory.
6. Run matlab script (.mlx) to plot graphs.
