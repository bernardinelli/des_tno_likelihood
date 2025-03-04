# des_tno_likelihood
 DES TNO likelihood in physical and dynamical properties


This repository includes a lot of the software developed as part of [Bernardinelli et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025arXiv250101551B/abstract). 

In the `Code` directory, we provide the implementation of the joint color-orbits-absolute magnitudes-light curve amplitude likelihoods, as well as the Simplex HMC software. The `Scripts` directory inside it also includes scripts that integrate these files and runs the chains for all cases demonstrated in the paper. 

Inside the `Chains` directory, we provide the primary HMC chains that led to the results discussed in the paper. Similarly, the selection functions are in the `Selection` directory. 

This repository also includes Jupyter Notebooks that reproduce the main plots and key results of the paper in the `Notebooks` directory. These notebooks also include information for how to read the chains and the selection function files.


While a comprehensive repository, not everything we produced for this massive paper is included (partially because some of the notebooks are quite messy and not at all user-friendly!). Please do not hesitate to ask for additional files, notebooks, or help using the dataset! 