# f1-pit-predictor-data

Ce repository contient les données utilisées pour le travail de Bachelor "Machine Learning pour prendre la décision d'un arrêt au stand en Formule 1".

## Données

Les données sont disponibles dans le dossier `data`. Elles sont au format CSV et sont séparées par année. Chaque fichier contient les données d'une course avec un nom de fichier au format suivant: `nom_du_grand_prix.csv`. Chaque dossier contient un fichier CSV 'season.csv' qui concatène les données de toutes les courses.

## Génération

Les données sont générées dans le notebook 'generate_dataset.ipynb' à partir des données fournies par la librairie [FastF1](https://github.com/theOehrly/Fast-F1).