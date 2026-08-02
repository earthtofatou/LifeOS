# LifeOS

Application web fullstack de gestion de vie personnelle — un "système d'exploitation" centralisant tâches, calendrier, finances, habitudes, objectifs, journal, études et documents en une seule plateforme cohérente.

## À propos

LifeOS est né d'un constat simple : la gestion du quotidien est aujourd'hui éclatée entre plusieurs outils (Notion pour les notes, Todoist pour les tâches, Google Calendar pour le planning, une app séparée pour le budget). LifeOS regroupe ces usages dans une interface unique, pensée pour être rapide, sobre et cohérente.

Ce projet est développé en solo, en partant de zéro sur l'ensemble de la stack, avec pour objectif de démontrer une maîtrise réelle du développement fullstack moderne (React / Node.js / Express / MongoDB) à travers un produit complet plutôt qu'une série d'exercices isolés.

## Fonctionnalités

- **Authentification** — inscription, connexion, gestion de profil, routes protégées
- **Dashboard** — vue d'ensemble personnalisée du quotidien
- **Tâches** — gestion complète avec priorités, deadlines, sous-tâches, tags et filtres
- **Calendrier** — vues jour / semaine / mois, synchronisées avec les tâches
- **Emploi du temps** — grille hebdomadaire personnalisable
- **Finances** — suivi des revenus et dépenses, budgets par catégorie, visualisation graphique
- **Habitudes** — suivi de fréquence et de séries (streaks)
- **Objectifs** — suivi de progression sur le court, moyen et long terme
- **Journal** — entrées personnelles avec suivi d'humeur
- **Documents** — stockage et organisation de fichiers
- **Notifications** — rappels et alertes in-app
- **Études** — suivi des cours, notes, examens et moyennes

## Stack technique

**Frontend**
- React
- React Router
- Axios
- Context API
- Tailwind CSS

**Backend**
- Node.js
- Express.js
- MongoDB / Mongoose

**Authentification & sécurité**
- JWT (JSON Web Token)
- bcrypt

**Gestion de fichiers**
- Multer

## Architecture

Le projet suit une architecture MVC (Model-View-Controller) des deux côtés :

```
frontend/
  src/
    pages/        # Pages de l'application
    components/   # Composants réutilisables
    hooks/        # Hooks personnalisés
    services/     # Appels API
    contexts/      # Contextes React (état global)
    layouts/       # Structures de mise en page

backend/
  routes/         # Définition des routes API
  controllers/    # Logique métier des routes
  models/         # Schémas Mongoose
  middlewares/    # Middlewares (auth, gestion d'erreurs, etc.)
  services/       # Logique réutilisable côté serveur
  utils/          # Fonctions utilitaires
  config/         # Configuration (base de données, variables d'environnement)
```

## Statut du projet

Projet en développement actif. Version en cours : V1 (fonctionnalités cœur avant extensions futures : Pomodoro, notes Markdown, synchronisation cloud, application mobile, fonctionnalités IA).

## Installation

Instructions à venir une fois le socle backend et frontend en place.

## Licence

À définir.
