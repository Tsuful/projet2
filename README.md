# Globe News 3D 🌍

Une interface web interactive avec un globe 3D filaire affichant les dernières nouvelles géolocalisées.

## Fonctionnalités

- 🌍 Globe 3D en mode filaire
- 🔄 Rotation automatique (désactivée pendant l'interaction)
- 👆 Drag pour tourner · Scroll pour zoomer
- 📍 50 marqueurs de news géolocalisés
- ⏰ Filtre: uniquement les news < 24h
- 📱 Responsive mobile

## Utilisation

Ouvrez `index.html` dans un navigateur.

Pour un vrai déploiement, servez le fichier via un serveur web local:

```bash
cd projet2
python3 -m http.server 8080
```

Puis ouvrez http://localhost:8080

## API News

Currently utilise des données mockées. Pour utiliser une vraie API:

1. Obtenez une clé API gratuite sur [GNews.io](https://gnews.io)
2. Remplacez `NEWS_DATA` par des appels API dans le fichier

## Tech

- Three.js (CDN)
- Vanilla JS
- Pas de build step requis
