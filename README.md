# Projet - Non Supervisé Avancé 
# Étude d'un article: 

## Fitting Mixtures of Linear Regressions de Susana Faria et Gilda Soromenho [Article](https://www.academia.edu/117473574/Fitting_mixtures_of_linear_regressions)

## Présentation 
Ce repository contient le code pour reproduire la simulation faite dans l'article pour un mélange de régression linéaire à deux composantes. 

## Résumé
Cet article traite des modèles de mélange pour la régression linéaire, une méthode qui combine plusieurs modèles pour mieux représenter des données hétérogènes. Les auteurs analysent trois algorithmes d'estimation : EM, CEM et SEM. En utilisant des données simulées, ils comparent leurs performances en termes de précision des estimations, nombre d'itérations nécessaires et capacité à s'adapter dans différentes configurations, comme des droites parallèles ou concurrentes, avec des paramètres initialisés aléatoirement ou non.
Leurs expériences montrent que l'algorithme CEM converge généralement plus rapidement et donne les estimations les plus précises lorsque l'initialisation utilise les vrais paramètres. Par contre, en cas d'initialisation aléatoire, l'algorithme SEM produit des estimations avec une erreur quadratique moyenne plus faible et des prédictions plus fiables, validées par une approche de validation croisée.

