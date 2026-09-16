
# DTLreactingFoam


[![Latest Release](https://img.shields.io/badge/latest%20release-v1.0.0-blue)](https://github.com/danhnam11/DTLreactingFoam-12/releases)
[![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)](https://github.com/danhnam11/DTLreactingFoam-12/pulls)
[![License](https://img.shields.io/badge/license-GPL--3.0-yellow)](https://github.com/danhnam11/DTLreactingFoam-12/blob/main/LICENSE)

[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cpc.2026.110052-red)](https://doi.org/10.1016/j.cpc.2026.110052)


## Overview
A package for high fidelity simulations of laminar reacting flows in OpenFOAM with low computational cost, incorporating both the detailed transport model (DTM) and the polynomial fit transport model (FTM) based on the principle of kinetic gas theory [1]. To enhance computational efficiency, it was integrated with the time-correlated thermophysical property calculation (coTHERM) method. This technique can significantly reduce the computational cost of numerical simulations using DTM/FTM in OpenFOAM while preserving accuracy. Readers are referred to our paper for all validation data.


## OpenFOAM Versions

| Version | Source Code |
|---|---|
| OpenFOAM 8 | [DTLreactingFoam-8](https://github.com/danhnam11/DTLreactingFoam-8) |
| OpenFOAM 10 | [DTLreactingFoam-10](https://github.com/danhnam11/DTLreactingFoam-10) |
| OpenFOAM 12 | [DTLreactingFoam-12](https://github.com/danhnam11/DTLreactingFoam-12) |

## Installation

Please refer to the README.md file in the corresponding version-specific source repository for installation instructions.

## Documentation

Documentation and usage examples are provided in the respective source repositories.

## Authors 
This package was developed at the Clean Combustion & Energy Research Lab., Dept. of Mech. Engineering, Ulsan National Institute of Science and Technology (UNIST), Korea ([Prof. C.S. Yoo](https://csyoo.unist.ac.kr/)). If you publish results obtained by using this package, please cite our paper as follows:
- D. N. Nguyen, J. H. Lee, C. S. Yoo, DTLreactingFoam: An efficient CFD tool for laminar reacting flow simulations using detailed chemistry and transport with time-correlated thermophysical properties, Computer Physics Communications 322 (2026) 110052.

If you need help with installation or have any questions, feel free to reach out: 
- danhnam11@gmail.com or nam.nguyendanh@hust.edu.vn 

## Reference
[1] R. J. Kee, F. M. Rupley, E. Meeks, J. A. Miller, CHEMKIN-III: A FORTRAN chemical kinetics package for the analysis of gas-phase chemical and plasma kinetics, SAND96-8216 (1996).
