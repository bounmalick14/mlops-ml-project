
# Projet MLOps - Classification Iris

## 1. Présentation

Ce projet consiste à mettre en place un pipeline de Machine Learning pour classifier les fleurs du jeu de données Iris.

Il comprend :
- Le chargement des données.
- Le prétraitement des données.
- L'entraînement d'un modèle de régression logistique.
- L'évaluation des performances.
- La sauvegarde du modèle et des métriques.
- Les tests automatisés.

## 2. Technologies utilisées

- Python
- Pandas
- Scikit-learn
- PyYAML
- Joblib
- Pytest

## 3. Installation

Créer un environnement virtuel :

```bash
python -m venv .venv
```

Activer l'environnement sous Windows :

```powershell
.venv\Scripts\Activate.ps1
```

Installer les dépendances :

```bash
python -m pip install -r requirements.txt
```

## 4. Entraînement du modèle

```bash
python scripts/train.py
```

## 5. Évaluation du modèle

```bash
python scripts/evaluate.py
```

## 6. Exécution des tests

```bash
python -m pytest -v
```

## 7. Résultats

Les fichiers générés sont enregistrés dans le dossier `artifacts/` :
- `model.joblib` : modèle entraîné.
- `metrics.json` : métriques d'évaluation.
- `confusion_matrix.png` : l'image de la matrice de confusion
- `report.json` : rapport d'évaluation.
