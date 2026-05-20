# Rewake Branding

Les ressources de design et guidelines pour l'identité visuelle de **Rewake**.

---

## 🎨 Identité Visuelle

### Police
- **Primaire**: [Geist Sans](https://vercel.com/font) (police par défaut Next.js)
  - Utilisée pour tout le texte : titres, corps, UI

### Couleurs
- **Primaire**: `emerald` (Tailwind CSS)
  - `emerald-900` : `#004F3B` (couleur principale)
  - Palette complète : `emerald-50` à `emerald-950`

---

## 📁 Structure

```
Branding/
├── logos/          # Logos (SVG, PNG, variantes)
├── favicons/       # Icônes
└── guidelines.md   # Règles d'utilisation
```

---

## 📖 Guidelines

Voir [guidelines.md](./guidelines.md) pour les règles détaillées :
- Utilisation du logo (tailles, espacement, variantes)
- Hiérarchie typographique
- Combinaisons de couleurs autorisées
- Exemples d'application

---

## 🛠 Utilisation

**Utiliser en CSS/JSX**
   ```jsx
   <h1 className="text-emerald-500 font-sans">Rewake</h1>
   ```

---

## 🔗 Ressources Externes

- [Tailwind Color Docs](https://tailwindcss.com/docs/colors)
- [Geist Font](https://vercel.com/font)
