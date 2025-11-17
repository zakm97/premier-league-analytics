# ⚽ Premier League Analytics Project (Zakaria)

Projet complet de Data Engineering + Data Science sur la Premier League, couvrant :

- Ingestion des données StatsBomb Open Data
- Transformation & Data Quality
- Analyse exploratoire (EDA) : distributions, corrélations, normalité, ACP
- Feature engineering football : expected goals, form ratings, Elo, home advantage
- Modélisation : prédiction de score / victoire / expected goals
- Dashboard final interactif (Streamlit ou Power BI)
- Documentation complète

## 🎯 Objectifs pédagogiques
- Reproduire le workflow complet d'un projet Data en entreprise
- Comprendre TOUT ce que l’on fait, pas juste exécuter
- Utiliser de vraies données football (Premier League)
- Travailler sur un projet long (3–4 semaines) avec sprints

## 📂 Structure
- data/raw : JSON StatsBomb bruts
- data/staging : datasets nettoyés
- data/final : features finales pour ML
- notebooks : EDA, modelling, tests
- src/ingestion : scripts d’ingestion
- src/features : feature engineering
- src/models : modèles de machine learning
- reports : documentation

## ⚙️ Installation

### Créer l’environnement
```bash
conda create -n football python=3.11
conda activate football
pip install -r requirements.txt
