# #CoCoPySHS - Séance 1 - 17/03/2022

## Résumé de la séance

Cette première séance organisée par l'URFIST de Lyon ouvre un cycle de présentations et d'échange autour de la programmation scientifique en Python en SHS. Son ambition est d'ouvrir un moment collectif dans des pratiques encore très dispersées en se concentrant sur Python (mais les praticiens de R, et d'autres langages, sont les bienvenus car de nombreuses questions sont plus générales). 

Trois publics en particulier sont attendus, et ont été au rendez-vous (une quarantaine de participants) :  1/ des praticiens pour parler de leur pratique 2/ des apprenants qui ont des questions sur les bonnes approches 3/ des curieux.ses voulant voir et échanger. Le point clé est cependant : en SHS, nous ne sommes pas des développeurs ni des informaticiens, et nous devons tenir ensemble la problématisation et l'aspect technique.

C'est ce que fait **Tristan Salord**. Il se définit avant tout comme un socio-anthropologue, et pas comme un informaticien. Il est chercheur en humanité digitale : la problématique est première, et le traitement des données est là pour y répondre. Par conséquent, peut-être que son code est "une monstruosité pour un développeur", mais elle permet de rendre utilisable des données : dans ce cas, des listes d'ingrédients.

En effet, coder : c'est réaliser des traductions, transporter des objets d'un univers à d'autre, en les dotant d'agentivité. Lui, il est venu à la programmation après une formation en sociologie par la petite porte du code : les bases de données, et SQL. Au gré des projets, il a été amené à automatiser certains traitements. Comme il le dit, *derrière la nécessité de coder, il y a toujours un calcul cout/bénéfice à faire : si ce que je peux faire je peux le faire manuellement, il n'y a pas besoin de coder*. 

Son travail en cours depuis quelques années sur les légumineuses s'inscrit dans un projet sur le changement des pratiques alimentaires. Il existe en effet des blocages technologiques autour des connaissances sur les légumineuses, et finalement peu de connaissances scientifiques sur la question. L'idée est d'apprendre des grosses bases de données alimentaires. Or, il n'existait pas d'outils de traitement de ces bases de données et d'ingrédients.

Ces données sont complexes et nécessitent un traitement; Ainsi, des aliments sont souvent marqués sous la forme de noms d'usages (une lentille en France n'est pas une lentille en Inde). Il est nécessaire de s'appuyer sur des savoirs spécifiques pour comprendre les listes d'ingrédients (des ensembles de mots). Par ailleurs, la taille de ces données limite un traitement humain, avec plus de 300000 entrées.

La tache clé a donc été d'automatiser le processus de lecture et de repérage que ferait un cerveau humain et de stocker ça dans une structure de données (un dictionnaire d'ingrédients). Concrètement, cela signifie développer un *parseur*. Pour cela, Tristan a décomposé les problèmes rencontrés à partir de la tache humaine, et progressivement constitué son workflow. Cela nécessite de trouver les astuces pour réduire le travail à faire : par exemple découper à la virgule plutôt que de repérer tous les patterns. Une première étape est alors de construire la réflexion sous la forme d'un pseudo-code en langage très descriptif, écrit à la main, puis de construire les briques de bases en Python. C'est un travail itératif, avec à chaque fois le besoin de tester les morceaux de code.
    
Pourquoi il a choisi Python : parce qu'il est proche du langage naturel, de la langue et donc du pseudo code. Le fait qu'il s'agisse d'un langage non typé aide. Son style est davantage procédural que orienté objet. Pour autant, il n'est pas exclusif, par exemple il se forme actuellement à Julia. Travaillant dans un IDE (Microsoft Visual Studio), il a développé avec le temps des bonnes pratiques de notation des fichiers, d'un usage extensif des commentaires pour documenter le code et de limiter la taille de ses scripts.

Il est convaincu que le mieux est l'ennemi du bien : il faut garder la possibilité de l'imperfection/d'une petite erreur plutôt que de s'épuiser à un code parfait. Un enjeu dans le traitement de données est de trouver la structure adaptée pour conserver au mieux l'information initiale. Mais celle-ci est pas donnée d'avance, et provient d'échanges progressifs avec des experts qui conduit à faire évoluer la structure de donnés.

Une fois l'outil développé au gré des traitements, que faire du code ? Tristan le met à disposition, mais la question demeure des bonnes pratiques de diffusion. 

Son avis sur le machine learning ? S'il est possible de l'éviter, autant l'éviter.

Et puis, finalement, **pourquoi faire tout ça ?** Cela permet d'ouvrir les boites noires de la production alimentaire, qui seraient inaccessibles sinon. Et de traiter des volumes impossibles à traiter à la main. Ce parseur est alors essentiel dans la production de résultats : réseaux de liens, évolution dans le temps, statistiques descriptives. Des publications sont en cours tant sur les résultats que sur le jeu de données produit.

Après la présentation, les questions ont balayé les problématiques de structure des données, du temps gagné à l'automatisation, des conditions de publication du script, de la décision entre apprendre à programmer soi-même ou déléguer à un spécialiste, ou encore des ressources disponibles. La question reste ouverte de la manière de faciliter les échanges : Twitter avec un hashtag #cocopyshs ? Un serveur Discord ? Ouvrir un mattermost avec Hum-Num ? Réflexion à suivre.

Quelques remarques remarquables :

- "pour faire une analogie simple, déléguer complètement la programmation c'est comme être un anthropologue qui dépend d'un traducteur"
- "perso je trouve qu'apprendre la programmation soi-même permet de mieux concevoir le panel des possibilités de techniques pour une recherche"
- "Beaucoup d'apriori aussi peut être sur le code en SHS..."
