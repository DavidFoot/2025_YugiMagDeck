# 🎴 CardDeck Portfolio API – Flask Edition

Bienvenue dans **CardDeck**, un projet portfolio basé sur Flask, visant à démontrer mes compétences techniques pour des recruteurs et projets professionnels.

---

## 🎯 Objectif

Créer une API REST en Python avec Flask pour gérer une bibliothèque de cartes de jeu (Pokémon, Magic, Yu-Gi-Oh!) et des decks personnalisés. Ce projet met en avant :

- Python (POO, bonnes pratiques)
- API REST avec Flask
- ORM SQLAlchemy
- Tests Pytest
- CI/CD GitHub Actions
- Docker & Docker Compose

---

## 📦 Fonctionnalités

- 📁 Gestion des cartes (CRUD)
- 🎮 Création de decks
- 🔎 Filtres, tri, catégories (Pokémon, Magic…)
- 🔐 Authentification (optionnelle)
- 📚 API REST documentée
- 🧪 Tests automatisés
- 🐳 Déploiement Dockerisé

---

## 🧱 Stack technique

| Composant       | Choix                       |
|-----------------|-----------------------------|
| Langage         | Python 3.10                 |
| Framework       | Flask (Blueprint / RESTful) |
| ORM             | SQLAlchemy                  |
| BDD             | PostgreSQL / SQLite         |
| Tests           | Pytest                      |
| CI/CD           | GitHub Actions              |
| Dockerisation   | Docker + Docker Compose     |

---

## 🚀 Lancement local

```bash
git clone https://github.com/DavidFoot/2025_YugiMagDeck
cd 2025_YugiMagDeck

# Env virtuel
python -m venv venv
source venv/bin/activate

# Dépendances
pip install -r requirements.txt

# Lancer l'app
flask run
