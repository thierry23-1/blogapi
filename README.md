﻿# Django API Project

## Introduction

Bienvenue dans notre projet Django API, développé avec Django Rest Framework. Ce guide vous expliquera comment installer, configurer et utiliser l'API pour gérer une liste d'utilisateurs et leurs articles de blog.

## Prérequis

- Python 3.x
- Docker
- Docker Compose
- Git

## Installation

### 1. Cloner le dépôt

Clonez le dépôt sur votre machine locale :

```bash
git clone <https://github.com/thierry23-1/blogapi.git>
cd blog_api
```
### 2. Créer et activer un environnement virtuel (optionnel)
Il est recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet :

```bash
python -m venv venv
source venv/bin/activate  # Sur Windows: venv\Scripts\activate
```
### 3. Installer les dépendances
Installez les dépendances nécessaires en utilisant le fichier requirements.txt :

```bash
pip install -r requirements.txt
Pour démarrer le serveur de développement :
```bash
python app.py
npm start
```

L'API sera disponible à l'adresse `http://127.0.0.1:8000`.

## Endpoints

- `GET /articles` : Récupère tous les articles de blog.
- `GET /articles/<id>` : Récupère un article de blog spécifique.
- `POST /articles` : Crée un nouvel article de blog.

## Autres
- `PUT /articles/<id>` : Met à jour un article de blog existant.
- `DELETE /articles/<id>` : Supprime un article de blog.

## Auteurs

- Feunang Fokoue Thierry Florian

```‣汢杯灡੩
