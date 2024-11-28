# Cours_Machine-learning
## Prédiction du diabète avec SVM et Random Forest
## Table des matières
- [Description du projet](#descriptionduprojet)
- [Technoogies utilisées](#technologiesutilisées)
- [Données](#données)
- [Méthodologie](#méthodologie)
- [Résultats](#résultats)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Contributors](#contributeurs)

### Description du projet
Ce projet vise à prédire la probabilité qu'une personne soit atteinte de diabète en se basant sur un ensemble de données médicales. Nous utilisons deux algorithmes de machine learning :
**SVM** : pour classifier les données en fonction de leur hyperplan optimal.
**Random Forest** : pour exploiter la puissance d'un ensemble d'arbres de décision.


### Technologies utilisées
- **Langage** : Python 3.1.1.9
- **Bibliothèques Principales** :
- **pandas** : pour le traitement des données.
- **numpy** : pour les calculs numériques.
- **matplotlib** et **seaborn** : pour la visualisation des données.
- **Scikit-learn**: pour l'implémentation des modèles SVM et Random Forest.
### Données
| Variable                        | Description                              |
|---------------------------------|------------------------------------------|
| `Pregnancies`                   | Nombre de grossesses                     |
| `Glucose`                       | Taux de glucose dans le sang             |
| `BloodPressure`                 | Pression artérielle                      |
| `SkinThickness`                 | Épaisseur de la peau (peau)             |
| `Insulin`                       | Taux d'insuline                          |
| `BMI`                           | Indice de masse corporelle (IMC)        |
| `DiabetesPedigreeFunction`      | Fonction de prédisposition au diabète   |
| `Age`                           | Âge                      |
| `Outcome`                       | 1 = diabétique, 0 = non diabétique        |

###  Source des données
Les données utilisées proviennent de [Kaggle - Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).

### Méthodologie
1. **Prétraitement des données** :
   - Gestion des valeurs manquantes
   - Normalisation et mise à l'échelle
2. **Exploration et visualisation des données** :
   - Analyse des corrélations
3. **Construction des modèles** :
   - Implémentation de Random Forest et SVM
   - Validation croisée 
4. **Évaluation des performances** :
   - Matrice de confusion
     
### Résultats
#### Random Forest :


#### SVM :
- **Précision avec paramètres pas défaut** : 0.7922
- **Précision du modèle avec le noyau rbf** et **C**=100.0  : 0.7597
- **Précision du modèle avec le noyau rbf** et **C**=1000.0  : 0.7078
- **Précision du modèle avec un noyau linéaire** et **C**=1.0 : 0.8247
- **Précision de l'ensemble d'entraînement** : 0,7638


   


