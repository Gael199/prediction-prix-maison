# Prédicteur de Prix de Maison

Cette application web de Machine Learning permet de prédire le prix d’une maison en fonction de deux caractéristiques :
- la **surface**
- le **nombre de pièces**

- ## Démo en ligne

Tester l’application ici :  
[Accéder à l’application]([https://ton-app.streamlit.app](https://prediction-prix-maison-apmhu3qhuh34e24yhlm6jh.streamlit.app/))

Ce projet présente un workflow simple de Machine Learning de bout en bout :
- création d’un petit jeu de données
- entraînement d’un modèle de **régression linéaire**
- sauvegarde du modèle avec **pickle**
- création d’une interface interactive avec **Streamlit**

## Aperçu du projet

L’objectif de ce projet est d’estimer le prix d’une maison à partir de :
- **la surface (sq ft)**
- **le nombre de pièces**

Le modèle est entraîné sur un petit jeu de données, puis intégré dans une application Streamlit permettant à l’utilisateur de saisir des informations et d’obtenir instantanément une prédiction.

## Fonctionnalités

- Entraînement d’un modèle de prédiction du prix des maisons
- Sauvegarde du modèle au format `.pkl`
- Interface utilisateur interactive avec Streamlit
- Prédiction en temps réel
- Projet simple et adapté à un portfolio débutant en Machine Learning

## Technologies utilisées

- Python
- scikit-learn
- NumPy
- pickle
- Streamlit

## Structure du projet

```bash
House-Price-Predictor/
│
├── create_dataset.ipynb
├── Eudes_prediction_House.ipynb
├── House_Price_Model.pkl
└── README.md
