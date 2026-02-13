# ARC_reactivation_model
Mathematical model of dynamic antigen expression in HIV reservoir clones. Code for Ferreira, I.A.T.M.
 *et al.*, Dynamic Antigen Expression and CTL Resistance in HIV Reservoir Clones. *Nature* (2026).

This repository contains code for simulations of our model of transient antigen expression and for fitting to simulated and real data. All necessary code is included in the jupyter notebook **ARC_reactivation_model.ipynb**. This file can be opened and **run with a free account** on Google Colab to recreate our analaysis of ARC data. Access the active version on Colab through this [link](https://colab.research.google.com/drive/1zJJaVwacgs4qot6J3AYt5iPx9uzr3ved?usp=sharingc).

1. System requirements:
 - any system that can run a jupyter notebook
 - Run with: Python 3.12.12, numpy v2.0.2, scipy v1.16.3, matplotlib v3.10.0, pymc v5.27.1, pytensor v2.37.0, arviz v0.22.0, seaborn v0.13.2, pandas v2.2.2
2. Installation guide:
 - download the jupyter notebook and then upload it to your Google Drive to run it via Google Colab
 - less than 5 minutes to install
3. Demo:
  - There is a code block included in jupyter notebook that generates simulated data and shows model fitting results
  - Code will return samples from the posterior distribution for model parameters, which are summarised and visualized
  - Run time depends on size of data set, number of chains, and number of samples during MCMC
4. Instructions for use:
  - To fit this model to your own data, replace the data entered in the "experimental data" code chunks with your own. Updated priors in `latency_model` chunk as needed and run fitting code.

For questions and concerns, post an issue or contact Maddie Gastonguay (mgaston1@jh.edu) and Alison Hill (alison.hill@utoronto.ca).
