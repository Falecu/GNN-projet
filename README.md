# Démarche de reproductibilité :

## bibliothèques requises : 
torch
torch_geometric
networkx
scikit-learn
pandas
numpy
matplotlib
jupyter

créer un environnement python à l'aide de la commande "python -m venv .venv" puis l'activer avec "source .venv/bin/activate" afin de pouvoir lancer le code.

placer le fichier "airportsAndCoordAndPop.graphml" au même endroit que projet.ipynb puis executer chaque celulles (la 5ème cellule )

### Modèles IA générative utilisé 

Claude Sonnet 5.5 et Gemini pro 3.5 flash-light : principalement pour le modèle GIN, l'affichage des résultats et pour se documenter.

exemples de prompt : "donne moi un autre modèle que MLP, GCN et GAT pour de la classification à partir d'un graphe", "rend l'affichage des résultat plus ordonné", "explique moi comment marche le f1 score de sklearn"
