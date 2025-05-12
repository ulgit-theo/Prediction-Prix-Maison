# 📈 Prédiction des Prix des Maisons - Machine Learning avec Régression Linéaire

## 🗂️ Description du projet

Ce projet a pour objectif de prédire le prix des maisons à partir de diverses caractéristiques (superficie, nombre de chambres, localisation, etc.) en utilisant une approche de **régression linéaire**. Le modèle a été entraîné à partir d'un jeu de données réel, après une étape de **nettoyage**, de **visualisation**, de **sélection des variables pertinentes** et de **prétraitement des données**.

---

## 🧠 Objectifs

- Comprendre et appliquer les étapes d’un pipeline de machine learning supervisé.
- Utiliser un modèle de régression linéaire pour faire de la prédiction.
- Enregistrer et réutiliser un modèle entraîné avec `pickle`.
- Interpréter les résultats et évaluer les performances du modèle.

---

## 🔧 Technologies utilisées

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib & Seaborn (visualisation)  
- Scikit-learn (modélisation)  
- Pickle (sérialisation du modèle)

---


---

## 🔍 Étapes du projet

1. **Importation des données**
   - Chargement du dataset au format CSV.
2. **Exploration et nettoyage**
   - Gestion des valeurs manquantes.
   - Transformation des variables catégorielles.
   - Visualisation des corrélations.
3. **Prétraitement**
   - Normalisation ou standardisation des données.
   - Séparation en variables explicatives (features) et cible (target).
4. **Modélisation**
   - Régression linéaire avec Scikit-learn.
   - Séparation en jeux d'entraînement et de test.
   - Évaluation avec RMSE, MAE, R².
5. **Enregistrement du modèle**
   - Sauvegarde avec `pickle` pour une réutilisation future.

---


## 🚀 Utilisation

vous pouvez réutiliser le modèle en chargeant le fichier sauvegardé avec `pickle` et le réutiliser pour des prédictions futures. Notez que le modèle a été entraîné avec les données du dataset original, il est donc important de s'assurer que les données de test sont similaires en termes de distribution et de structure. voici un exemple de code pour réutiliser le modèle : 
```
import pickle

with open("models/linear_model.pkl", "rb") as f:
    model = pickle.load(f)

# Exemple de prédiction :
prix = model.predict([[valeur1, valeur2, ..., valeurN]])
```

**Cloner le projet**  
```bash
git clone https://github.com/ulgit-theo/Prediction-Prix-Maison.git
cd Prediction-Prix-Maison
```


📌 Auteurs
Toukam Kuate Ulrich Théo
Étudiant en cycle ingénieur informatique - 3IL

📬 Contact
Pour toute question, suggestion ou collaboration :
📧 kuatetheo2.0@gmail.com





