# Cahier des Charges : Notepad — Application de Gestion de Notes

## 1. Contexte & Enjeux

- **Pourquoi ce projet ?** : Permettre à des utilisateurs authentifiés de créer, organiser et partager des notes personnelles via une interface web. Une partie publique permet la consultation sans inscription.
- **Cible** :
  - **Utilisateurs inscrits** (rédacteurs, éditeurs) : créent et gèrent leurs notes.
  - **Administrateurs** : gèrent tous les utilisateurs et toutes les notes.
  - **Visiteurs anonymes** : consultent les notes publiques sans compte.
- **Tons & Style** : Professionnel, épuré, lisible. Interface sobre orientée productivité.

---

## 2. Besoins Fonctionnels

- **Besoin Métier** : Offrir un espace centralisé de prise de notes multi-utilisateurs avec contrôle d'accès par rôle (visiteur, éditeur, admin).

- **Fonctionnalités Clés** :
  - **Authentification** : Inscription, connexion, déconnexion sécurisées.
  - **Gestion des notes (CRUD)** : Créer, lire, modifier et supprimer ses propres notes.
  - **Catégorisation** : Associer une note à une catégorie pour l'organiser.
  - **Visibilité publique** : Afficher les notes marquées comme publiques sur une page accessible sans connexion.
  - **Contrôle d'accès par rôle** :
    - `visiteur` : lecture seule des notes publiques.
    - `éditeur` : gère ses propres notes, peut en ajouter.
    - `admin` : gère toutes les notes et tous les utilisateurs.
  - **Filtrage / Recherche** : Filtrer les notes publiques par catégorie ou mot-clé.
  - **Pagination** : Navigation paginée sur les listes de notes.

- **Contenus Indispensables** :
  - Liste des notes de l'utilisateur connecté (dashboard privé).
  - Détail d'une note (titre, contenu, catégorie, auteur, date).
  - Page publique listant les notes visibles par tous.
  - Formulaire de création / édition de note.
  - Gestion des catégories (au minimum : sélection lors de la création d'une note).

---

## 3. Contraintes

- **Deadline** : À définir avec le client.
- **Technique** :
  - Framework back-end : Laravel (PHP).
  - Base de données : MySQL.
  - Front-end : Blade templates + Vanilla JS / Alpine.js.
  - Pas de framework JS externe (React, Vue) sauf Alpine.js déjà intégré.
- **Langue** : Français (interface et documentation).
- **Sécurité** :
  - Authentification native Laravel (guards).
  - Autorisation via Policies / Gates (Spatie RBAC).
  - Protection CSRF sur tous les formulaires.
