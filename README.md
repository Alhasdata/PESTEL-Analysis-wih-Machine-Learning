# PESTEL Analysis with Machine Learning

Implemented a non supervised algorithm (KMeans) with python and Sklearn in order to propose groups of countries according to several indicators for **international poultry meat trade**.

## Data Pre-processing

Determined the indicators to consider then collected and cleaned data related from [FAOSTAT](https://www.fao.org/faostat/en/) and [World bank open data](https://donnees.banquemondiale.org/).
- 2 macro-economic indicators that provide information on the country's wealth: **GDP per capita** and **GDP per capita growth**.
- 2 socio-economic indicators : **Average population growth** and the **Political stability** of the country.
- 2 indicators related to food availability : **Imports quantity related to the product**.
- 2 criteria that provide information on the **Continent** and M**embership of the European Union**.

## Data Exploration

Used a Principal Component Analysis to explore and understand data.

**PCA** Model with sklearn.

<img alt="MySQL" width="80%" src="./data/pca.png" style="padding-right:10px;" />

## Clustering

Used Kmeans algorithm to classify.

**KMeans** Model with sklearn.

<img alt="MySQL" width="50%" src="./data/kmeans_.png" style="padding-right:10px;" />
