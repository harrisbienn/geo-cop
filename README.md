# geo-cop
Repository for the geospatial analysis community of practice.

## Initializing a geospatial stack
Constructing a dedicated geospatial stack in python is a common pain point that can be readily resolved by using the following resources to create and install necessary stack elements.

### Option A: Use the packages specifications defined in geo.yml
1. Open a terminal or command prompt and navigate to the directory where the YAML file is located. Then run the following command to create a new environment:
`conda env create -f geo.yaml python=3.9`
2. Once the environment is created, activate it by running the following command:
`conda activate geo`
3. You can check if the required libraries are installed by running the following command within the activated environment:
`conda list` 

### Option B: Use gishub with additional dependencies
In a terminal, run the following commands in order[^1]:

1. `conda create -n geo python=3.9`
2. `conda activate geo`
3. `conda install geopandas`
4. `conda install -c conda-forge mamba`
5. `mamba install -c conda-forge geospatial`
6. `pip install cookiecutter`

[^1] More detailed guidance can be found on [gishub.org](https://geospatial.gishub.org/installation/)