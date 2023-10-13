# Reduced-order surrogate modeling for linear-nonlinear coupled problems

Jupyter notebook version 6.4.12

## About
All scripts corresponding to the problems of interest from the final project are included here. The problems of interest are

* Linear_poisson
* Nonlinear_diffusion
* Nonlinear_reaction

## Installation requirements
You will need to have installed FEniCSx, an open source computing platform for solving partial differential equations. See https://fenicsproject.org/download/ for details.

Dolfin Version 2019.1.0

## How to use

Each folder corresponds to a problem of interest. All folders contain the files
  * functions.ipynb
    * A file containing all functions with detailed description of the inputs and outputs
  * Results.ipynb
    * A running file containing the performance results of the reduced-order models (ROMs) as they are obtained in the thesis
  * FOM_snapshots_LL_P1.ipynb
    * A file that computes solutions to the full-order model (FOM) of the respective problem

Simply run the running files from top to bottom in order to run the simulations.

Each folder is equipped with .pkl files that are saved variables so you don't have to run this time and again. 
In each running file, the boolean 'alreadyrun' in each cell determines whether you want to use the saved variables (1) or not (0)

Additionally, the respective folders contain the following:

Linear_poisson:
  * Failure_probability.ipynb
    * A running file containing the results of the failure probability
  * Hybrid_snapshots_LL_P1.ipynb
    * A file that computes solutions to the hybrid model
  * Importance_Sampling_FOM.ipynb
    * A file that computes solutions to the FOM applied with importance sampling

Nonlinear_diffusion:
  * Adding_modes.ipynb
    * A running file containing the results of adding modes
  * GD_Newton_BFGS.ipynb
    * A running file containing the results of the iterative solvers
  * MC_simulations.ipynb
    * A file that computes Monte Carlo samples of the FOM
  * MC_simulations_ROM.ipynb
    * A file that computes Monte Carlo samples of the ROM
  * PDF_estimation
    * A running file containing the results of the PDF estimation

Nonlinear_reaction:
  * Estimating_statistical_information.ipynb
    * A running file containing the results of estimating the statistical information

## Contact

Mail: stuivertje13@gmail.com
