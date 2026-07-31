# Météo

Application météo en un seul fichier HTML (CSS et JS inclus). Saisissez une ville, cliquez sur la carte ou utilisez votre position pour afficher la météo.

## Fonctionnalités

- Recherche d'une ville avec géocodage (Open-Meteo, sans clé API)
- Carte interactive (Leaflet + OpenStreetMap) : marqueur sur la ville cherchée, clic n'importe où pour la météo locale
- Température actuelle, ressenti, humidité, vent, pression, précipitations
- Courbe des températures sur 24 h (SVG maison, sans dépendance) et prévisions sur 7 jours
- Gestion des erreurs (ville introuvable, géolocalisation refusée, problème réseau)
- Unités °C / °F, thème clair / sombre, recherches récentes et dernière ville mémorisées (localStorage)
- Design sobre et responsive

## Utilisation

Ouvrez `index.html` dans un navigateur, ou déployez le dossier tel quel (statique).

## API

- Géocodage : `https://geocoding-api.open-meteo.com/v1/search?name=VILLE&count=1&language=fr`
- Météo : `https://api.open-meteo.com/v1/forecast?latitude=LAT&longitude=LON&current=temperature_2m,weather_code`
