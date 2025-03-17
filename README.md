#  FASTAPI-IRA-PREDICTION-V2

Une application FastAPI pour analyser et prédire Infections respiratoires aiguës "IRA" basée sur un modèle Machine Learning.

##  Démo

https://github.com/sar2016/API-PredictionIRA

## Technologies utilisées

- Python (FastAPI)
- HTML, CSS, JavaScript (avec Bootstrap)
- LightGBM pour le modèle de Machine Learning

##  Installation

###  Cloner le dépôt
```bash
git clone https://github.com/sar2016/API-PredictionIRA
cd FASTAPI-IRA-PREDICTION-V2
```

### Installer les dépendances
```bash
pip install -r requirements.txt
```

### Lancer l'application
```bash
uvicorn app2:app --reload
```

##  Fonctionnalités

-  Interface utilisateur avec Bootstrap
-  Prédiction avec un modèle LightGBM
-  Chargement et analyse de fichiers CSV
-  API rapide et légère avec FastAPI

##  Structure du projet

```bash
📂 FASTAPI-IRA-PREDICTION-V2
├── 📂 static
│   ├── 📂 css
│   │   ├── bootstrap.min.css
│   │   ├── style.css
│   ├── 📂 images
│   │   ├── image.png
│   │   ├── logo.webp
│   │   ├── logo2.png
│   │   ├── logo3.png
├── 📂 templates
│   ├── homepage.html
│   ├── prediction.html
├── 📂 venv (environnement virtuel)
├── __pycache__
├── app2.py
├── departement.txt
├── df_Test_Indust.csv
├── featuresExtract.py
├── lightgbm_model_ML_OK.pkl
├── listeFeatures.txt
├── requirements.txt
```

##  Auteurs

- **Nom:** groupe 2 -M2I
- **GitHub:** lien de notre répertoire

## Licence

Ce projet est sous licence...
