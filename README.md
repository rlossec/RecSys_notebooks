# RecSys Notebooks

## Projet

Ce projet est un projet de formation qui consiste en une application de recommandation de contenu.
L'application web est développée en React déployée sur Azure à l'aide d'un container Docker.
Cette application fait appel à une azure Function qui contient la logique des modèles alimentée par des fichiers sur Blob Storage d'Azure.

## Repositories
Le projet se découpe en 3 repositories :
  - ce repo : les notebooks avec les Systèmes de recommandations
  - [l'azure function](https://github.com/rlossec/RecSys_AzureFunction)
  - [l'application web](https://github.com/rlossec/RecSys_WebApp)

## Architecture

![Architecture globale de l'application](https://github.com/rlossec/RecSys_notebooks/blob/master/Architecture.drawio.png)



## Repo Notebooks
Ce repository contient les notebooks Jupyter utilisés pour développer et tester les systèmes de recommandation.
Ces notebooks explorent différentes approches et algorithmes pour recommander du contenu.

## Structure 
- `notebooks/` : Contient tous les notebooks Jupyter.
- `data/` : Contient les jeux de données utilisés par les notebooks.
- `scripts/` : Contient des scripts auxiliaires pour le traitement des données et l'entraînement des modèles.
