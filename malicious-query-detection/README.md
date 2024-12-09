# Détection de requêtes HTTP malveillantes grace aux techniques de NLP

## Présentation du projet

Dans l'écosystème numérique actuel, les plateformes e-commerce représentent des cibles privilégiées pour les cyberattaques, gérant quotidiennement des millions de requêtes HTTP aux enjeux critiques. Ce flux constant de données transite par des infrastructures exposant des vulnérabilités potentiellement exploitables.
Le paysage des menaces cybernétiques se caractérise par une sophistication croissante : au-delà des injections SQL classiques, les attaquants déploient des stratégies complexes incluant des scripts intersites (XSS), des attaques par dissimulation de commandes, et des tentatives d'exploitation de failles applicatives. Les mécanismes de défense traditionnels, principalement basés sur des règles statiques et des signatures prédéfinies, accusent désormais un retard significatif face à l'agilité des techniques d'intrusion.
 
Dans ce projet, vous êtes invité à utiliser les techniques de traitement du langage naturel (NLP) et de cybersécurité afin de créer un modèle de détection de requêtes HTTP malveillantes.  Ce modèle pourra servir de module d'un système de défense proactif, capable d'optimiser la résilience des infrastructures numériques face aux menaces émergentes.

## Votre tâche

Créer un système capable d'identifier et de bloquer les requêtes HTTP malveillantes à l'aide de modèles de détection des menaces basés sur le NLP.

__NB: L’ARCHITECTURE DU RÉSEAUX EST DOIT ÊTRE UN RÉSEAUX RÉCURRENT (RNN, GRU, LSTM) OÙ UN TRANSFORMER.__

## Jeux de données
Pour relever ce défi de détection des requêtes malveillantes, nous disposons de deux ensembles de données complémentaires, construits pour entraîner et valider votre modèle de détection :
- Un premier jeu de données, ***badqueries.txt***, constitué de 48 126 requêtes HTTP identifiées comme malveillantes. 
- Un second jeu de données, ***goodqueries.txt***, comprenant 1 294 531 requêtes HTTP légitimes.

Vous trouverez les données dans le dossier `data`.

## Livrables
- Un notebook contenant le code source et une documentation de bonne qualité qui présente votre solution. 
- Un rapport de projet.
- Une présentation Powerpoint.
