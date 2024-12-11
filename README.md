# Machine Learning Water Leak Detection

## Installation
1. Clone the repository
2. Install the dependencies : `pip install -r requirements.txt`


Organisation du repository :

```
water-leak-detection-ml/
├── data/                # Données brutes et prétraitées
│   ├── raw/             # Données brutes (spectrogrammes, fichiers CSV, etc.)
│   ├── processed/       # Données prétraitées (features extraites, datasets prêts pour le ML)
│   ├── README.md        # Instructions pour organiser les données
├── notebooks/           # Jupyter Notebooks pour l'exploration et l'entraînement
│   ├── data_analysis.ipynb   # Analyse exploratoire des données
│   ├── feature_extraction.ipynb # Extraction des caractéristiques des spectrogrammes
│   ├── model_training.ipynb     # Entraînement des modèles
├── src/                 # Code source pour les scripts et modules Python
│   ├── data_loader.py   # Chargement et gestion des données
│   ├── preprocessing.py # Prétraitement et extraction des features
│   ├── models.py        # Implémentation des modèles ML
│   ├── inference.py     # Script pour tester les modèles en conditions réelles
├── results/             # Résultats des modèles (logs, métriques, courbes)
│   ├── logs/            # Journaux des entraînements
│   ├── models/          # Modèles entraînés sauvegardés
│   ├── reports/         # Rapports de performance (PDF, markdown)
├── requirements.txt     # Liste des dépendances Python
├── README.md            # Documentation principale du projet
└── LICENSE              # Licence du projet (si applicable)

```