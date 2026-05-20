# Rewake Brand Guidelines

Guides d'utilisation de l'identité visuelle pour la marque **Rewake**.

---

## 🎯 Principes de Base

### Ton & Personnalité
- **Professionnel** : Design épuré et moderne
- **Innovant** : Approche technique et avant-gardiste
- **Accessible** : Lisible et compréhensible par tous
- **Fiable** : Cohérent et reconnaissable

---

## 🎨 Couleurs

### Palette Principale

| Couleur | Code Hex | Tailwind | Utilisation |
|---------|----------|---------|-------------|
| **Emerald Primary** | `#19534F` ou `#006045` | `emerald-800` | Couleur de marque principale |
| Emerald Light | `#10B981` | `emerald-500` | Accents, boutons, liens |
| Emerald Dark | `#002C22` | `emerald-950` | Textes sur fonds clairs |
| Emerald Subtle | `#D1FAE5` | `emerald-100` | Fonds, survols |

### Palette Neutre

| Couleur | Code Hex | Tailwind | Utilisation |
|---------|----------|---------|-------------|
| Blanc | `#FFFFFF` | `white` | Arrière-plans, texte |
| Gris Clair | `#F9FAFB` | `gray-50` | Fonds |
| Gris Moyen | `#6B7280` | `gray-500` | Texte secondaire |
| Noir | `#111827` | `gray-900` | Texte principal |

### Règles d'Utilisation
- **Couleur principale** : Utiliser `#19534F` (extraite du logo) pour l'identité de marque
- **Contraste** : Toujours vérifier le contraste texte/fond (WCAG AA minimum)
- **Combinaisons autorisées** :
  - `#19534F` + Blanc ✅
  - `#19534F` + `emerald-100` ✅
  - `#19534F` + `gray-50` ✅
  - Éviter : `#19534F` + `emerald-900` (manque de contraste) ❌

---

## 🔤 Typographie

### Police Principale
- **Nom** : Geist Sans
- **Source** : [Vercel Geist](https://vercel.com/font)
- **Poids disponibles** : 400, 500, 600, 700

### Hiérarchie

| Éléments | Taille | Poids | Couleur | Exemple |
|----------|--------|-------|---------|---------|
| H1 | `4xl` (2.25rem) | 700 | `gray-900` | Titres de page |
| H2 | `3xl` (1.875rem) | 600 | `gray-900` | Sections |
| H3 | `2xl` (1.5rem) | 600 | `#19534F` | Sous-sections |
| H4 | `xl` (1.25rem) | 500 | `gray-900` | |
| Body | `base` (1rem) | 400 | `gray-700` | Texte principal |
| Small | `sm` (0.875rem) | 400 | `gray-500` | Légendes |
| Lien | `base` (1rem) | 500 | `#10B981` | Liens cliquables |

---

## 🏷️ Logo

### Fichiers Disponibles
- `/logos/logo_rewake.svg` — Logo principal (couleur `#19534F`)
- `/logos/logo_rewake_white.svg` — Version blanche pour fonds sombres
- `/logos/logo_rewake_black.svg` — Version noire pour fonds clairs

### Tailles Recommandées
| Contexte | Taille (largeur) | Fichier |
|----------|------------------|---------|
| Favicon | 32x32px | `favicon.svg` |
| Mobile (Header) | 120px | `logo_rewake.svg` |
| Desktop (Header) | 180px | `logo_rewake.svg` |
| Hero Section | 250px | `logo_rewake.svg` |
| Footer | 120px | `logo_rewake_white.svg` |

### Utilisation Incorrecte ❌
- Étirer ou déformer le logo
- Changer la couleur du logo (sauf versions blanche/noire prévues)
- Placer sur un fond de même couleur (manque de contraste)

---

## 🖼️ Exemples d'Application

[Application interne](https://app.rewake.fr)
[Page de redirection SAV](https://sav.rewake.fr)

---

## ✅ Checklist de Validation

Avant de publier :
- [ ] Adaptation mobile testée
- [ ] Couleur principale `#19534F` ou `emerald-900` utilisée correctement
- [ ] Cohérence avec les exemples existants (app.rewake.fr, sav.rewake.fr)

---

## 📎 Annexes

### Outils Recommandés
- **Couleurs** : [Tailwind Color Picker](https://tailwindcss.com/docs/customizing-colors)
- **Polices** : [Google Fonts - Inter](https://fonts.google.com/specimen/Inter) (fallback)
- **Accessibilité** : [a11y Color Contrast](https://color.a11y.com/)

### Contacts
- **Design Team** : [paul@rewake.fr](paul@rewake.fr)
- **Développement** : [alban.catoire@rewake.fr](alban.catoire@rewake.fr)

---

*Dernière mise à jour : 20 mai 2026 | Version : 0.1.0*
