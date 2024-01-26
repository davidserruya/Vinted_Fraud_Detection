# Vinted_Fraud_Detection

Ce projet vise à détecter les fraudes dans les annonces de sneakers sur la plateforme Vinted en utilisant des techniques de machine learning comme l'approche supervisée ou semi-supervisée.

## Objectif Initial

Dans cette première phase, l'étude se concentre exclusivement sur la paire Adidas Campus 00s.

## Prérequis

La présence de [Python](https://www.python.org/) sur la machine est requise.

## Configuration de l'Environnement

Après avoir cloné ce projet, vous devez exécuter les commandes suivantes :

```bash

# Installer la bibliothèque pandas
$ pip install pandas
# Installer la bibliothèque matplotlib
$ pip install matplotlib
# Installer la bibliothèque sklearn
$ pip install sklearn
# Installer la bibliothèque seaborn
$ pip install seaborn
# Installer la bibliothèque numpy
$ pip install numpy
# Installer la bibliothèque unicodedata
$ pip install unicodedata
# Installer la bibliothèque emoji
$ pip install emoji
```

## Dossiers

1. **Creation_Dataset**
   - `Scraping_Vinted.ipynb`: Notebook pour le scraping des annonces Vinted.
   - `Build_Dataset.ipynb`: Notebook pour la construction du dataset en ajoutant des variables grâce à des fonctions personnalisées.
   - `Functions.ipynb`: Notebook contenant l'ensemble des fonctions appelées dans `build_dataset.ipynb`.

2. **Data_Exploration**
   - `Exploratory_Data_Analysis.ipynb`: Notebook pour l'exploration des données.
   - `Statistical_Analysis.ipynb`: Notebook pour les analyses statistiques des données.

3. **Data_Preprocessing**
   - `Data_Preprocessing.ipynb`: Notebook pour le prétraitement des données.

4. **Semi_Supervised_Model**
   - `Self_Training_Classifier.ipynb`: Notebook pour tester une approche semi-supervisée avec le Self Training Classifier utilisant Random Forest.

5. **Supervised_Model**
   - `Decision_Tree_Random_Forest.ipynb`: Notebook pour l'entraînement des modèles de Decision Tree et Random Forest avec optimisation utilisant GridSearch.
   - `XGBoost.ipynb`: Notebook pour l'entraînement du modèle XGBoost avec optimisation utilisant GridSearch.

## Contributors

- David Serruya
- Yona Bitton
