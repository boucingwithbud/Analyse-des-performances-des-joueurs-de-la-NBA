# Analyse des performances des joueurs de la NBA

Ce projet porte sur l'analyse des performances des joueurs de la NBA à partir de leurs statistiques individuelles.

L'objectif est d'identifier différents profils de joueurs en utilisant des méthodes d'apprentissage non supervisé. L'analyse repose principalement sur une réduction de dimensionnalité suivie d'une étape de clustering avec K-Means.

## Objectif

Les joueurs peuvent avoir des profils très différents : certains sont principalement orientés vers le scoring, d'autres vers la création, le rebond ou encore la polyvalence.

L'objectif de ce projet est donc de répondre à la question suivante :

> Peut-on regrouper automatiquement les joueurs de la NBA selon leurs caractéristiques statistiques ?

Pour cela, plusieurs variables décrivant les performances des joueurs sont analysées afin de faire ressortir les principales différences entre les profils.

## Méthode

L'analyse est réalisée en plusieurs étapes.

### Exploration des données

Dans un premier temps, les données sont explorées afin de comprendre les différentes variables disponibles et leur distribution.

Cette étape permet notamment d'identifier les variables pertinentes pour caractériser les performances des joueurs et de préparer les données pour les étapes suivantes.

### Réduction de dimensionnalité

Les données comportant plusieurs variables, une réduction de dimensionnalité est réalisée afin de faciliter leur analyse et leur représentation.

Une FAMD (Factor Analysis of Mixed Data) est utilisée pour prendre en compte les différentes variables présentes dans le jeu de données et représenter les joueurs dans un espace de dimension réduite.

Cette représentation permet également de mieux visualiser les relations entre les joueurs et les variables.

### Clustering

Les données obtenues après la réduction de dimensionnalité sont ensuite utilisées avec l'algorithme K-Means.

Le but est de regrouper les joueurs présentant des caractéristiques similaires et d'obtenir plusieurs groupes correspondant à différents profils statistiques.

Les groupes obtenus sont ensuite analysés afin de comprendre les principales caractéristiques qui les différencient.

## Technologies utilisées

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Prince

## Structure du projet

```text
Analyse-des-performances-des-joueurs-de-la-NBA/
│
├── Dimensionnalité_Clustering.ipynb
└── README.md
