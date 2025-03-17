<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/sar2016/API-PredictionIRA">
    <img src="static/images/logo3.png" alt="Logo" width="100" height="100">
  </a>
  
  <h3 align="center">FASTAPI-IRA-PREDICTION-V2</h3>

  <p align="center">
    Une application FastAPI pour analyser et prédire les Infections Respiratoires Aiguës (IRA) à l'aide d'un modèle de Machine Learning.
    <br />
    <a href="https://github.com/sar2016/API-PredictionIRA"><strong>Explorer la documentation »</strong></a>
    <br />
    <br />
    <a href="#demo">Voir la Démo</a>
    ·
    <a href="#issues">Signaler un Bug</a>
    ·
    <a href="#contributing">Contribuer</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## 📜 Table des matières

- [À propos du projet](#-à-propos-du-projet)
- [Démarrage rapide](#-démarrage-rapide)
- [Installation](#-installation)
- [Structure du projet](#-structure-du-projet)
- [Utilisation](#-utilisation)
- [Contribuer](#-contribuer)
- [Contact](#-contact)
- [Licence](#-licence)

---

## 📌 À propos du projet

FASTAPI-IRA-PREDICTION-V2 est une API FastAPI conçue pour analyser et prédire les infections respiratoires aiguës en utilisant le modèle LightGBM. 

### 🛠️ Technologies utilisées

- **FastAPI** - Framework rapide pour les API avec Python
- **LightGBM** - Modèle de Machine Learning pour la classification et régression
- **Bootstrap** - Framework CSS pour un design moderne et réactif
- **Jinja2** - Moteur de templates pour les pages web

---

## 🚀 Démarrage rapide

Pour obtenir une copie locale et exécuter l'application, suivez ces étapes :

1. Clonez le dépôt
```bash
git clone https://github.com/sar2016/API-PredictionIRA.git
cd API-PredictionIRA
```
2. Installez les dépendances
```bash
pip install -r requirements.txt
```
3. Lancez l'application
```bash
uvicorn app2:app --reload
```
4. Accédez à l'application à `http://127.0.0.1:8000/`

---

## 📂 Structure du projet

```bash
API-PredictionIRA/
├── static/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   └── style.css
│   └── images/
│       ├── image.png
│       ├── logo.webp
│       ├── logo2.png
│       └── logo3.png
├── templates/
│   ├── homepage.html
│   └── prediction.html
├── venv/ (environnement virtuel)
├── app2.py
├── featuresExtract.py
├── lightgbm_model_ML_OK.pkl
├── requirements.txt
```

---

## 🏗️ Utilisation

L'application offre plusieurs fonctionnalités :
- Interface utilisateur responsive
- Prédiction des infections respiratoires aiguës
- Chargement et analyse des fichiers CSV
- API REST rapide avec documentation automatique Swagger

---

## 🤝 Contribuer

Les contributions sont les bienvenues !
1. Forkez le projet
2. Créez une branche (`git checkout -b feature-nouvelle-fonctionnalité`)
3. Commitez vos modifications (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez sur la branche (`git push origin feature-nouvelle-fonctionnalité`)
5. Ouvrez une Pull Request

---

## 📞 Contact

- **Nom :** Votre Nom
- **GitHub :** [Votre Profil](https://github.com/votre-utilisateur)
- **Email :** votre.email@example.com

---

## 📜 Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.
