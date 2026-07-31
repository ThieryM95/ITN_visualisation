# ITN_visualisation

This repository contains the analysis code accompanying the manuscript:
Trade-offs in deploying chlorfenapyr-pyrethroid insecticide-treated nets to reduce malaria burden: a modelling study
Authors: Thiery Masserey¹ ², Swapnoleena Sen¹ ², Neil Hobbs³, Clara Champagne¹ ², Thomas A. Smith¹ ², Nakul Chitnis¹ ²
¹ Swiss Tropical and Public Health Institute (Swiss TPH), Allschwil, Switzerland
² University of Basel, Basel, Switzerland
³ Liverpool School of Tropical Medicine, Liverpool, United Kingdom
Correspondence: Prof. Nakul Chitnis (nakul.chitnis@unibas.ch)

---

# Overview
This study used OpenMalaria, an individual-based model of malaria epidemiology and transmission developed by Swiss TPH.
OpenMalaria documentation is available at:
https://github.com/SwissTPH/openmalaria/wiki

This repository contains the data and R code used to generate the figures for two complementary analyses presented in the manuscript.

Analysis 1
We compared the public health impact of deploying:
* conventional pyrethroid-only insecticide-treated nets (PYR-ITNs), and
* chlorfenapyr-pyrethroid insecticide-treated nets (CFP-PYR-ITNs) under different deployment strategies. Because CFP-PYR-ITNs are more expensive than PYR-ITNs, we evaluated scenarios in which the increased unit cost resulted in:
  * no compromise (assuming a higher budget),
  * a 25% or 50% reduction in coverage relative to PYR-ITNs.
  * a 25% or 50% reduced deployment frequency (every 4 or 6 years) relative to PYR-ITNs (every3 years).

Analysis 2
We quantified the change in malaria burden among individuals who might lose access to insecticide-treated nets under the reduced-coverage CFP-PYR-ITN scenarios.


---

## Repository structure

The repository is organised into three main folders:

```
Analysis_1_Figures/
```

Contains the data, R code, and PDF versions of the figures for Analysis 1.

```
Analysis_2_Figures/
```

Contains the data, R code, and PDF versions of the figures for Analysis 2.

```
Methods/
```

Contains the data, R code, and PDF versions of figures and illustrations used in the Methods section of the manuscript.

---

# Note 

Within each folder, the files are organised according to the figure names used in the manuscript.
The plotting scripts were developed using the authors' original folder structure and working directories. To reproduce the figures, users will need to update the file paths in the scripts to match their local directory structure.


