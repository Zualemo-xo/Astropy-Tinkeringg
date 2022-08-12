# Jupyter Notebook Template
 <!--- https://github.com/gitpod-io/gitpod/issues/758 --->
Use this template for creating Jupyter notebooks compatible with Gitpod and local environments.

Once the Gitpod workspace has successfully loaded, it will install the most common dependencies used in a typical notebook.

## How to use

- Add your notebooks in the `./notebbook` folder.
- Open the notebooks and run the python code.

## Default dependencies

```
# Base ----------------------------------------
pandas>=1.1.4
numpy>=1.18.5
opencv-python>=4.1.2
matplotlib>=3.2.2
ipyleaflet>=0.14.0
sympy>=1.10.1

# Machine learning ----------------------------
sklearn
```
## Gitpod
You can use this command to tell the notebook server to allow your workspace location to access the API:

jupyter notebook --NotebookApp.allow_origin=\'$(gp url 8888)\'
