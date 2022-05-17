# #CoCoPySHS - Séance 3 - 12/05/2022

## Résumé de la séance

Cette troisième séance porte l'éclairage sur les pratiques peu visibles de **transformation des données**, en amont de l'usage d'un logiciel spécialisé (dans ce cas, Iramuteq). Ici, "le résultat de mon code est une porte d'entrée et pas une conclusion".

[Lucie Loubère](https://www.lerass.com/author/lloubere/) est spécialiste dans l'analyse des débats avec les outils de traitement textuels. Elle mobilise largement Iramuteq pour la production des résultats, dont elle a la familiarité à la fois théoriques (les notions sous-jacentes au logiciel) et pratique (ses paramétrages). Cependant, avant de pouvoir procéder à une analyse de corpus, il est indispensable de constituer ce corpus et de le mettre en forme. Comme elle le fait remarquer, "la force des logiciels spécialisés dépend de la qualité du corpus qu'il y a en amont".

Pour cela, la programmation en Python permet d'avoir une forte flexibilité pour collecter les données et constituer différents corpus textuels qui respectent les formats attendus par le logiciel. Notamment, cela permet de filtrer ou de recomposer les corpus à analyser, rajouter des informations supplémentaires (conserver certains textes à partir d'une liste d'expressions par exemple) ou procéder à des regroupements pertinents. Le faire à la main limiterait largement l'exploration des possibilités. 

Un exemple qui témoigne de l'importance d'avoir les outils : nettoyer un corpus pour neutraliser les chiffres romains (ou des groupes de mots) en les remplaçant par des expressions non-ambigues qui pourront être analysées. Ou encore, des scripts permettent de décomposer des textes en sous éléments (début, milieu, fin) et d'analyser d'autres aspects.

Il ne s'agit donc pas pour elle de développer un nouveau logiciel ou de suppléer à son usage : non seulement les compétences et le temps nécessaire dépassent souvent largement l'activité, mais en plus ces logiciels existent et son performants. Par contre, en maîtrisant les bases du langage et quelques tours de mains, faire un script utile est à la fois possible et fait gagner du temps, en étendant les usages. 

Il y a plusieurs raisons qui l'incitent à utiliser de la programmation. 

Tout d'abord, comme Lucie le fait remarquer, "les données s'y prête ou incitent à le faire", notamment sur des données non structurées à collecter comme les réseaux sociaux. 

Ensuite, s'il existe des solutions pour certaines transformations, la versatilité de Python permet progressivement de monter en compétence. Ainsi, elle fait remarquer que
"dans certains cas, je ne connais pas les outils, et ça va plus vite que de me familiariser à un nouveau logiciel pour beaucoup de pratique de collecte de données".

Enfin, écrire ses scripts de transformation permet de maîtriser le processus complet des données au logiciel, et de ne pas passer par des boîtes noires non contrôlées.

Quelles sont les raisons d'utiliser Python plutôt qu'un autre langage ? Tout d'abord, "mon entourage scientifique m'y a invité", cet entourage étant Pierre Ratinaud. C'est un langage très accessible, auquelle elle s'est familiarisée en autodidacte, et qui a de nombreuses forces comme la gestion des encodages. Par ailleurs, "de nombreuses librairies préxistantes : je ne vais pas réinventer la roue, plein de gens ont déjà fait des roues et des voitures, et on peut les utiliser".

En pratique, qu'est-ce qu'elle fait ? Elle décrit un peu la répartition de ses usages :

- 80% des pratiques: ouvrir un fichier texte ; lire les lignes et constituer des objets et écrire un nouveau fichier
- 15% des pratiques : adapter des solutions trouvées sur Stackoverflow : "souvent ça passe : souvent, on ne sait pas pourquoi ça passe, mais ça passe".
- 5% des pratiques : aspect créatif, qui porte sur des points limités mais qui peut prendre du temps
- marginalement, elle est aussi intervenu sur le code du logiciel lui-même, grâce aux compétences développées

Un exemple précis d'utilisation ? Écrire un petit script qui permet d'ajouter des variables descriptives à un corpus, qui a pris 10 minutes et a permis une publication.

Ses bibliothèques préférées ? CSV, Selenium, BeautifulSoup.

Sur l'ouverture du code par contre, les pratiques de scripts restent largement personnelles. Ce sont des palimpsestes qui évoluent dans le temps en fonction des besoins. Elle n'utilise pas les Notebooks, et travaille directement dans des fichiers. Cette variabilité des besoins très proche de la pratique limite le passage vers des outils stabilisés diffusables (modules, bibliothèques). Cela souligne l'existence de différents niveaux de scripts.

Dans la discussion, Lucie développe un peu sur son usage de Selenium pour automatiser l'action d'un navigateur afin de collecter des données sur des sites. Cela permet de contourner certaines limitations, notamment celles liées au caractère non statique de certains sites. Cela nécessite cependant une forte dose de rétroingéniérie pour comprendre la structure du site, et c'est souvent une course contre les évolutions des pages internets. 

Une pensée pour la route ? "c'est parce qu'on en a besoin qu'on apprend : j'ai toujours codé pour un besoin précis. Mais à chaque fois qu'on code, on apprend". C'est en se confrontant à une gamme de problèmes qu'on monte en compétence."