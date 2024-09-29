[![CI/CD](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/CI_CD.yml/badge.svg)](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/CI_CD.yml) [![Install](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/install.yml) [![Format](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/format.yml) [![Lint](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/lint.yml) [![Test](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/Fennie_miniproject4/actions/workflows/test.yml)


# IDS706_Fennie_Miniproject4
## Fennie's GitHub Actions Matrix with Python using the Pandas Descriptive Statistics Report

The purpose of miniproject 3 is to create a GitHub Actions workflow that will test at least three different version of Python. Doing checks for portability, backwards compatability interoperability.


Pandas Decriptive Report for Russian Equipment Losses (since the start of the war)\
Data Source - Kaggle: Russia Ukraine War 2022\
URL: https://www.kaggle.com/datasets/piterfm/2022-ukraine-russian-war?select=russia_losses_equipment.csv

Core Files are:
* `Jupyter notebook`
* `library.py`
* `test_library.py` & `test_main.py`
* `requirements.txt`
* `CI/CD pipeline`
* `Makefile`
* `README.md`

The execution of the `GitHub Actions` matrix for the different versions of Python can be found in the .yml `workflows` files. A screenshot has been provided below for convenience:

<img width="577" alt="matrix" src="https://github.com/user-attachments/assets/8838108b-144c-4c41-a3d2-25896bde4e50">


The notebook `main_notebook.ipynb` is the result of the report, but below are some graphics of the summary statistics data visualization.

### Summary Statistics of the Russian Equipment Losses
<img width="1036" alt="summary_stats" src="https://github.com/user-attachments/assets/5225f53c-066a-46ed-88ef-c84dbe1cf1f6">

### Data Visualization of the Russian Equipment Losses
![main_ground_losses](https://github.com/user-attachments/assets/d7ced2c7-fa23-44bf-9734-9e674e0ec029)