# **Machine Learning Supervisé pour la Santé**

##    **Problème à Résoudre**
Prédire le **risque de développer des douleurs lombaires** à partir de caractéristiques biomécaniques et physiques.  
Approche : Problème de **classification supervisée**.

##  **Étapes du Projet**
1. **Packages & Préparation** : Import des bibliothèques nécessaires.
2. **Exploration des Données** :
   - Importation et nettoyage.
   - Gestion des valeurs extrêmes.
   - Analyse descriptive.
3. **Corrélations & Statistiques** :
   - Visualisation des relations entre variables explicatives et cibles.
   - Création de matrices de corrélation.
4. **Modélisation & Évaluation** :
   - **Régression Logistique**.
   - **Random Forest**.
   - **XGBoost**.
5. **Visualisations** :
   - Courbes ROC.
   - Matrices de confusion.
   - Courbes de gains cumulés.


##  **Pourquoi ce Projet est Important**
Les douleurs lombaires touchent **4 personnes sur 5** en France au cours de leur vie. Ce projet propose des outils prédictifs basés sur le Machine Learning pour aider à la prévention des lombalgies.


##  **Résultats**
### **Modèles Étudiés** :
| Modèle               | Exactitude | AUC  |
|----------------------|------------|------|
| Régression Logistique | 77%        | 0,72 |
| Random Forest        | 78%        | 0,75 |
| XGBoost             | **80%**    | **0,78** |

### **Interprétations Clés** :
- Les courbes ROC montrent une meilleure performance pour XGBoost, confirmée par l'AUC.
