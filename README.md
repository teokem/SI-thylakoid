[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/teokem/SI-thylakoid/master)

# Electron diffusion model for micropatterned chips for photocurrent generation

This repository contains a [Jupyter](http://jupyter.org) Notebook for reproducing the theoretical calculations of the scientific paper _Micropatterned Carbon-on-Quartz Electrode Chips for Photocurrent Generation from Thylakoid Membranes_, [DOI: ](http://dx.doi.org/).

### Layout

- `notebook.ipynb` Jupyter Notebook to perform calculations and generate plots
- `notebook.html` Jupyter Notebook in HTML format 

### Usage

To open the Notebooks, install python via [Miniconda](https://conda.io/miniconda.html) and make sure all required packages are loaded
by issuing the following terminal commands

```bash
    conda env create -f environment.yml
    source activate thylakoid
    jupyter-notebook
```
