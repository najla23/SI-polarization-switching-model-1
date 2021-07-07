[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/template-for-supporting-information/HEAD)

# Electronic Notebook

This is an electronic notebook for the scientific publication
_Polarized Switching Force Field Model for Membrane Translocation_

## Layout

Description of the directory layout.

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
