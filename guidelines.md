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

| Couleur | Code Hex | Variable CSS | Utilisation |
|---------|----------|--------------|-------------|
| **Primary** | `#19534f` | `--color-primary` | Couleur de marque principale |
| Primary Hover | `#006045` | `--color-primary-hover` | Survol des boutons/liens |
| Primary Foreground | `#FFFFFF` | `--color-primary-foreground` | Texte sur fond primaire |
| **Success** | `#00a63e` | `--color-success` | Actions réussies |
| Success Hover | `#008236` | `--color-success-hover` | Survol |
| Success Foreground | `#FFFFFF` | `--color-success-foreground` | Texte sur fond succès |
| **Destructive** | `#ef4444` | `--color-destructive` | Actions dangereuses |
| Destructive Hover | `#dc2626` | `--color-destructive-hover` | Survol |
| Destructive Foreground | `#FFFFFF` | `--color-destructive-foreground` | Texte sur fond destructif |

### Palette Neutre (Light Mode)

| Couleur | Code Hex | Variable CSS | Utilisation |
|---------|----------|--------------|-------------|
| Background | `#FFFFFF` | `--color-background` | Arrière-plan principal |
| Foreground | `#0f172a` | `--color-foreground` | Texte principal |
| Card | `#FFFFFF` | `--color-card` | Fonds des cartes |
| Card Foreground | `#0f172a` | `--color-card-foreground` | Texte dans les cartes |
| Secondary | `#f1f5f9` | `--color-secondary` | Boutons secondaires |
| Secondary Foreground | `#0f172a` | `--color-secondary-foreground` | Texte sur secondaire |
| Muted | `#f1f5f9` | `--color-muted` | Éléments discrèts |
| Muted Foreground | `#64748b` | `--color-muted-foreground` | Texte secondaire |
| Accent | `#e2e8f0` | `--color-accent` | Accents subtils |
| Accent Foreground | `#0f172a` | `--color-accent-foreground` | Texte sur accent |
| Border | `#e2e8f0` | `--color-border` | Bordures |
| Input | `#f8fafc` | `--color-input` | Champs de saisie |
| Ring | `#059669` | `--color-ring` | Contours focus |

### Palette Neutre (Dark Mode)

| Couleur | Code Hex | Variable CSS | Utilisation |
|---------|----------|--------------|-------------|
| Background | `#0f172a` | `--color-background` | Arrière-plan principal |
| Foreground | `#f1f5f9` | `--color-foreground` | Texte principal |
| Card | `#1e293b` | `--color-card` | Fonds des cartes |
| Card Foreground | `#f1f5f9` | `--color-card-foreground` | Texte dans les cartes |
| Secondary | `#334155` | `--color-secondary` | Boutons secondaires |
| Secondary Foreground | `#f1f5f9` | `--color-secondary-foreground` | Texte sur secondaire |
| Muted | `#334155` | `--color-muted` | Éléments discrèts |
| Muted Foreground | `#94a3b8` | `--color-muted-foreground` | Texte secondaire |
| Accent | `#475569` | `--color-accent` | Accents subtils |
| Accent Foreground | `#f1f5f9` | `--color-accent-foreground` | Texte sur accent |
| Border | `#334155` | `--color-border` | Bordures |
| Input | `#1d293d` | `--color-input` | Champs de saisie |
| Ring | `#10b981` | `--color-ring` | Contours focus |

### Rayons

| Variable | Valeur | Utilisation |
|----------|--------|-------------|
| `--radius-sm` | `calc(var(--radius) - 4px)` | Petits rayons |
| `--radius-md` | `calc(var(--radius) - 2px)` | Rayons moyens |
| `--radius-lg` | `var(--radius)` | Grands rayons |
| `--radius-xl` | `calc(var(--radius) + 4px)` | Rayons extra-larges |

**Rayon de base**: `0.5rem`

### Règles d'Utilisation
- **Couleur principale** : Utiliser `--color-primary` (`#19534f`) pour l'identité de marque
- **Contraste** : Toujours vérifier le contraste texte/fond (WCAG AA minimum)
- **Combinaisons autorisées** :
  - `--color-primary` + `--color-primary-foreground` ✅
  - `--color-primary` + `--color-background` ✅
  - `--color-primary` + `--color-secondary` ✅
  - Éviter : `--color-primary` + `--color-destructive` (conflit visuel) ❌
- **Variables CSS** : Toujours utiliser les variables (`--color-*`) plutôt que les codes hex direct

---

## 🔤 Typographie

### Police Principale
- **Nom** : Roboto
- **Source** : [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto)
- **Poids disponibles** : 300, 400, 500, 700, 900

### Hiérarchie

| Éléments | Taille | Poids | Police | Couleur | Exemple |
|----------|--------|-------|--------|---------|---------|
| H1 | `4xl` (2.25rem) | 700 | Roboto | `--color-foreground` | Titres de page |
| H2 | `3xl` (1.875rem) | 600 | Roboto | `--color-foreground` | Sections |
| H3 | `2xl` (1.5rem) | 600 | Roboto | `--color-primary` | Sous-sections |
| H4 | `xl` (1.25rem) | 500 | Roboto | `--color-foreground` | |
| Body | `base` (1rem) | 400 | Roboto | `--color-muted-foreground` | Texte principal |
| Small | `sm` (0.875rem) | 400 | Roboto | `--color-muted-foreground` | Légendes |
| Lien | `base` (1rem) | 500 | Roboto | `--color-primary` | Liens cliquables |
| Code | `sm` (0.875rem) | 400 | Roboto Mono | `--color-muted-foreground` | Extraits de code |

### Polices
- **Principale**: Roboto (tout le texte standard)
- **Code**: Roboto Mono (pour les extraits de code et éléments monospace)

### Espacements
Utiliser les classes Tailwind v4 standard : `p-4`, `gap-2`, `m-1`, etc.

### Breakpoints
Utiliser les breakpoints Tailwind v4 standard : `sm:`, `md:`, `lg:`, `xl:`, `2xl:`

---

## 🏷️ Logo

### Fichiers Disponibles
- `/logos/logo_rewake.svg` — Logo principal (couleur `#006045`)
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
- [ ] Couleur principale `--color-primary` (`#006045`) utilisée correctement
- [ ] Variables CSS (`--color-*`) utilisées plutôt que codes hex
- [ ] Cohérence avec les exemples existants (app.rewake.fr, sav.rewake.fr)

---

## 📎 Annexes

### Outils Recommandés
- **Couleurs** : [Tailwind Color Picker](https://tailwindcss.com/docs/customizing-colors)
- **Polices** : [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto)
- **Accessibilité** : [a11y Color Contrast](https://color.a11y.com/)

### Contacts
- **Design Team** : [paul@rewake.fr](paul@rewake.fr)
- **Développement** : [alban.catoire@rewake.fr](alban.catoire@rewake.fr)

---

*Dernière mise à jour : 12 juin 2026 | Version : 0.2.0*
