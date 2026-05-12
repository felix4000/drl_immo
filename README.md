# DRL Immobilier — Site Web

Site vitrine de DRL Immobilier, branche immobilière de DRL Participations.

## Déploiement sur GitHub Pages

1. Crée un dépôt GitHub (ex: `drl-immobilier`)
2. Upload `index.html` à la racine du dépôt
3. Va dans **Settings → Pages**
4. Source : `Deploy from a branch` → Branch : `main` / `root`
5. Ton site sera live sur : `https://ton-username.github.io/drl-immobilier`

## Structure

```
/
└── index.html       ← Site complet (HTML + CSS + JS en un seul fichier)
```

## Personnalisation rapide

| Élément | Où modifier dans le HTML |
|---|---|
| Adresse / contact | Section `#contact`, `.contact-detail-value` |
| Photo hero | `.hero-img` → remplacer l'URL Unsplash par ta propre photo |
| Textes | Directement dans les balises HTML |
| Couleurs | Variables CSS au début du `<style>` |

## Pour ajouter ton logo

Dans la balise `<nav>`, remplace le bloc `.nav-logo-text` par :
```html
<img src="logo.png" alt="DRL Immobilier" style="height: 40px;" />
```
Et upload `logo.png` au même niveau que `index.html`.

---

© 2026 DRL Participations
