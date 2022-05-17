# #CoCoPySHS - Séance 2 - 08/04/2022

## Résumé de la séance

Cette deuxième séance organisée par l'URFIST de Lyon propose de plonger directement dans les problématiques au coeur de nos interrogations : l'usage des outils numériques par les chercheurs et la reproductibilité des résultats d'une enquête. 

Le duo Mariannig Le Béchec et Emilien Schultz présentent justement cette dynamique de reproduction de données d'une enquête menée en 2021 **Reproductibilité de l'enquête SOSP - State of Open Science Practices in France** (Mariannig Le Béchec - Aline Bouchard - Philippe Charrier - Claire Denecker - Gabriel Gallezot - Stéphanie Rennes) dont le rapport est paru il y a peu https://hal.archives-ouvertes.fr/hal-03545512v1

La démarche de l'équipe investigatrice était justement de favoriser les bonnes pratiques de la recherche mais dans les contraintes d'une activité prises par les impératifs matériels et organisationnels. Ainsi, s'ils ont utilisé un logiciel propriétaire pour la collecte et l'analyse des données (Sphinx, déployé par la TGIR Huma-Num qui avait l'avantage de permettre la mise en ligne du questionnaire pour la passation et le traitement des données), ils ont rapidement ouvert les données en déposant le jeu de données et de méta-données sur *Zenodo* : https://zenodo.org/record/5827206.

De là, nous avons tout pour nous saisir de cette enquête, vérifier certains traitements et aller plus loin si besoin. Cela permet de mettre à l'épreuve les outils existant en Python.

Mariannig présente la genèse et le périmètre de l'enquête, en insistant sur quelques résultats marquants concernant les pratiques des chercheurs.

Emilien présente alors sa pratique de traitement de données en sociologie qui utilise uniquement les outils de la programmation scientifique en Python : les Notebooks Jupyter, et les bibliothèques principales (Pandas, Matplotlib, etc.).

Sans rentrer dans le détail fin du code, disponible dans un carnet Jupyter exécutable (https://github.com/emilienschultz/sosppyshs), il insiste sur les différentes étapes : le chargement, le nettoyage, puis la reproduction de certains résultats, notamment une visusalisation du rapport pour en modifier certains aspects, et enfin l'exploration de pistes ouvertes par le rapport mais qui n'ont pas été détaillées.

L'intérêt de travailler dans un Notebook Jupyter est de faciliter cette interaction avec les données tout en gardant une trace de l'ensemble des opérations, qui peuvent ensuite être mises en pause sans perdre le travail, ou partagée à des collègues. L'association entre les bibliothèques structurantes de Python scientifique (Pandas, Matplotlib, Plotly, etc.) couplé avec des bibliothèques plus spécifiques (PySHS, Prince), permettent de couvrir l'ensemble des traitements statistiques "habituels", tout en formalisant les étapes.

Bien entendu, le coût d'entrée existe et il n'est pas évident de trouver immédiatement ces opérations et la meilleure manière de le faire. Cet exemple a justement pour objectif de donner un cas réutilisable d'étapes qui peuvent ensuite être traduites pour d'autres enquêtes.

Une rapide démonstration a ensuite été faite sur la possibilité de passer de l'étape de prototypage dans un notebook avec une application grâce à Streamlite. Python permet justement de lier les pratiques d'exploration avec le passage en production.

Une rapide synthèse pose la question des forces et des faiblesses de Python :

Forces

- Formaliser la démarche
- Support Jupyter ++ pour le travail collaboratif et incrémental
- Code réexcutable facile à reprendre et à corriger
- Des outils très puissants qui permettent la souplesse
- Sortir de la dépendance d'un logiciel (Sphinx initialement)
- De nombreuses ressources disponibles sur internet

Faiblesses

- Manque d'exemple -> beaucoup de petites recherches sur internet pour arriver au résultat final
- Cout d'entrée pour son propre code : découvrir les bibliothèques, etc.
- Manque de bibliothèques SHS & de tutoriaux spécifiques
- Un travail "caché" : chercher les bonnes manières de faire, etc. difficile à montrer + beaucoup de temps à passer à retrouver les bonnes options
- Une ergonomie qui peut être moindre qu'un logiciel dédié


Et puis demeure la dernière question : Python ou R ? Ce sont effecivement deux solutions possibles, et nous ne prétendons pas terminer ce débat :)

La discussion qui a suivi la présentation a justement porté sur le coût d'entrée, l'importance d'avoir des exemples pour s'y mettre, et sur l'intérêt évident de construire des documents exécutables pour la reproductibilité des résultats.

Affaire à suivre ...