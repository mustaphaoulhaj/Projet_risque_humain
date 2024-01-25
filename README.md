# Comment prévenir le risque humain en Python

## Introduction

La non-participation à la planification familiale peut en effet présenter des risques pour les femmes et leurs enfants. 
Voici quelques raisons pour lesquelles cela peut être considéré comme un risque humain :

- Croissance démographique incontrôlée : Une pression sur les ressources naturelles, l'environnement et les services de santé.
- Santé maternelle et infantile : Le risque de grossesses non désirées et non planifiées, avortements non sécurisés, des complications liées à la grossesse et à l'accouchement et augmentation de la mortalité maternelle et infantile.
- Maladies sexuellement transmissibles : Une augmentation du nombre de cas de MST.

## Source de données

Les données utilisées dans ce travail viennent de la base de données de l'enquête nationale sur la population et la santé familiale (ENPSF) réalisée par le ministère de la Santé du Maroc (MS) en 2011.

## Méthodologie 

Ce projet peut être divisé en deux parties distinctes : 

### - Construction d'un modèle de prévision et validation de sa performance : 
Dans cette partie, nous construisons un modèle prédictif en utilisant des données d'apprentissage. Nous séparons les données en un ensemble d'apprentissage et un ensemble de test pour évaluer les performances du modèle. Nous  entraînons le modèle sur l'ensemble d'apprentissage, puis nous l'évaluons sur l'ensemble de test pour mesurer sa capacité à prédire avec précision les résultats attendus.

### - Mise en routine du modèle avec système d'alerte en cas de déviation :
Nous avons mis en place un système d'alerte pour détecter les déviations. Lorsque de nouvelles données sont introduites dans le modèle, il génère des prédictions. Si les prédictions dépassent un seuil prédéfini ou indiquent une déviation par rapport aux attentes, le système envoie une notification d'alerte (par exemple, un e-mail) pour signaler la présence d'un risque humain.
