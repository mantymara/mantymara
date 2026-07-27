# SomaPro – Plateforme de gestion académique

Plateforme web de gestion académique permettant aux établissements d'enseignement de gérer les utilisateurs, les cours, les évaluations, les inscriptions et le suivi pédagogique à travers une interface moderne et intuitive.

## 🎯 Contexte

Ce projet a été développé dans le cadre d'une plateforme de gestion académique destinée aux établissements d'enseignement. Il répond au besoin de centraliser l'administration scolaire, la gestion des apprenants, des enseignants, des cours et du suivi pédagogique dans une seule application.

L'objectif est d'offrir une solution évolutive permettant d'améliorer l'organisation des établissements et de faciliter les échanges entre les différents acteurs (administrateurs, responsables académiques, enseignants, apprenants et parents).

## ✨ Fonctionnalités

- Authentification sécurisée avec gestion des rôles
- Gestion des établissements et institutions
- Gestion des départements, filières et spécialités
- Gestion des classes et groupes
- Gestion des cours, modules et séquences
- Gestion des ressources pédagogiques
- Gestion des inscriptions des apprenants
- Gestion des sessions de formation
- Suivi de la progression des apprenants
- Gestion des évaluations et quiz
- Tableau de bord avec statistiques

## 🛠️ Stack technique

| Côté | Technologies |
|------|-------------|
| Frontend | Angular, TypeScript, Angular Material, RxJS |
| Backend | Python, Django, Django REST Framework |
| Base de données | PostgreSQL |
| Authentification | JWT |
| Outils | Git, GitHub, Postman |
| Déploiement | Docker |

## 🧠 Ce que ce projet démontre

- Développement d'une API REST avec Django REST Framework
- Conception d'une architecture Frontend Angular modulaire
- Gestion de l'authentification JWT
- Gestion des rôles et permissions
- Intégration Frontend / Backend
- Conception et modélisation d'une base de données PostgreSQL
- Développement de composants Angular réutilisables
- Travail collaboratif avec Git et GitHub

## 🚀 Installation

```bash
# Cloner le dépôt
git clone https://github.com/mantymara/somapro.git

# Backend
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
# Linux / macOS
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

```bash
# Frontend
cd frontend
npm install
ng serve
```

L'application sera disponible sur :
- Frontend : `http://localhost:4200`
- Backend : `http://localhost:8000`

## 📸 Démo

À venir. Vous pouvez consulter les principales fonctionnalités via les captures d'écran présentes dans le dépôt.

## 📄 Licence

Projet présenté à des fins de démonstration et de portfolio.
