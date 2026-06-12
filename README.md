# Formation Flask

Projet d'apprentissage du framework web **Flask** (Python), réalisé dans le cadre de ma formation en développement. L'objectif était de comprendre les bases de Flask : créer un serveur web, définir des routes et afficher des pages HTML avec un système de gabarit (templates).

## Ce que fait l'application

Une petite application web composée de deux pages :
- **Page d'accueil** (`/`) : affiche un titre de bienvenue
- **Page À propos** (`/about/`) : page de présentation

Les pages utilisent un gabarit commun (`base.html`) grâce au moteur de templates **Jinja2**, et sont mises en forme avec **Bootstrap 5**.

## Notions travaillées

- Création d'une application Flask et lancement d'un serveur de développement
- Définition de routes avec le décorateur `@app.route()`
- Affichage de pages HTML avec `render_template()`
- Héritage de templates avec Jinja2 (`{% extends %}`, `{% block %}`)
- Intégration de Bootstrap via CDN

## Technologies utilisées

- **Python 3.12**
- **Flask**
- **Jinja2** (moteur de templates)
- **Bootstrap 5** (mise en forme)

## Structure du projet

```
formation_flask/
├── app.py                  # Application Flask (routes)
└── templates/
    ├── base.html           # Gabarit commun (head, Bootstrap)
    ├── index.html          # Page d'accueil
    └── about.html          # Page À propos
```

## Installation et lancement

1. Cloner le dépôt
   ```bash
   git clone https://github.com/ada0508/formation_flask.git
   cd formation_flask
   ```
2. Installer Flask
   ```bash
   pip install flask
   ```
3. Lancer l'application
   ```bash
   python app.py
   ```
4. Ouvrir dans le navigateur : `http://127.0.0.1:5000`
   - Page À propos : `http://127.0.0.1:5000/about/`

Pour arrêter le serveur : `Ctrl + C`.

## Améliorations possibles

- Ajouter une barre de navigation entre les pages
- Enrichir le contenu des pages
- Connecter une base de données avec Flask-SQLAlchemy

## Autrice

**Ndeye Adama Diop** — Étudiante en Informatique Appliquée à la Gestion des Entreprises
[github.com/ada0508](https://github.com/ada0508)
