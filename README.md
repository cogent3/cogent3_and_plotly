# Decoding genomes with cogent3 + Plotly

Source code demonsytrating the integration of Plotly visualisation capabilities into cogent3.

## Installation instructions

To run the notebook you need a Python installation. We expect most readers to be familiar with [conda](https://docs.anaconda.com/miniconda/miniconda-install/). We suggest you create a conda environment and activate it

```
$ conda create -n c3demo python=3.12
$ conda activate c3demo
```

Then install cogent3 with plotly dependencies as 
```
$ pip install "cogent3[extra]" ipykernel nbformat jupyter
```

We recommend using [VS Code](https://code.visualstudio.com) with the Python and Jupyter extensions for running the notebook.
