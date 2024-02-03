<h1 align="center"> LAMMPS-HEA-tensile-script</h1> 

<h2 align="center">A Molecular Dynamics Study on the Uniaxial Tensile Behaviour of NbTiZrMoV High Entropy Alloy: Effect of Temperature, Strain Rate and Alloying Element Content</h2>


doi: ...

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/0c480431-fa3d-4047-96d4-432c7a228109" height="15px"> Operating systems: Windows 11, version 23H2

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/68f4d2f0-b5c9-40e5-b931-50acd0a06e97" height="15px"> Versions of software: LAMMPS 64-bit 2Aug2023-MSMPI

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/b2ffe720-fc11-422d-842d-1383993d5cbc" height="15px"> Any required non-standard hardware: No

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/46fd6ea5-48f3-414d-8717-13f55da766d0" height="15px"> Instructions to install: https://docs.lammps.org/Install_windows.html

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/bbf26202-2008-4e2c-9f6b-c95589cae75a" height="15px"> Instructions to run on data: `mpiexec -np xx lmp -in input.lmp` (xx is the number of processors to use)

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/66b5eb6c-536f-4b6e-a973-a8d92e733b2f" height="15px"> Expected output: "stress-curve-xx.txt" for stress data; "dump.xx" for atomic configurations

<img src="https://github.com/Riaz-404/LAMMPS-HEA-tensile-script/assets/66328924/d822daa7-5ab7-4abe-afdc-91aa1d54569e" height="15px"> Expected run time: several hours to several days depends on the number of processors

<h3> How to run the software on your data: </h3>

- Structure: High entropy alloy structure can be created using LAMMPS script or atomsk command.
- Simulation:<br>
  - "NbTiZrMoV.lmp" is the structure model created LAMMPS script or atomsk.
  - "library.meam", "NbTiZrMoV.meam" are the interatomic potential files.
  - "input.lmp" is the file to define the simulation script
