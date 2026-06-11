# y0uls.github.io

> Portfolio personnel — sysadmin & side-project builder.

Site statique hébergé via **GitHub Pages**, construit en HTML/CSS vanilla (pas de framework, pas de bundler).

## Structure

```
.
├── index.html   # Page principale
├── style.css    # Styles (CSS custom properties, grid, responsive)
└── README.md
```

## Déploiement

Le site est automatiquement publié via GitHub Pages à chaque push sur `main`.

Aller dans **Settings → Pages → Source → Deploy from branch → main / root**.

## Personnalisation

- **Projets** : éditer les `<article class="card">` dans `index.html`
- **Stack** : section `#stack`, modifier les listes
- **Couleur d'accent** : variable `--accent` dans `:root` (défaut `#00d4aa`)
- **Liens GitHub / npm** : remplacer les `href` dans les cards

## Licence

MIT
