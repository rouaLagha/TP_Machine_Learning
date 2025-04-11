# README - Travaux Pratiques : Modélisation et Prédiction avec des Algorithmes de Machine Learning

## Introduction

Ce projet comprend trois exercices pratiques sur la modélisation et la prédiction avec des algorithmes de machine learning. Les exercices sont axés sur la régression linéaire, les machines à vecteurs de support (SVM) et les forêts aléatoires (Random Forest). Chaque exercice utilise un ensemble de données spécifique pour prédire différents aspects en fonction de variables d'entrée.

## Exercices

### Exercice 1 : Prédiction de la Consommation Énergétique avec la Régression Linéaire

**Objectif** : Utiliser la régression linéaire pour prédire la consommation énergétique en fonction de différentes variables environnementales.

#### Étapes réalisées :
1. **Chargement du dataset** : Le dataset de consommation énergétique a été chargé à partir d'un fichier CSV.
2. **Exploration des données** : Les données ont été explorées pour identifier les variables, observer les distributions et détecter d’éventuelles valeurs manquantes.
3. **Prétraitement des données** :
   - Gestion des valeurs manquantes (suppression ou imputation).
   - Normalisation des caractéristiques (scaling) si nécessaire pour améliorer la performance du modèle.
4. **Division des données** : Les données ont été divisées en un ensemble d’entraînement (80%) et un ensemble de test (20%).
5. **Entraînement du modèle** : Un modèle de régression linéaire a été entraîné sur l'ensemble d'entraînement.
6. **Évaluation des performances** : Les performances du modèle ont été évaluées sur l'ensemble de test en utilisant les métriques suivantes :
   - Erreur quadratique moyenne (RMSE).
   - Coefficient de détermination (R²).
7. **Interprétation des résultats** : L'influence des variables environnementales sur la consommation énergétique a été analysée, permettant de tirer des conclusions sur les facteurs clés affectant la consommation d'énergie.

### Exercice 2 : Classification de Maladies avec un SVM

**Objectif** : Utiliser un SVM pour classifier différentes maladies en fonction de leurs caractéristiques médicales.

#### Étapes réalisées :
1. **Chargement du dataset** : Le dataset contenant des informations médicales sur les maladies a été chargé.
2. **Prétraitement des données** :
   - Encodage des variables catégorielles (ex. : transformation des variables textuelles en variables numériques) pour être compatible avec l’algorithme SVM.
3. **Division des données** : Les données ont été divisées en un ensemble d’entraînement (70%) et un ensemble de test (30%).
4. **Entraînement du modèle** : Un classificateur SVM a été entraîné sur l'ensemble d'entraînement.
5. **Évaluation des performances** : Les performances du modèle ont été évaluées en utilisant les métriques suivantes :
   - Exactitude (accuracy).
   - Précision et rappel.
6. **Visualisation des résultats** : Une visualisation a été réalisée pour examiner la capacité du modèle à distinguer les différentes classes de maladies et identifier les zones de confusion potentielles.

### Exercice 3 : Prédiction de la Durée de Vie des Produits avec un Random Forest

**Objectif** : Utiliser un modèle de Random Forest pour prédire la durée de vie des produits en fonction de leurs caractéristiques techniques.

#### Étapes réalisées :
1. **Chargement du dataset** : Le dataset de durée de vie des produits a été chargé pour commencer l’analyse.
2. **Exploration des données** : Les données ont été explorées pour identifier les variables et vérifier leur pertinence pour la prédiction.
3. **Division des données** : Les données ont été divisées en un ensemble d’entraînement (80%) et un ensemble de test (20%).
4. **Entraînement du modèle** : Un modèle de Random Forest a été entraîné sur l'ensemble d'entraînement.
5. **Évaluation des performances** : Les performances du modèle ont été évaluées à l'aide des métriques suivantes :
   - Erreur quadratique moyenne (RMSE).
   - Coefficient de détermination (R²).
6. **Analyse des caractéristiques importantes** : Les caractéristiques les plus importantes pour prédire la durée de vie des produits ont été identifiées, permettant d’interpréter les facteurs ayant un impact majeur sur la longévité des produits.

## Conclusion

Ces trois exercices pratiques ont permis de mettre en œuvre des algorithmes de machine learning pour la régression, la classification et la prédiction. Chaque exercice a permis de comprendre le processus de prétraitement des données, l'entraînement des modèles et l’évaluation des performances, avec une attention particulière portée à l’interprétation des résultats pour tirer des conclusions significatives.
