# Sensor Selection for Angle of Arrival Estimation Based on the Two-Target Cramér-Rao Bound

[<img src="./icassp2023-acceptance-landscape-image.png" align="right" width="428px"/>](https://2023.ieeeicassp.org)
Notebook associated with our submission for the 2023 ICASSP.

## Viewing

The notebook can be viewed online by opening it in nbviewer or Google Colab. The integrated notebook viewer of GitHub cannot show the plot, but it will show everything else.

[![Open in nbviewer](https://img.shields.io/static/v1?label&message=Open+in+nbviewer&color=343433&style=for-the-badge&logo=jupyter)](https://nbviewer.org/github/CostasAK/icassp2023/blob/main/crb_sparse_sensing.ipynb)
[![Open in Colab](https://img.shields.io/static/v1?label&message=Open+in+Colab&color=097ABB&style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/CostasAK/icassp2023/blob/main/crb_sparse_sensing.ipynb)

## Usage

Tested using Pipenv and Jupyter in Visual Studio Code on Ubuntu 20.04.

1. `git clone` this repository and `cd` into the directory.
2. (optional) `export PIPENV_VENV_IN_PROJECT=1` to install Pipenv virtual environments into the current project folder.
3. `pipenv install`.
4. Open this folder in Visual Studio Code.
5. Install the workspace recommended extension.
6. Open `crb_sparse_sensing.ipynb`.

Alternatively, you can try and run a Jupyter server manually, or use Google Colab. Note that in Google Colab the errorbars on the last 2 plots might not be supported unless you update to a newer version of `scipy`.

[![Open in Colab](https://img.shields.io/static/v1?label&message=Open+in+Colab&color=097ABB&style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/CostasAK/icassp2023/blob/main/crb_sparse_sensing.ipynb)
