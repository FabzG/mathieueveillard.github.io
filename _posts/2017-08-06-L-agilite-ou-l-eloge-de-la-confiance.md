---
layout: post
title:  "[Software] L’agilité ou l’éloge de la confiance"
date:   2017-08-06 11:34:09 +0200
categories: software
---

![Trust]({{ site.url }}/assets/2/Trust.jpg)

[Crédits photo](https://pxhere.com/fr/photo/1402678)

Les cadres méthodologiques agiles existent depuis bientôt 20 ans et connaissent un nouvel essor ces dernières années. Malheureusement, leur adoption conduit trop souvent à les dénaturer : on fait "un peu" de Scrum. Rien de surprenant à cela tant les valeurs sur lesquels ces cadres méthodologiques reposent sont étrangères à nos organisations. Au travers de cet article, examinons plus particulièrement pourquoi la confiance est à la base de l'agilité, et comment l'instaurer.


### Faire confiance… à l’utilisateur !

Des études ont montré qu'à ce jour, dans un contexte où les méthodologies séquentielles prédominent (cascade et cycle en V), __50% des fonctionnalités mises en œuvre ne sont jamais utilisées__. Cela signifie que nous pourrions faire des applications tout aussi utiles en deux fois moins de temps ou avec un budget deux fois inférieur. Comment en sommes-nous arrivés là ?

Les méthodologies séquentielles introduisent elles-mêmes un premier biais : concevoir un système dans son intégralité avant de le mettre en œuvre est certes un gage de cohérence fonctionnelle et technique, mais la peur d'oublier une fonctionnalité et de ne pas pouvoir revenir en arrière conduit bien souvent à une recherche effrenée d'exhaustivité. Lotir ne faisant que repousser le problème, seule une approche réellement itérative permet d'en sortir.

Le caractère itératif repose sur la prise en compte du retour d'expérience de l'utilisateur. C'est là que réside le second biais : nous, informaticiens, sommes habitués à concevoir des applications sans vraiment demander son avis à l'utilisateur. Parce qu'après tout, avouons-le nous, on sait quand-même mieux que lui ce dont il a besoin, non ?

Non.

Non, car quand bien même nous connaîtrions exactement son métier (c'est le cas des applications grand public : chacun sait comment réserver un billet de train), nous ne serions pas représentatifs de la population des utilisateurs :
1. Nous concevons les applications au lieu de les découvrir ;
2. Nous connaissons la grammaire implicite des systèmes informatiques, parce que c'est notre métier ;
3. Nous sommes "quelques" concepteurs quand les utilisateurs se comptent en dizaines ou centaines de milliers voire en millions, voire... Facebook :)
4. Mais surtout, concevoir une application, ce n'est pas l'utiliser. Le temps et la répétition sont seuls à pouvoir apporter certaines réponses, seuls aussi à pouvoir poser certaines questions.

__Nous, informaticiens, devons donc nous déclarer "incompétents" et faire confiance à l’utilisateur pour savoir ce dont il a besoin.__ L'une des vertus de l'agilité est justement de remettre l'utilisateur au centre : [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product), [livraison continue](https://en.wikipedia.org/wiki/Continuous_delivery) et tests utilisateurs sont autant de moyens d'organiser le recueil régulier de ce feedback, sans lequel il n'est pas de bonne application.


### Gagner la confiance du client
Posons-le tout de suite : __le besoin étant dicté au fur et à mesure par l’utilisateur et non le client, agilité et cadre contractuel forfaitaire ne sont pas compatibles__. Un fournisseur ne peut pas s'engager à réaliser "quelque chose" (engagement de résultat) quand ce "quelque chose" n'est pas identifié au départ. L'agilité implique un engagement de moyens de la part du fournisseur. Cela n'empêche en rien le client d'établir un budget, ce budget représentant ce qu'il est capable et prêt à dépenser sans toutefois que le périmètre fonctionnel de l'application soit clairement défini. Le _budget_ d'un client n'est donc pas l'_engagement forfaitaire_ d'un fournisseur.

Nous mettons ainsi le doigt sur l'une des principales difficultés de l'agilité : une très grande confiance doit exister entre un client et son fournisseur pour qu'un projet puisse se dérouler dans le cadre d'un engagement de moyens, puisque le risque financier est entièrement assumé par le client. __En renonçant à tout engagement forfaitaire, le client reconnaît la responsabilité qui est la sienne dans la réussite du projet__ : à lui de prioriser les fonctionnalités à mettre en œuvre, de fournir les informations en temps et en heure et de décider sans délai. Le [Guide Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf) est très explicite à ce sujet :

> _"Le Product Owner est responsable de maximiser la valeur du produit et du travail de l’Équipe de Développement"_

Atteindre ce niveau de confiance est un défi difficile à relever. C'est d'ailleurs pour cette raison que l'agilité est une modalité que l'on rencontre le plus souvent en dehors du cadre contractuel client-fournisseur, au sein de start-up, éditeurs de logiciels ou de grands groupes dont les équipes sont constituées exclusivement de salariés.

__Relever ce défi nécessite que client et fournisseur travaillent plus que jamais dans une optique de partenariat sincère et "généreuse"__. Nous devons lutter pour retrouver cet esprit, mis à mal depuis longtemps par les notions de "périmètre" et "d'écarts de périmètres" qui cristalisent tant de crispations.

![Relieved]({{ site.url }}/assets/2/Relieved.jpg)

[Crédits photo](https://pxhere.com/fr/photo/1341198)

De ce point de vue, la proximité physique des membres de l'équipe est un atout considératible : quand distance rime avec défiance, la proximité, elle, est source de confiance. Quoi de mieux en effet que la multitude d'interactions informelles qu'offre une journée de travail pour apprendre à se connaître ? Quoi de plus sûr que le langage corporel pour savoir que l'on peut faire le premier pas et accorder sa confiance à autrui ?


### Faire confiance à l’équipe de développement
Il serait temps, enfin, de faire confiance aux membres de l'équipe de développement, qu'il s'agisse d'analystes/concepteurs fonctionnels ou de développeurs. Quelqu'un pourrait-il mieux que ces derniers évaluer la complexité d'une fonctionnalité à mettre en œuvre ? Ces derniers ne sont-ils pas suffisamment autonomes et responsables pour, d'eux-mêmes, améliorer continuellement leur façon de travailler en équipe ?

Mon expérience personnelle m'a conforté dans l'idée que chacun donne le meilleur de lui-même quand on favorise son autonomie et se prise de responsabilités. [Le cadre méthodologique Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf) tire les conséquences logiques de ce postulat et propose de laisser l'équipe s'auto-gérer pour améliorer sa productivité avec le temps, faisant ainsi écho aux nouvelles formes d'organisation du travail, dites "horizontales", décrites par Frédéric Laloux dans son ouvrage [_Reinventing Organizations_](https://www.amazon.fr/dp/2354561059).

Plus de chef de projet, donc, mais un _Scrum Master_ au service de l'équipe, avec une différence fondamentale : le premier dirige, le second facilite et conseille. L’organisation interne des entreprises de services informatiques s’en trouve profondément chamboulée. Que faire du sacro-saint chef de projets ? [Certaines entreprises](http://www.theodo.fr/), parce qu'elles sont jeunes et n'ont connu que l'agilité, l'ont compris et se sont structurées en conséquence. Pour les autres, c'est un changement de culture profond.

__Cette approche suscite de fortes rétiscences parce qu'elle se heurte à l'idée que la prise de responsabilités managériale est la seule réussite sociale possible__. Aussi bon soit-il, un développeur de 50 ans est vu comme quelqu'un qui n'a pas réussi à s'élever socialement. Quelle aberration ! Donnons au développeur la place centrale qu'il mérite, et qu'il va souvent chercher Outre-Atlantique à défaut de la trouver en France. Comment expliquer que la voie dite "technique" soit à ce point déconsidérée, sociétalement et salarialement ? Quand aurons-nous enfin des développeurs "stars" français, reconnus au même titre que [Martin Fowler](https://twitter.com/martinfowler), [Dan Abramov](https://twitter.com/dan_abramov) ou [André Staltz](https://twitter.com/andrestaltz) ? Cessons de dépeindre le développeur comme un solitaire produisant frénétiquement du code sans rien comprendre du contexte dans lequel il travaille ni prendre aucune décision. Développer efficacement suppose une compréhension avancée de systèmes fortement complexes, une rigueur infaillible,  une grande connaissance de soi et de belles capacités relationnelles. Qu’est-ce qu’un bon développeur sinon déjà un architecte en devenir ?

Loin de moi l'idée que l'on puisse se passer de management, bien au contraire. Mais souhaitons ensemble une direction recentrée sur sa fonction première : orienter, inspirer et fédérer en donnant du sens au travail. Comme [André Comte-Sponville](https://www.youtube.com/watch?v=TBuRaS1L6aI) a su l'expliquer de manière lumineuse, un manager devrait tenter de répondre à la question _"pourquoi travailler ?"_ plutôt qu'à la question _"comment travailler ?"_.


Cet article avait pour but de démontrer que l'agilité n'est pas une méthodologie projet mais bien un __projet de société__ fondé sur la confiance. Certains parleront d'utopie, soit, mais pourquoi ne pas y aspirer ? Faisons en tout cas le premier pas : la meilleure façon de savoir si l'on peut faire confiance à quelqu'un, c'est de lui faire confiance.

![First step]({{ site.url }}/assets/2/First_Step.jpg)

[Crédits photo](https://pxhere.com/fr/photo/749593)