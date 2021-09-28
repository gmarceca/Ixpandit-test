# Ixpandit-test
Este es el analysis que desarrolle para el test de ML de Ixpandit

Los 4 puntos pedidos fueron desarrollados en 4 Jupyter Notebooks usando un entorno de miniconda.\
En el repositorio se encuentra el archivo `environment.yml` para poder instalar las librerias.\
A continuacion las instrucciones para descargar miniconda y crear dicho entorno.

Debido al tamano del archivo `data.csv`, no fue incluido en el repo. Asumo que los evaluadores
cuentan con dicho archivo.

1. Análisis exploratorio de datos:
    - Exploratory data analysis.ipynb
2. Desarrollo de un modelo predictivo:
    - Data processing and Random Forest Classifier.ipynb
3. Optimización de hiper parámetros:
    - Bayesian optimization for hyperparameters.ipynb
4. Procesamiento de lenguaje natural:
    - Word2Vec + K-means for titles feature extraction.ipynb

## Instalacion
<b># Installation of Miniconda from scratch</b>
- Get and install Miniconda:
    1. `cd your_project/` (Miniconda packages might require a significant space ~Gbs)
    1. `wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh`
    2. `bash Miniconda3-latest-Linux-x86_64.sh`
    3. `export PATH="/home/user/your_project/miniconda3/bin:$PATH"` (or where you have decided to install miniconda3)

<b># Create an environment</b>
- An environment file is provided for version compatibility.\
`conda env create -f environment.yml`
