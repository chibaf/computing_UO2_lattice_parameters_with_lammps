# computing_UO2_lattice_parameters_with_lammps
lattice parameter depends on temperature

(We employ Ubuntu 22.04)

usage(1): python3 fcc111.py > data.fcc111 #generate UO2 lattice

usage(2): python3 lattice.py # computing UO2 lattices for temperatures with lammps

usage(3): python3 lattice_p.py # computing UO2 lattice parameters for temperatures from lammps logs

the document for programs above: UO2_lattice_parameters.pdf

<img width="791" alt="fcc111" src="https://user-images.githubusercontent.com/1296728/180451685-89ae3955-a1c9-4edc-8bca-c8046fef4ec6.png">


ref:

2.7. Output Readers — LAMMPS documentation https://docs.lammps.org/Python_formats.html

2.6. Download the LAMMPS source with git https://docs.lammps.org/Install_git.html

remark: we need kspace package of lammps for UO2 lammps calculation

then: cmake ../cmake/ -D PKG_KSPACE=yes
