

<div align=center>
  
  ![Finding_Donors](https://github.com/BaraSedih11/finding_donors/assets/98843912/600353c1-08fe-4a41-854c-36d896a4952d)


   ![GitHub repo size](https://img.shields.io/github/repo-size/BaraSedih11/finding_donors) ![GitHub repo file count (file type)](https://img.shields.io/github/directory-file-count/BaraSedih11/finding_donors) [![Python Version](https://img.shields.io/badge/python-3.8-blue)](https://www.python.org/downloads/release/python-380/)
[![Pip Version](https://img.shields.io/badge/pip-21.0-orange)](https://pypi.org/project/pip/21.0/)
 ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/BaraSedih11/finding_donors/main)
[![Version](https://img.shields.io/badge/version-v1.0.0-blue)](https://github.com/BaraSedih11/finding_donors/releases/tag/v1.0.0)
[![Contributors](https://img.shields.io/github/contributors/BaraSedih11/finding_donors)](https://github.com/BaraSedih11/finding_donors/graphs/contributors)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/BaraSedih11/finding_donors)
  
</div>

This repository contains a training and prediction model, along with tuning and testing, to identify the best estimators and features for our dataset.

## Introduction
We explored three models and ultimately chose the Random Forest model, which proved to be the most suitable for our dataset. We then fine-tuned the hyperparameters to obtain the best estimators and identified the top 5 features. Finally, we trained a reduced model using these features.

## Contents

- `finding_donors.ipynb`: Jupyter Notebook containing the implementation of Random Forest using Python.
- `report.html`: An html page presenting the jupyter notebook.
- `README.md`: This file providing an overview of the repository.
- `census.csv`: This is the working dataset.


## Requirements
To run the code in the Jupyter Notebook, you need to have Python installed on your system along with the following libraries:

* NumPy
* pandas
* scikit-learn
* matplotlib
* seaborn
You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/BaraSedih11/finding_donors.git
```

2. Navigate to the repository directory:

```bash
cd finding_donors
```

3. Open and run the Jupyter Notebook `finding_donors.ipynb` using Jupyter Notebook or JupyterLab.

4. Follow along with the code and comments in the notebook to understand how Random Forest and training and tuning is implemented using Python.


## Acknowledgements

- [scikit-learn](https://scikit-learn.org/): The scikit-learn library for machine learning in Python.
- [NumPy](https://numpy.org/): The NumPy library for numerical computing in Python.
- [pandas](https://pandas.pydata.org/): The pandas library for data manipulation and analysis in Python.
- [matplotlib](https://matplotlib.org/): The matplotlib library for data visualization in Python.
- [seaborn](https://seaborn.pydata.org/): The seaborn library for data visualization in Python.


