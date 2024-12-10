# Carte des Transporteurs Bus et Tram en Île-de-France 2024

Carte interactive présentant les différents transporteurs exploitant des lignes de bus et de tramway en Île-de-France, basée sur les données de validation 2024.

## Fonctionnalités

- 🚌 Visualisation par groupes de transporteurs
- 📊 Basé sur les données de validation par commune
- 🔍 Popups informatifs détaillés :
  - Population de la commune
  - Transporteur principal

## Données

Les données utilisées proviennent d'IDFM (Île-de-France Mobilités) et reflètent la situation en Octobre 2024.

## Accès à la carte

📍 [Voir la carte interactive](https://bixente-san.github.io/Cartes-transporteurs-bus-IDF-2024/)

## Méthodologie

### Groupes de transporteurs
Les opérateurs sont regroupés en 5 catégories principales :
- **Francilité**
- **Keolis**
- **RC** (RATP Cap IDF)
- **RATP**
- **Transdev**

  **Remarque**: les transporteurs RATP et RC (Ratp CAP IDF) partagent une couleur similaire car ils appartiennent aux même groupe.
  Le transporteur "RD" (RATP Dev) correspond à "RC" dans la légende car c'est bien RATP CAP qui gère les filiales gagnés par le groupe RATP en IdF. 

### Traitement des données
- Pour les communes desservies par plusieurs transporteurs, seul le transporteur réalisant le plus grand nombre de validations est affiché
- Les données de population sont issues du dernier recensement INSEE

## Technologies utilisées

- **Python** - Traitement des données et génération de la carte
- **Folium** - Création de la carte interactive
- **GeoPandas** - Manipulation des données géographiques
- **GitHub Pages** - Hébergement et partage


```python
# Cloner le repository
git clone https://github.com/bixente-san/Cartes-transporteurs-bus-IDF-2024.git
