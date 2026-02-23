# Wireframe : Accueil Public (index.md)

## ZONE 1 : Header (Navigation)
- **Composant** : Logo / Nom du site
- **Contenu** : "Notepad"
- **Action** : Vers /
- **Composant** : Liens Navigation
- **Contenu** : "Notes Publiques", "Se connecter", "S'inscrire"
- **Action** : Vers /public, /login, /register

## ZONE 2 : Hero (Proposition de Valeur)
- **Composant** : Titre H1
- **Contenu** : "Notes partagées — Explorez les idées de la communauté"
- **Composant** : Sous-titre
- **Contenu** : "Parcourez des notes organisées, filtrées et partagées par vos pairs."
- **Composant** : Bouton CTA
- **Contenu** : "Créer mon compte — Commencer à rédiger"
- **Action** : Vers /register

## ZONE 3 : Barre de Recherche & Filtres
- **Composant** : Champ Recherche
- **Contenu** : "Rechercher par mot-clé..."
- **Composant** : Liste déroulante Catégories
- **Contenu** : "[Toutes les catégories], Travail, Études, Personnel..."

## ZONE 4 : Grille de Notes
- **Composant** : Cartes de Notes (répétition)
    - **Titre** : "[Titre de la note]"
    - **Extrait** : "[3 premières lignes du contenu...]"
    - **Badge** : "[Catégorie]"
    - **Auteur** : "Par [Nom Utilisateur]"
    - **Lien** : "Lire la suite"
    - **Action** : Vers /notes/{id} (vue publique)

## ZONE 5 : Footer
- **Composant** : Liens secondaires
- **Contenu** : "À propos, Contact, Mentions légales"
