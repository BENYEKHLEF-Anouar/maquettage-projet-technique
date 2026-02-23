# Wireframe : Détail d'une Note (show.md)

## ZONE 1 : Header
- **Composant** : Navigation standard (Publique ou Privée selon contexte)

## ZONE 2 : En-tête de la Note
- **Composant** : Titre H1
- **Contenu** : "[Titre de la note]"
- **Composant** : Métadonnées
- **Contenu** : "Auteur : [Nom] | Date : [Date] | Catégorie : [Badge]"

## ZONE 3 : Corps de la Note
- **Composant** : Contenu Texte
- **Contenu** : "[Texte intégral de la note]"

## ZONE 4 : Actions Contextuelles
- **Composant** : Si Propriétaire
- **Contenu** : Boutons "Modifier", "Supprimer"
- **Action Modifier** : Vers /notes/{id}/edit
- **Composant** : Si Visiteur
- **Contenu** : "← Voir d'autres notes publiques"
- **Action** : Vers /public
