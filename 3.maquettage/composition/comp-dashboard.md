# Composition : Dashboard (comp-dashboard.md)

## Atoms (Composants de base)
- **A1: Logo** : Identique index.
- **A2: Nav-Link** : Identique index.
- **A5: Btn-Primary** : Identique index.
- **A8: Badge-Category** : Identique index.
- **A11: Badge-Visibility** : Badge vert (Public) ou gris (Privé).
- **A12: Btn-Icon-Action** : Petit bouton rond avec icone (Slate-200 border).
- **A13: Table-Header** : Cellule TH Slate-50, texte Slate-500 XS bold uppercase.
- **A14: Pagination-Link** : Carré blanc, border Slate-200, hover bg-Slate-50.

## Molecules (Assemblages)
- **M6: Navbar-Private** : A1 + Liste A2 + Avatar/Profil (dropdown).
- **M7: Dashboard-Title** : A3 (H1) + A5 (+ Nouvelle Note).
- **M8: Note-Table-Row** : Ligne TR avec Titre, A8 (Category), A11 (Visibility), Date, et A12 x2 (Actions).
- **M9: Pagination-Bar** : Suite de A14.

## Organisms
- **Header** : M6.
- **Main** : M7 + Table de M8 + M9.
