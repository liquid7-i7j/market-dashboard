# Crypto Market Dashboard

Dashboard de surveillance des marchés crypto et macro avec esthétique terminal/sci-fi militaire.

## Structure du projet

```
/
├── index.html          # Fichier HTML unique avec React chargé via CDN
├── CLAUDE.MD           # Documentation projet pour IA
├── README.md           # Ce fichier
└── docs/
    └── parameters.md   # Liste des paramètres suivis
```

## Utilisation

1. Ouvrir `index.html` dans un navigateur moderne
2. Le dashboard s'affiche avec les données configurées

## Mise à jour des données

Les données sont mises à jour manuellement directement dans `index.html` (section `marketData`).

**Routine recommandée** : hebdomadaire

## Stack technique

- React 18 (via CDN)
- CSS vanilla (intégré dans index.html)
- Babel Standalone pour transpilation JSX
- Pas de build process

## Esthétique

Style terminal/sci-fi militaire inspiré de Canto :
- Palette : verts/cyan sur fond sombre
- Font : monospace (Courier New)
- Interface type terminal

## Documentation

Voir `docs/parameters.md` pour la liste des paramètres suivis et leurs sources.
