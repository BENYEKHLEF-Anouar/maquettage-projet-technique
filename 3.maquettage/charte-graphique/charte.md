# Charte Graphique : Notepad

Ce document définit les standards visuels et les tokens de design pour l'application Notepad.

## 🎨 Palette de Couleurs

L'identité visuelle de Notepad repose sur une palette sobre et professionnelle, favorisant la lisibilité et la concentration.

### 1. Couleur Primaire (Teal / Cyan)
Utilisée pour les actions principales, l'identité de marque et les éléments interactifs.
- **Base (500)** : `#17A2B8` (hsl(188, 78%, 41%))
### 1. Palette de Couleurs

| Rôle | Couleur | Hexadécimal | Usage |
| :--- | :--- | :--- | :--- |
| **Primaire** | Royal Blue | `#0449AE` | Boutons, Liens actifs, Éléments de marque |
| **Primaire (Light)** | Blue Light | `#EBF2FC` | Fonds de badges, survol |
| **Neutre (Fond)** | Slate 50 | `#F8FAFC` | Couleur d'arrière-plan principale |
| **Neutre (Texte)** | Slate 800 | `#1E293B` | Titres et texte important |
| **Success** | Emerald 500 | `#10B981` | Messages de succès, Badges positifs |
| **Error** | Red 500 | `#EF4444` | Erreurs, Suppressions, Alertes.
| **Warning** | Amber 500 | `#f59e0b` | Attention.
| **Info** | Blue 500 | `#3b82f6` | Information.

---

## typography Typographie

- **Font Family** : `Inter, sans-serif` (Google Fonts)
- **Usage** :
  - **Titres (h1-h6)** : Font-weight 600 ou 700. Slate-800.
  - **Corps de texte** : Font-weight 400 ou 500. Slate-800 ou Slate-950.
  - **Labels / Petits textes** : Slate-500.

---

## 💎 Composants UI (Directives)

- **Radii (Bordures)** : `rounded-lg` (8px) par défaut pour les boutons et cartes.
- **Shadows (Ombres)** : `shadow-sm` pour les éléments interactifs légers, `shadow-md` pour les modales/dropdowns.
- **Borders** : `border-slate-200` (subtil).

---

## 🛠️ Stack Technique Frontend
- **Framework** : Tailwind CSS v3.
- **Composants** : Preline UI (Navigation, Dropdowns).
- **Icônes** : Lucide Icons ou icônes SVG intégrées.
