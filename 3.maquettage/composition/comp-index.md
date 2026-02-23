# Composition : Accueil Public (comp-index.md)

## Atoms (Composants de base)
- **A1: Logo** : Texte "Notepad" avec style spécifique (Indigo-600).
- **A2: Nav-Link** : Lien simple, Slate-600, hover Slate-900.
- **A3: Title-H1** : Grand titre gras, Slate-900.
- **A4: Subtitle** : Texte Slate-500, taille LG.
- **A5: Btn-Primary** : Bouton fond Indigo-500, texte blanc, arrondi LG.
- **A6: Input-Search** : Champ texte avec icône loupe (facultatif), Slate-200 border.
- **A7: Select-Category** : Liste déroulante stylisée.
- **A8: Badge-Category** : Petit label Indigo-100 / Indigo-800, arrondi full.
- **A9: Link-More** : Lien "Lire la suite", souligné au hover, Indigo-600.
- **A10: Text-Excerpt** : Texte Slate-600, 3 lignes max.

## Molecules (Assemblages)
- **M1: Navbar-Public** : A1 (Logo) + Liste de A2 (Nav-Links) + A5 (Btn-Primary pour inscription).
- **M2: Hero-Section** : A3 (H1) + A4 (Subtitle) + A5 (CTA).
- **M3: Filter-Bar** : A6 (Search) + A7 (Category Select).
- **M4: Note-Card-Public** : A3 (H3 Titre) + A8 (Badge) + A10 (Excerpt) + A9 (Link).
- **M5: Footer-Simple** : Liste de A2 (Nav-Links secondaires) + copyright.

## Organisms (Pages/Sections complexes)
- **Header** : M1.
- **Main Content** : M2 + M3 + Grille de M4.
- **Footer** : M5.
