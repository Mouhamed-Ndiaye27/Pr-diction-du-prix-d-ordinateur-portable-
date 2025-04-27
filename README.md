# Pr-diction-du-prix-d-ordinateur-portable-

Ce projet vise à développer un modèle de Machine Learning capable de prédire le prix des 
ordinateurs portables en fonction de leurs caractéristiques techniques. Les données utilisées 
proviennent d'un fichier CSV contenant des informations telles que la marque, le type 
d'ordinateur, la taille de l'écran, la RAM, le poids, la résolution d'écran, le processeur, la 
carte graphique, et le système d'exploitation.

1. Chargement et Nettoyage des Données : 
o Suppression des colonnes inutiles (ex : Unnamed : 0). 
o Conversion des colonnes Ram et Weight en types numériques. 
o Extraction des dimensions de l'écran (Width et Height) à partir de la colonne 
ScreenResolution.

2. Visualisation des Données : 
o Histogrammes pour la distribution des prix, de la taille d'écran et de la 
RAM. 
o Matrice de corrélation pour identifier les relations entre les 
caractéristiques numériques.

3. Préparation des Données : 
o Séparation des données en ensembles d'entraînement et de test. 
o Prétraitement des variables catégorielles avec OneHotEncoder. 
o Normalisation des variables numériques avec StandardScaler.

4. Modélisation : 
o Régression Linéaire : Utilisée comme modèle de base. 
o Random Forest : Modèle plus complexe pour capturer les relations non 
linéaires. 
o Évaluation des modèles avec les métriques MAE, RMSE et R².
 
5. Courbe d'Apprentissage : 
o Analyse de la performance du modèle Random Forest en fonction de la taille 
des données d'entraînement.
