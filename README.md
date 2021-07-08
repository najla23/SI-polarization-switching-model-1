[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-polarization-switching-model/HEAD)

# Electronic Notebook: Polarized Switching Force Field Model for Membrane Translocation

## Directory Layout

- `thermodynamic_integration/` - MD setup for thermodynamic integration
- `membrane_translocation/` - MD setup for pulling across three different membranes
- `electronic_structure/` - Electronic structure calculations of anti-cancer drug molecules
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
