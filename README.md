"Recovering Parameters of Galaxy Cluster Systems using Weak Gravitational Lensing" - supervised by Professor Adam Hincks.

Undergraduate thesis project through AST425: Research Topic in Astronomy at the University of Toronto. 

This research utilizes observations of the Abell 399 - Abell 401 galaxy cluster pair to reconstruct shear maps from convergence maps in order to test the sensitivity of a recoverable convergence map for a given level of noise in the observations, as shape noise allows us to better understand instrument requirements for detecting cosmic filaments with weak lensing. 

The goal of this project is to determine the amount of sensitivity needed in an observation, or the maximum tolerable shape noise to detect a filament between two galaxy clusters of known mass. We estimate the best-fit parameters and corresponding errors of the appropriate shear maps for various levels of noise using the Markov Chain Monte Carlo (MCMC) method via the Python module $\tt{emcee}$. This process is repeated for a cluster pair system, modelled after the A399-401 system and a stand-alone filament, whose convergence profile takes the form of a Mesa model (Hincks et al. 2022); the process is finally executed for the more complex combined cluster pair and filament sytem.

Each $\tt{ipynb}$ in the repository represents contains this process for a different system - either a single cluster, the cluster pair, a single filament, or the combined cluster pair + filament system.
