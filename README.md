# Optimisation de Modèles de Régression pour la Prédiction de MPG

Ce projet compare différents modèles de régression pour prédire la consommation de carburant (MPG) des véhicules.

## Objectif

L'objectif principal est d'analyser et de comparer les performances de la régression linéaire, Ridge et Lasso pour prédire le MPG, en mettant l'accent sur l'optimisation des hyperparamètres et la sélection de variables. [cite: 38, 39]

## Fonctionnalités

* Chargement et prétraitement des données
* Implémentation de modèles de régression linéaire, Ridge et Lasso
* Optimisation du paramètre alpha (Ridge, Lasso) via validation croisée
* Visualisation des résultats (erreurs, importance des variables)
* Sauvegarde du meilleur modèle

## Technologies utilisées

* Python
* Scikit-learn
* Pandas
* Numpy
* Matplotlib, Seaborn

## Installation

1.  Clonez le dépôt :
    ```bash
    git clone <URL_DU_DEPOT>
    ```
2.  Installez les dépendances :
    ```bash
    pip install -r requirements.txt # Si vous avez un fichier requirements.txt
    ```
3.  Exécutez le notebook Jupyter :
    ```bash
    jupyter notebook build.ipynb
    ```

## Utilisation

Le notebook `build.ipynb` contient le code pour charger, prétraiter, modéliser et visualiser les données. Suivez les cellules du notebook pour reproduire l'analyse.

## Compétences démontrées

* Régression linéaire et régularisée (Ridge, Lasso)
* Optimisation d'hyperparamètres (alpha)
* Sélection de variables
* Analyse exploratoire des données
* Visualisation de données
* Python

## Améliorations futures

* Explorer d'autres modèles de régression (e.g., Elastic Net)
* Ajouter des métriques d'évaluation supplémentaires
* Créer une application web pour interagir avec le modèle

## Auteur

Fidèle Ledoux
