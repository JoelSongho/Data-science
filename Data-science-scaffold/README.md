# 📚 Parcours Data Science — Suivi & Portfolio

Ce dépôt contient **ton apprentissage Data Science sur 3 mois (80 % pratique)**.
Il est structuré pour t’aider à **travailler proprement**, **versionner chaque jour** et **construire un portfolio** visible.

## 🗂️ Structure
```
Data-science/
├── data/         # jeux de données (petits CSV/XLSX utiles aux notebooks)
├── notebooks/    # notebooks Jupyter par semaine/module
├── scripts/      # scripts .py réutilisables (cleaning, utils, etc.)
└── reports/      # exports (images, HTML, PDF) et livrables
```

## 🗓️ Programme (rappel rapide)
- **Mois 1** : Python, Pandas, DataViz, Statistiques
- **Mois 2** : Préprocessing, Feature Engineering, Régression/Classification, Validation
- **Mois 3** : NLP, Clustering, Déploiement (Streamlit), Portfolio

## 🚀 Démarrage
1. Crée un environnement (ex. conda) et installe les dépendances :  
   ```bash
   conda create -n ds-env python=3.10 -y
   conda activate ds-env
   pip install -r requirements.txt
   ```
2. Place tes jeux de données dans `data/` et tes notebooks dans `notebooks/`.
3. Versionne **chaque fin de journée** :
   ```bash
   git add .
   git commit -m "Jour X : résumé des travaux (ex: EDA + visualisations)"
   git push origin main
   ```

## ✅ Bonnes pratiques
- Garde les **petits datasets** dans `data/`. Pour de gros fichiers, ajoute-les au `.gitignore`.
- Nomme tes notebooks clairement : `notebooks/sem2_01_eda_superstore.ipynb`
- Un notebook propre = **titre, objectifs, code commenté, conclusions**.
- Mets à jour ce README avec une **liste de tes travaux** (ci-dessous).

## 🧾 Journal de bord (à compléter)
- **Sem1** : Python — ...
- **Sem2** : Pandas / Nettoyage — ...
- **Sem3** : Visualisation — ...
- **Sem4** : Statistiques — ...
- **Sem5–8** : ML — ...
- **Sem9–12** : NLP, Clustering, Déploiement, Portfolio — ...

Bon apprentissage ! 💪
