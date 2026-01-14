# CLAUDE.MD

## Project Overview

Dashboard de surveillance des marchés crypto et macro pour un portefeuille 100% on-chain.

**Objectif** : Construire un tableau de bord React affichant les paramètres de marché clés à surveiller.

**Esthétique** : Terminal/sci-fi militaire inspiré de Canto.

**Mise à jour des données** : Manuelle, routine hebdomadaire prévue.

## Contexte Spécifique

- Analyse de marchés crypto et macro
- Portefeuille 100% on-chain
- **Contraintes** : Pas d'accès aux marchés traditionnels sauf via solutions on-chain ou Bitpanda
- **Privilégier les sources gratuites** quand possible
- Pas de backend pour l'instant (données en dur dans le code)

## Stack Technique

- **React** (JSX)
- **CSS vanilla** (style terminal/sci-fi)
- Pas de backend (données statiques dans le code pour l'instant)

## Règles de Travail (à appliquer systématiquement)

### Communication
- **Ne jamais supposer ou inventer d'information** : poser des questions si incertain
- **Ne pas générer de code sans accord explicite** : d'abord analyser et proposer une approche
- Rester factuel, neutre, professionnel
- Réponses structurées, sources citées
- Distinction claire entre faits et opinions/hypothèses

### Code
- Expliquer brièvement la logique du code si non évidente
- Suivre les conventions React et JSX standards
- Respecter l'esthétique terminal/sci-fi dans le CSS
- Code simple et maintenable

## Project Structure

```
/src
  /components     # Composants React réutilisables
  /data          # Données statiques (paramètres de marché)
  /styles        # CSS vanilla (thème terminal/sci-fi)
  App.jsx        # Composant principal
  index.js       # Point d'entrée
/public          # Assets statiques
```

## Références Esthétiques

- Style terminal/sci-fi militaire
- Inspiré de Canto
- Palette de couleurs : tons verts/cyan sur fond sombre typique des terminaux

## Notes Importantes

- Les données sont mises à jour manuellement (pas d'API en temps réel pour l'instant)
- Routine de mise à jour hebdomadaire prévue
- Focus sur la clarté et la lisibilité des métriques
- Privilégier les sources de données gratuites et on-chain
