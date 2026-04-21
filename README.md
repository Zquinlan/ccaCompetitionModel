# Coral larval settlement preference for crustose coralline algae can enhance coral persistence and restoration success<img width="468" height="70" alt="image" src="https://github.com/user-attachments/assets/129890d5-1d15-4c77-817b-4f9c8175acea" />

 <br />
Zachary A. Quinlan*, Lisa C. McManus, Megan J. Donahue <br />
*Corresponding author

### Abstract:
As coral reefs shift towards algal-dominated states worldwide, there is increasing interest in designing management interventions to slow or halt these declines. Crustose coralline algae (CCA), a major benthic component of many reef systems, have important interactions with coral yet their role in coral-algal regime shifts is not well understood. In recent studies, CCA has been shown to be either beneficial or antagonistic to coral larvae depending on the CCA species. This species-specific variability may play a large role in supporting or opposing regime shifts as dominance of more antagonistic CCA can potentially reduce the amount of available settlement space across the benthos and inhibit recruitment. To explore the impacts of this broad range of species-specific interactions, we expanded a well-studied analytical model to explicitly include CCA and larval settlement preference or inhibition based on CCA species-specific interactions. Our model results demonstrate the importance of local community composition for a better understanding of coral reef regime shifts that can be leveraged for management efforts. Through a series of reef restoration scenario simulations, we suggest that manipulating CCA or macroalgal cover during coral outplanting reduces the amount of effort required to shift community trajectories towards coral recovery.


### Funding sources:
Funding for the study was provided by the National Science Foundation-OCE PRF (award #2308400) awarded to ZAQ and by NSF BIO/DBI (award #2233983) and NSF OCE 2443233 awarded to LCM.

*****
## Repository Overview:
This repository contains the original code used to produce, simulate and analyze the models presented in our manuscript <br />


We have tried to clearly index each script and file below but if you have any questions please email me: zquinlan@gmail.com <br /> <br />

All raw data is in the subdirectory data/raw/

### Requirements:
R - Code was written and tested in 3.6.1 <br />
Python - Code was written and tested in 3.11 <br />
R Libraries - tidyverse, broom, data.table, DescTools, readxl, vegan, ape, lme4, MuMIn, RColorBrewer <br />
Python Libraries - Numpy, matplotlib, seaborn, pandas, mpl_toolkits, and multiprocessing

### Installation and running the code:
1) Clone the repo to your desktop
2) install R, python and the required libraries using the install.libraries() function
3) Open the .R file in the code directory
4) The locations of all the files are hard coded in the second section of the code "Loading -- Datasets". Change the beginnig file paths "'~/Documents/GitHub/ccaReefModeling" to the location where you have cloned the respository manually


*****
# Contents:
## code - all the code that we used to analyzed the data in the above manuscript
#### modifiedMumby07.ipynb 
- Jupyter notebook that takes the original Mumby et al., (2007) model and adds in CCA. Figure 2 was produced using code within this notebook by changing the variables as labeled within the figure <br /><br />
#### simanalysis.R
- Analysis of the results from the simulations <br /><br />
#### Simulations/
- Subfolder that contains the results python scripts used to simulate data from each of the simulations presented in figures 3-4.
- .slurm files are the submission files for the slurm cluster which we use.
<br /><br />

## data - raw data, plots, and analyzed spreadsheets we exported during analysis
* not all of this was used in the publication <br />

### plots:
- Plots and figures generated in R.<br />

### raw:
- This folder contains all of the results from the simulations that were run.
