# geo-cop
Repository for the geospatial analysis community of practice.

### Initializing a geospatial stack
Constructing a dedicated geospatial stack in python is a common pain point that can be readily resolved by using the following resources to create and install necessary stack elements. In a terminal, run the following commands in order:

* `conda create -n geo python=3.9`
* `conda activate geo`
* `conda install geopandas`
* `conda install -c conda-forge mamba`
* `mamba install -c conda-forge geospatial`
* `pip install cookiecutter`

More detailed guidance can be found on [gishub.org](https://geospatial.gishub.org/installation/)