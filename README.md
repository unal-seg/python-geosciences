## Geology coding

### Environment settings

Create a python conda environment with full anaconda packages and aditional ones listed in requirements.txt

- conda create --name segpy python=3.8 anaconda
- pip install nb_conda_kernels
- conda activate segpy
- python -m ipykernel install --user --name segpy
- pip install -r requirements.txt

### Notebooks

- 00-intro.ipynb - Introduction to python with examples in geological contexts
- 01-functions.ipynb - Introduction to functions and use in geological equation modeling

### 00-intro.ipynb

### 01-functions.ipynb

### 02-data-visualization.ipynb

### 03-visualizing-dems.ipynb

Data wrangling and visualization of Digital elevation models

1. Using numpy, imageio and pandas to transform DEM data from a tif file to a npy array and then to a pandas dataframe
2. Using matplotlib and interactive ipywidgets to plot data both static and interactively

<img src="demo-gifs/03-dems.gif" width="70%"/>
