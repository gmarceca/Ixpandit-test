# Ixpandit-test
This is the analysis I developed for the ML test in Ixpandit.

The 4 requested points were developed on 4 Jupyter Notebooks using a miniconda environment.\
In the repository you can find the `environment.yml` file to install the libraries.\
Here are the instructions to download miniconda and create such an environment.

Due to the size of the `data.csv` file, it was not included in the repo. I assume that the evaluators
have such a file.

## Objective:
Given data collected from paid and unpaid loans, the goal is to predict whether a customer will pay or not.\
Below are the codes developed for the required items. The whole analysis was performed in 48hs as specified by the test requirements.

1. Exploratory data analysis:
    - Exploratory data analysis.ipynb
2. Development of a predictive model:
    - Data processing and Random Forest Classifier.ipynb
3. Optimization of hyper parameters:
    - Bayesian optimization for hyperparameters.ipynb
4. Natural language processing:
    - Word2Vec + K-means for titles feature extraction.ipynb

## Installation
<b># Installation of Miniconda from scratch</b>
- Get and install Miniconda:
    1. `cd your_project/` (Miniconda packages might require a significant space ~Gbs)
    1. `wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh`
    2. `bash Miniconda3-latest-Linux-x86_64.sh`
    3. `export PATH="/home/user/your_project/miniconda3/bin:$PATH"` (or where you have decided to install miniconda3)

<b># Create an environment</b>
- An environment file is provided for version compatibility.\
`conda env create -f environment.yml`
