# Composition : Éditeur de Note (comp-editor.md)

## Atoms
- **A1: Logo** : Identique index.
- **A2: Nav-Link** : Identique index (Lien retour).
- **A3: Title-H1** : Identique index.
- **A5: Btn-Primary** : Identique index (Enregistrer).
- **A15: Form-Label** : Texte Slate-700 SM Medium.
- **A16: Input-Text** : Bordure Slate-200, focus Indigo-500.
- **A17: Form-Textarea** : Identique input, hauteur libre.
- **A18: Form-Select** : Identique input.
- **A19: Form-Checkbox** : Carré Indigo-500.
- **A20: Link-Cancel** : Texte Slate-500, hover Slate-700.

## Molecules
- **M10: Form-Field** : A15 (Label) + A16/A17/A18 (Input).
- **M11: Editor-Actions** : A5 (Enregistrer) + A20 (Annuler).

## Organisms
- **Header** : M6 (ou M1 simplifié avec lien retour).
- **Form** : Liste de M10 + M11.
