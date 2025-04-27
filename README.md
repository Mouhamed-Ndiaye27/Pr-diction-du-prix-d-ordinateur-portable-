# Pr-diction-du-prix-d-ordinateur-portable-

Ce projet vise à développer un modèle de Machine Learning capable de prédire le prix des 
ordinateurs portables en fonction de leurs caractéristiques techniques. Les données utilisées 
proviennent d'un fichier CSV contenant des informations telles que la marque, le type 
d'ordinateur, la taille de l'écran, la RAM, le poids, la résolution d'écran, le processeur, la 
carte graphique, et le système d'exploitation.

1. Chargement et Nettoyage des Données : 
- Suppression des colonnes inutiles (ex : Unnamed : 0). 
- Conversion des colonnes Ram et Weight en types numériques. 
- Extraction des dimensions de l'écran (Width et Height) à partir de la colonne 
ScreenResolution.

2. Visualisation des Données : 
- Histogrammes pour la distribution des prix, de la taille d'écran et de la 
RAM. 
- Matrice de corrélation pour identifier les relations entre les 
caractéristiques numériques.

3. Préparation des Données : 
- Séparation des données en ensembles d'entraînement et de test. 
- Prétraitement des variables catégorielles avec OneHotEncoder. 
- Normalisation des variables numériques avec StandardScaler.

4. Modélisation : 
- Régression Linéaire : Utilisée comme modèle de base. 
- Random Forest : Modèle plus complexe pour capturer les relations non 
linéaires. 
- Évaluation des modèles avec les métriques MAE, RMSE et R².
 
5. Courbe d'Apprentissage : 
- Analyse de la performance du modèle Random Forest en fonction de la taille 
des données d'entraînement.
