# 🚢 Analyse de survie du Titanic

Projet complet d'analyse de données et de Machine Learning sur le célèbre dataset du Titanic.

## 🎯 Objectif

Analyser les données des 891 passagers du Titanic pour comprendre les facteurs de survie, puis comparer plusieurs modèles d'IA capables de prédire si un passager aurait survécu.

## 🛠️ Technologies utilisées

- **Python 3**
- **Pandas** — manipulation de données
- **Matplotlib** — visualisation
- **Scikit-learn** — Machine Learning classique
- **XGBoost** — Machine Learning avancé

## 📊 Analyses réalisées

- Exploration et nettoyage des données
- Taux de survie global : 38%
- Analyse par sexe : femmes 74% vs hommes 19%
- Analyse par classe : 1ère classe 63% vs 3ème classe 24%
- Visualisations graphiques (barres, courbes, camemberts)

## 🤖 Comparaison de 4 modèles prédictifs

| Modèle | Précision |
|--------|-----------|
| Régression logistique | 75,52% |
| Arbre de décision | 75,52% |
| Random Forest | 76,22% |
| **XGBoost** 🏆 | **76,92%** |

## 🔍 Analyse d'importance des variables

XGBoost a identifié les facteurs les plus déterminants :
- **Sexe : 74%** (variable la plus importante)
- **Classe sociale : 18%**
- **Âge : 4%**
- **Prix du billet : 4%**

## 📈 Résultats clés

Le sexe et la classe sociale étaient de loin les facteurs les plus déterminants pour la survie — l'IA l'a découvert automatiquement à partir des données.

## 👤 Auteur

**Benjamin Gravé** — Data Analyst Freelance
📍 Belgique | 💼 [LinkedIn](https://www.linkedin.com/in/benjamin-gravé-217a0517)
