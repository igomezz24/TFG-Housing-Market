# Complex systems and statistical mechanics in housing markets

This repository contains the source code and data analysis scripts for the Bachelor's Thesis (TFG) titled *"Complex systems and statistical mechanics in housing markets"*.

## Overview
 Understanding the variability of the housing market is essential for assessing systemic risk and preventing crises. For this reason, it must be treated as a complex system far from thermodynamic equilibrium. Forty-three time series of quarterly price indices are analysed using the persistent random walk formalism, stochastic escape times, and random matrix theory. The analysis of returns reveals heavy-tailed distributions, confirming a probability of extreme events higher than in a Gaussian distribution. The calculation of the mean squared displacement shows a short-term superdiffusive regime with a transition to long-term subdiffusion, demonstrating a finite memory of the system. Escape times reveal a temporal asymmetry favouring growth over contraction. Finally, cross-correlation analysis identifies a dominant market mode and a group mode indicating the existence of economic subgroups. It is concluded that the dynamics are non-Gaussian and incompatible with the classical random walk.

## Repository Structure

* `Tot Codi TFG.ipynb`: Jupyter Notebook containing the full data pipeline, from raw time series processing to the generation of the statistical models and figures.

**Datasets:**
* **US Market:** 
  * `USA House Price Index.csv` (National index)
  * State-level indices: `Alaska`, `California`, `Florida`, `Indiana`, `New York`, `Ohio`, `Pennsylvania`, `Texas`, and `Wyoming` (Formatted as `[State] House Price Index.csv`).
* **UK Market:** 
  * `UK + Regions House Price Index Cleaned 1973-2025_4.csv`: Quarterly price index data for the UK and its internal regions.
* **International Markets:** 
  * `23 países trimestral 1975 - 2025, Federal Reserve Bank of Dallas.csv`: Global quarterly price indices for 23 selected countries.

## Requirements
To run this code, the following libraries:
* `pandas`
* `numpy`
* `matplotlib`

## Usage
1. Clone the repository: `git clone https://github.com/tu-usuario/tu-repositorio.git`
2. Open the Jupyter Notebook `Tot Codi TFG.ipynb`.
3. Ensure the data files are in the correct directory.
4. Run all cells to reproduce the results and graphs.

## Author
* **Iván Gómez Plaza** - [Universitat de Barcelona - Facultat de Física]
