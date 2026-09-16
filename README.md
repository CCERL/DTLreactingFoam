# DTLreactingFoam

## General Information
A package for high fidelity simulations of laminar reacting flows in OpenFOAM-12 with low computational cost, incorporating both the detailed transport model (DTM) and the polynomial fit transport model (FTM) based on the principle of kinetic gas theory [1]. To enhance computational efficiency, it was integrated with the time-correlated thermophysical property calculation (coTHERM) method. This technique can significantly reduce the computational cost of numerical simulations using DTM/FTM in OpenFOAM-12 while preserving accuracy. Readers are referred to our paper for all validation data. Readers are also referred to https://github.com/danhnam11/DTLreactingFoam-10 and https://github.com/danhnam11/DTLreactingFoam-8 for DTLreactingFoam in OpenFOAM-10 and OpenFOAM-8, respectively.

## Authors 
This package was developed at the Clean Combustion & Energy Research Lab., Dept. of Mech. Engineering, Ulsan National Institute of Science and Technology (UNIST), Korea (Prof. C.S. Yoo: https://csyoo.unist.ac.kr/). If you publish results obtained by using this package, please cite our paper as follows:
- D. N. Nguyen, J. H. Lee, C. S. Yoo, DTLreactingFoam: An efficient CFD tool for laminar reacting flow simulations using detailed chemistry and transport with time-correlated thermophysical properties, Computer Physics Communications 322 (2026) 110052 (https://doi.org/10.1016/j.cpc.2026.110052).

If you need help with installation or have any questions, feel free to reach out: 
- danhnam11@gmail.com or nam.nguyendanh@hust.edu.vn 

## Reference
[1] R. J. Kee, F. M. Rupley, E. Meeks, J. A. Miller, CHEMKIN-III: A FORTRAN chemical kinetics package for the analysis of gas-phase chemical and plasma kinetics, SAND96-8216 (1996).

## Notes: 
Should you find bugs or have suggestions on how to make the code better, please post on cfd-online using the following thread: https://www.cfd-online.com/Forums/openfoam-community-contributions/262087-dtlreactingfoam-new-solver-laminar-reacting-flow-simulations-openfoam.html 
