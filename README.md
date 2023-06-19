# IA_prediction
# Réseau de neurones pour la classification des fleurs
Ce code implémente un réseau de neurones simple pour classer des fleurs en deux catégories : rouge et bleu. Le réseau de neurones est entraîné sur un ensemble de données d'entrée, qui sont des caractéristiques des fleurs, et un ensemble de données de sortie, qui sont les couleurs des fleurs.

# Structure du réseau de neurones
Le réseau de neurones a une couche d'entrée avec deux neurones (correspondant aux deux caractéristiques des fleurs), une couche cachée avec trois neurones, et une couche de sortie avec un neurone (correspondant à la couleur de la fleur).

# Fonctionnement du réseau de neurones
Le réseau de neurones fonctionne en deux étapes : la propagation avant et la rétropropagation.

# Propagation avant
Dans la propagation avant, les données d'entrée sont multipliées par les poids du réseau de neurones pour produire une valeur de sortie. Cette valeur de sortie est ensuite passée à travers une fonction d'activation (dans ce cas, la fonction sigmoid) pour produire la sortie finale du réseau de neurones.

# Rétropropagation
Dans la rétropropagation, l'erreur entre la sortie prédite par le réseau de neurones et la sortie réelle est calculée. Cette erreur est ensuite utilisée pour ajuster les poids du réseau de neurones afin de minimiser l'erreur.

# Entraînement du réseau de neurones
Le réseau de neurones est entraîné en répétant les étapes de propagation avant et de rétropropagation pour un certain nombre d'itérations. À chaque itération, les poids du réseau de neurones sont ajustés pour minimiser l'erreur.

# Prédiction
Une fois que le réseau de neurones a été entraîné, il peut être utilisé pour prédire la couleur d'une fleur à partir de ses caractéristiques. Dans ce code, la prédiction est effectuée en passant les caractéristiques d'une fleur à travers le réseau de neurones entraîné et en utilisant la sortie pour déterminer la couleur de la fleur.

# Utilisation
Pour utiliser ce code, vous devez avoir une installation de Python avec la bibliothèque numpy. Vous pouvez exécuter le code en utilisant l'interpréteur Python. Le code affichera la sortie prédite du réseau de neurones à chaque itération de l'entraînement, ainsi que la prédiction finale pour une fleur donnée.
