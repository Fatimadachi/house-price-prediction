# 🏠 Prédiction du prix des maisons — Californie

**Problème** : régression (prédire un prix en $)
**Données** : 20 640 quartiers, 8 caractéristiques (scikit-learn)
**Méthode** : comparaison de 3 modèles + train/test split (80/20)

## 📊 Résultats

| Modèle | RMSE | R² |
|---|---|---|
| Régression linéaire | 74 558 $ | 0.576 |
| Random Forest | 50 534 $ | 0.805 |
| **XGBoost** 🏆 | **44 981 $** | **0.846** |

## 🚀 Comment lancer
1. Ouvrir le notebook dans Google Colab
2. Exécuter les cellules dans l'ordre

## 🛠️ Outils
Python · Pandas · scikit-learn · XGBoost · Matplotlib
