---
layout: default
---

# Welcome to the CELL documentation

**CELL (Cellular Effect Lesions Linker)** is a graphical interface for cell survival predictions based on different simulation chains pre-loaded in the system for different cell lines [[1]](#references). The program was written in Python using the PyQt5 library.

## Install

The [repository](https://github.com/mpvalen/interfaz_grafica_adn) has to be downloaded. The following libraries are necessary for the execution,  `python`  should be version 3.X minimum.

- Numpy
- Matplotlib
- PyQt5
- scipy
- natsort
- uncertainties

The program allows the use of the [MCDS](https://faculty.washington.edu/trawets/mcds/) (Monte Carlo Damage Simulation) software [[2]](#references)[[3]](#references)[[4]](#references)[[5]](#references) . The latest version of MCDS (3.10A) is required for the correct execution of the program, the folder  `mcds` should be located inside the `INTERFAZ` directory.

The current version of the program has two theoretical models pre-loaded that can be combined with MCDS to estimate cell survival fractions:
- Track-damage repair model (Wang et al. 2018)[[6]](#references)
- Two lession kinetic model (TLK) (Stewart 2001)[[7]](#references)

## Execution

To use the interface, simply execute `main.py`.

## Contents

- [Usage](./usage.md)

- [Examples](./examples.md)

## Citing CELL

If you use CELL in a scientific publication, consider citing the following reference:

Valenzuela M.P., Ciardiello A., Buvic L., Espinoza I., Galvez S., Salgado S., Videla H.,
Russomando A., CELL: A user-friendly tool for computing cell survival based on radiation-induced
DNA damage, Radiotherapy & Oncology, 194, 2024, Digital poster. 
[https://doi.org/10.1016/S0167-8140(24)02410-1](https://doi.org/10.1016/S0167-8140(24)02410-1)

## References

[1] S. Salgado, A. Carabe, I. Espinoza, S. Galvez, M.P. Valenzuela, A. Russomando, Monte Carlo simulations of cell survival in proton SOBP. Phys. Med. Biol. 68 195024 (2023)

[2] V.A. Semenenko and R.D. Stewart. A fast Monte Carlo algorithm to simulate the spectrum of DNA damages formed by ionizing radiation. Radiat Res. 161(4), 451-457 (2004).

[3] V.A. Semenenko and R.D. Stewart. Fast Monte Carlo simulation of DNA damage formed by electrons and light ions. Phys. Med. Biol. 51(7), 1693-1706 (2006)

[4] Y Hsiao and  R.D. Stewart, Monte Carlo Simulation of DNA Damage Induction by X-rays and Selected Radioisotopes. Phys. Med. Biol. 53, 233-244 (2008)

[5] R.D. Stewart, V.K. Yu, A.G. Georgakilas, C. Koumenis, J.H. Park, D.J. Carlson, Monte Carlo Simulation of the Effects of Radiation Quality and Oxygen Concentration on Clustered DNA Lesions. Radiat. Res. 176, 587-602 (2011)

[6] Wang, W., Li, C., Qiu, R. et al. Modelling of Cellular Survival Following Radiation-Induced DNA Double-Strand Breaks. Sci Rep 8, 16202 (2018). https://doi.org/10.1038/s41598-018-34159-3

[7] Stewart RD. Two-lesion kinetic model of double-strand break rejoining and cell killing. Radiat Res. 2001 Oct;156(4):365-78. doi: 10.1667/0033-7587(2001)156[0365:tlkmod]2.0.co;2. PMID: 11554848.

[back](./)
