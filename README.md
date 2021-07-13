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
