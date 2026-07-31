# Météo

Petite application météo en un seul fichier HTML (CSS et JS inclus). Saisissez une ville et affichez la température actuelle et le temps qu'il fait.

## Fonctionnalités

- Recherche d'une ville avec géocodage (Open-Meteo, sans clé API)
- Température actuelle et conditions météo traduites en français
- Gestion des erreurs (ville introuvable, problème réseau)
- Design sobre et responsive

## Utilisation

Ouvrez `index.html` dans un navigateur, ou déployez le dossier tel quel (statique).

## API

- Géocodage : `https://geocoding-api.open-meteo.com/v1/search?name=VILLE&count=1&language=fr`
- Météo : `https://api.open-meteo.com/v1/forecast?latitude=LAT&longitude=LON&current=temperature_2m,weather_code`
