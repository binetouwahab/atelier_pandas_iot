# Atelier Pandas – Analyse de données IoT

## Présentation

Cet atelier a pour objectif de découvrir et de mettre en pratique la bibliothèque **Pandas** à travers l'analyse de données provenant de capteurs IoT.

Une entreprise possède plusieurs bâtiments équipés de capteurs qui collectent régulièrement différentes informations : température, humidité, pression, 
consommation énergétique, état du capteur, bâtiment, date et heure de mesure.

Les données sont préparées, nettoyées et analysées afin de pouvoir être utilisées ultérieurement dans un système de **Machine Learning** permettant
notamment de détecter des situations anormales.

##  Structure du projet

text
atelier_pandas_iot/
│
├── data/
│   └── mesures_capteurs.csv
│
├── notebooks/
│   └── atelier_pandas_iot.ipynb
│
├── exports/
│   ├── donnees_nettoyees.csv
│   └── donnees_nettoyees.json
│
└── README.md

##  Technologies utilisées

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

##  Contenu de l'atelier

L'atelier est organisé en plusieurs parties :

### Partie 1 – Series

* Création et manipulation de Series Pandas
* Gestion des index
* Accès aux valeurs

### Partie 2 – DataFrame

* Création d'un DataFrame à partir d'un dictionnaire
* Importation du fichier CSV
* Consultation des dimensions du DataFrame

### Partie 3 – Exploration

* Affichage des premières et dernières lignes
* Nombre de lignes et de colonnes
* Noms des colonnes
* Informations générales
* Statistiques descriptives

### Partie 4 – Sélection

* Sélection de colonnes
* Sélection de plusieurs colonnes
* Utilisation de `loc`
* Utilisation de `iloc`

### Partie 5 – Manipulation des colonnes

* Création de nouvelles colonnes
* Conversion de température
* Catégorisation des températures
* Renommage de colonnes
* Suppression de colonnes

### Partie 6 – Filtrage

* Filtrage selon la température
* Filtrage avec plusieurs conditions

### Partie 7 – Tri

* Tri croissant et décroissant
* Recherche des 10 températures les plus élevées
* Tri selon plusieurs colonnes

### Partie 8 – Analyse

* Consommation moyenne par bâtiment
* Statistiques de température
* Analyse de la consommation
* Température moyenne et maximale
* Identification du bâtiment consommant le plus
* Nombre d'alertes par bâtiment

### Partie 9 – Gestion des valeurs manquantes

* Détection des valeurs manquantes
* Calcul du taux de valeurs manquantes
* Affichage des lignes concernées
* Remplacement des valeurs manquantes par la moyenne, la médiane ou une valeur spécifique

### Partie 10 – Gestion des doublons

* Détection des doublons
* Affichage des doublons
* Suppression des doublons

### Partie 11 – Statistiques descriptives

* Minimum
* Maximum
* Moyenne
* Médiane
* Écart-type
* Nombre de valeurs
* Analyse de l'état des capteurs

### Partie 12 – Exportation

Les données nettoyées sont exportées dans deux formats :

* `exports/donnees_nettoyees.csv`
* `exports/donnees_nettoyees.json`

### Partie 13 – Bonus

Une fonctionnalité supplémentaire et pertinente peut être proposée afin d'améliorer l'analyse ou la visualisation des données.

##  Utilisation

1. Placer le fichier `mesures_capteurs.csv` dans le dossier `data/`.
2. Ouvrir le notebook :

```text
notebooks/atelier_pandas_iot.ipynb
```

3. Exécuter les cellules du notebook dans l'ordre.
4. Les fichiers nettoyés seront générés automatiquement dans le dossier `exports/`.

##  Objectifs pédagogiques

À la fin de l'atelier, les compétences suivantes sont mises en pratique :

* Manipuler des Series et DataFrames avec Pandas
* Importer et explorer un jeu de données
* Sélectionner et filtrer des données
* Trier et analyser des données
* Gérer les valeurs manquantes
* Supprimer les doublons
* Calculer des statistiques descriptives
* Exporter des données nettoyées
* Préparer des données pour une future utilisation en Machine Learning


