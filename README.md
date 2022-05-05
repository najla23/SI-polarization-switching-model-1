[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-polarization-switching-model/HEAD)

# Electronic Notebook: Electronic polarization effects on membrane translocation of anti-cancer drugs

Supporting information for reproducing results in the scientific article
[_Electronic polarization effects on membrane translocation of anti-cancer drugs_](https://dx.doi.org/10.1039/d2cp00056c).


## Directory Layout

- `Simulations/` - SMD trajectories for umbrella sampling 
- `Topology-DLPC/` - Topology files for DLPC membrane
- `Topology-DPPC/` - Topology files for DPPC membrane
- `Topology-POPC/` - Topology files for POPC membrane 
- `plots/` - reproduction of plots presented on the article

## Requirements

To run the Notebooks online, click on the _Launch Binder_ logo above. Alternatively, if you want to run on your own computer,
install python using e.g. [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://docs.conda.io))
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
    conda env create -f environment.yml
    source activate switchingff
    jupyter-notebook
```
