# Sitemap : Notepad — Application de Gestion de Notes

## Structure de Navigation

### Navigation Publique (visiteur non connecté)
- Lien vers la page publique des notes
- Liens Connexion / Inscription

### Navigation Privée (utilisateur connecté)
- Dashboard (Mes notes)
- Créer une note
- Déconnexion

---

## Arborescence Hiérarchique

```
[Accueil Public - /]
│   ↳ Liste des notes publiques (filtrables par catégorie / recherche)
│   ↳ Détail d'une note publique
│
├── [Authentification]
│   ├── /register  → Inscription
│   └── /login     → Connexion
│
├── [Espace Privé - Authentification requise]
│   ├── /notes           → Dashboard : liste de mes notes
│   ├── /notes/create    → Créer une note
│   ├── /notes/{id}      → Détail d'une note
│   ├── /notes/{id}/edit → Modifier une note
│   └── /notes/{id}      → Supprimer une note (action DELETE)
│
└── [Administration - Rôle admin uniquement]
    ├── Toutes les notes (lecture + suppression)
    └── Gestion des utilisateurs
```

---

## Règles de Navigation (SEO Structure)
- **Règle des 3 clics** : Toute note est accessible en max 2 clics depuis l'accueil.
- **Siloing** : Zone publique / Zone privée / Zone admin clairement séparées.
- **Menu principal** : 4 entrées max (Notes publiques, Connexion, Mon espace, Créer).
