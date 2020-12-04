# 2010_geopandas
Examples of geopandas.

Notebook 1: Basic geopnadas methods, and production of maps
Notebook 2: Add an inset map to a main map (e.g. for islands)

## Run on BinderHub

(Note: This may take a while to start if it has not been used for a while)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MichaelAllen1966/2010_geopandas/main)


## Set up the anaconda environment locally

Alternatively, to get the same libraries and versions I am using then you may recreate the environment. To create and activate the `geopandas` environment used:

To create environment. Navigate to the `binder` folder.

`conda env create -f environment.yml`

To activate environment:

`conda activate geopandas`

To deactivate:

`conda deactivate`

To update environment (from updated yml file):

`conda env update --prefix ./env --file environment.yml  --prune`

To remove the environemnt:

`conda env remove -n geopandas`
