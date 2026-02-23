# Wireframe : Dashboard - Mes Notes (dashboard.md)

## ZONE 1 : Header (Espace Privé)
- **Composant** : Logo
- **Contenu** : "Notepad"
- **Composant** : Navigation
- **Contenu** : "Mes Notes", "+ Nouvelle Note", "[Nom Profil] (Profil/Déconnexion)"

## ZONE 2 : Titre de Section
- **Composant** : Titre H1
- **Contenu** : "Mes Notes"
- **Composant** : Bouton Action
- **Contenu** : "+ Nouvelle Note"
- **Action** : Vers /notes/create

## ZONE 3 : Liste des Notes (Tableau ou Liste)
- **Composant** : En-têtes (Colonnes)
- **Contenu** : "Titre, Catégorie, Visibilité, Date, Actions"
- **Composant** : Lignes de Note (répétition)
    - **Titre** : "[Titre]"
    - **Badge Catégorie** : "[Catégorie]"
    - **Statut** : "[Publique / Privée]"
    - **Date** : "[DD/MM/YYYY]"
    - **Actions** : "Éditer (icône), Supprimer (icône)"
    - **Action Éditer** : Vers /notes/{id}/edit
    - **Action Supprimer** : Déclenche confirmation de suppression

## ZONE 4 : Pagination
- **Composant** : Liens Navigation
- **Contenu** : "Précédent, 1, 2, 3, Suivant"
