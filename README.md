<!-- https://social-science-data-editors.github.io/template_README/template-README.html -->
<!-- created with $ pandoc ReadMe.md -o ReadMe.pdf --top-level-division=chapter -->

# README


## Submission Information

**Article:** When Norms Collide: How Feedback Dynamics of Salience Describe Norm Compliance in Littering and Beyond

**Corresponding Author:** Markus Krecik, Economics Department, Freie Universität, Boltzmannstr. 20, 14195 Berlin

**Email:** m.krecik@fu-berlin.de


## Overview

The code in this replication package simulates the differential equations and generates the 2 figures in the paper using Mathematica. The code runs in less than 1 hour.


## Data Availability and Provenance Statements

The paper uses data obtained from (Cialdini et al, 1991). The data is extracted from Fig. 2, and stored in the Mathematica notebook.
No special permission is needed to use the data.


## Computational requirements

### Software Requirements

- Mathematica >=12.3

### Controlled Randomness

- [x] No Pseudo random generator is used in the analysis described here.

### Memory, Runtime, Storage Requirements

#### Summary

Approximate time needed to reproduce the analyses on a standard (2024) desktop machine:

- [x] <10 minutes

Approximate storage space needed:

- [x] < 25 MBytes

Approximate Memory needed:

- [x] < 4 GBytes

#### Details

The code was last run on a **6-core Intel-based laptop with Ubuntu 22.04 with 32GB RAM and 50GB of free space**.


## Description of programs/code

- `norms_dynamics_plots.nb`: Generates all plots used in the paper. Code which creates figures is clearly labeled by headings in the file. Output files are called appropriately (`Fig1.pdf`--`Fig2.pdf`) and should be easy to correlate with the manuscript.
  - Final figures are stored in the same folder


## Instructions to Replicators

1. Open Mathematica Notebook
2. Select Evaluation/Evaluate Initialization Cells (Alt+v, Alt+z)
3. If prompted to run initialization cells, press yes


## List of tables and programs

The provided code reproduces:

- [x] All figures in the paper

| Figure/Table #    | Program                  | Output file    |
|-------------------|--------------------------|-------------|
| Figure 1  | `norms_dynamics_plots.nb` | `Fig1.pdf`  |
| Figure 2  | `norms_dynamics_plots.nb` | `Fig2.pdf`  |


## References

Cialdini, Robert B., Carl A. Kallgren, and Raymond R. Reno. “A Focus Theory of Normative Conduct: A Theoretical Refinement and Reevaluation of the Role of Norms in Human Behavior.” In Advances in Experimental Social Psychology, edited by Mark P. Zanna, vol. 24. Academic Press, 1991. https://doi.org/10.1016/S0065-2601(08)60330-5.

---
