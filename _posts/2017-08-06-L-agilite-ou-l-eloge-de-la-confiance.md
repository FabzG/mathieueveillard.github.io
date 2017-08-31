---
layout: post
title:  "[Software] L’agilité ou l’éloge de la confiance"
date:   2017-08-06 11:34:09 +0200
categories: software
---

![Trust]({{ site.url }}/assets/2/Trust.jpg)

[Crédits photo](https://pxhere.com/fr/photo/1402678)

Les cadres méthodologiques agiles existent depuis bientôt 20 ans et connaissent un nouvel essor ces dernières années. Malheureusement, leur adoption conduit trop souvent à les dénaturer : on fait "un peu" de Scrum. Rien de surprenant à cela tant les valeurs sur lesquelles ces cadres méthodologiques reposent sont étrangères à nos organisations. Au travers de cet article, examinons plus particulièrement pourquoi la confiance est à la base de l'agilité, et comment l'instaurer.


### Faire confiance… à l’utilisateur !

Dans le domaine du développement d'applications de gestion, les méthodologies séquentielles prédominent. Dans ce contexte, Jim Johnson, président du Standish Group, estime que __45% des fonctionnalités mises en œuvre ne sont jamais utilisées__ (1). Cela signifie que nous pourrions faire des applications tout aussi utiles en deux fois moins de temps ou avec un budget deux fois inférieur. Comment en sommes-nous arrivés là ?

Les méthodologies séquentielles (cascade et cycle en V) proposent de concevoir un système dans son intégralité avant de commencer sa mise en œuvre. On constate fréquemment que, ce faisant, la peur d'oublier une fonctionnalité et de ne pas pouvoir revenir en arrière (ou à un coût important) conduit à une recherche effrénée d'exhaustivité. Lotir ne fait que repousser le problème car la définition des lots _ex ante_ ne laisse aucune place au retour d'expérience utilisateur, ou alors chèrement payée et remettant en cause les lots suivants.

Cette dérive ne se produirait pas si la prise en compte du retour d'expérience utilisateur était correctement organisée notamment en l'impliquant dans le processus dès le début et en construisant l'outil avec lui. Nous sommes habitués à concevoir des applications sans vraiment demander l'avis de ce dernier. Parce qu'après tout, avouons-le, on sait quand-même mieux que lui ce dont il a besoin, non ?

Non.

Non, car nous ne sommes pas représentatifs de la population des utilisateurs, même quand leur métier nous est familier (cas des applications grand public, chacun sait par exemple comment réserver un billet de train). A cela plusieurs raisons :
1. Nous concevons les applications au lieu de les découvrir et d'en être de simples utilisateurs ;
2. Nous connaissons la grammaire implicite des systèmes informatiques, parce que c'est notre métier et donc ce qui est évident pour nous ne l'est pas forcément pour le public visé ;
3. Nous sommes "quelques" concepteurs quand les utilisateurs se comptent en dizaines ou centaines de milliers voire en millions, voire... Facebook :)
5. La conception d'une application est complexe et demande des expertises technique et métier du terrain que nous n'avons pas forcément ;
4. Mais surtout, concevoir une application, ce n'est pas l'utiliser. Le temps et la répétition sont seuls à pouvoir apporter certaines réponses, seuls aussi à pouvoir poser certaines questions.

__Nous, informaticiens, devons donc nous déclarer "incompétents" et faire confiance à l’utilisateur pour savoir ce dont il a besoin.__ L'une des vertus de l'agilité est justement de remettre l'utilisateur au centre : [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product), [livraison continue](https://en.wikipedia.org/wiki/Continuous_delivery) et tests utilisateurs sont autant de moyens d'organiser le recueil régulier de ce feedback, sans lequel il n'est pas de bonne application.


### Gagner la confiance du client
Posons-le tout de suite : __le besoin étant dicté au fur et à mesure par l’utilisateur et non le client, agilité et engagement de résultat (cadre contractuel forfaitaire) ne sont pas compatibles__. Un fournisseur ne peut pas s'engager à réaliser "quelque chose" quand ce "quelque chose" n'est pas identifié au départ.

Nous mettons ainsi le doigt sur l'une des principales difficultés de l'agilité : une très grande confiance doit exister entre un client et son fournisseur pour qu'un projet puisse se dérouler dans le cadre d'un simple engagement de moyens, qui implique que le risque financier soit entièrement assumé par le client. __En renonçant à tout engagement forfaitaire, le client reconnaît la responsabilité qui est la sienne dans la réussite du projet__ : à lui de prioriser les fonctionnalités à mettre en œuvre, de fournir les informations en temps et en heure et de décider sans délai. Le [Guide Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf) est très explicite à ce sujet :

> _"Le Product Owner est responsable de maximiser la valeur du produit et du travail de l’Équipe de Développement"_

Atteindre ce niveau de confiance est un défi difficile à relever. C'est d'ailleurs pour cette raison que l'agilité est une modalité que l'on rencontre le plus souvent en dehors du cadre contractuel client-fournisseur, au sein de start-up, éditeurs de logiciels ou de grands groupes dont les équipes sont constituées exclusivement de salariés.

__Relever ce défi nécessite que client et fournisseur travaillent plus que jamais dans une optique de partenariat sincère et généreuse__. Nous devons lutter pour retrouver cet esprit, mis à mal depuis longtemps par les notions de "périmètre" et "d'écarts de périmètre", qui cristallisent tant de crispations dans les projets séquentiels. De toute façon, il est fréquent que le client, au travers d'avenants successifs, reconnaisse être à l'origine d'une surcharge de travail et que l'engagement de résultat initial évolue _de facto_ vers un engagement de moyens.

Quand il s'agit d'instaurer la confiance, la proximité physique du Product Owner client et de l'équipe de développement fournisseur est un aspect nécessaire. Cette proximité permet une multitude d'interactions informelles qui, inconsciemment, contribuent à faire tomber les barrières. Travaillant ensemble, le client et le fournisseurs voient les impacts de leurs décisions ou actions sur l'autre la relation se transforme de client fournisseur en un mode coopératif.

![Relieved]({{ site.url }}/assets/2/Relieved.jpg)

[Crédits photo](https://pxhere.com/fr/photo/1341198)


### Faire confiance à l’équipe de développement
Il serait temps, enfin, de faire confiance aux membres de l'équipe de développement, qu'il s'agisse d'analystes/concepteurs fonctionnels ou de développeurs. Ne sont-ils pas les mieux à même d'évaluer la complexité d'une fonctionnalité à mettre en œuvre ? Ne sont-ils pas suffisamment autonomes et responsables pour améliorer d'eux-mêmes leur productivité ?

Créer les conditions pour que chacun se sente investi de responsabilités est un formidable levier de motivation des équipes. [Le cadre méthodologique Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf) pousse le principe à l'extrême et promeut leur auto-gestion, ce qui n'est pas sans rappeler les nouvelles formes d'organisation du travail, dites "horizontales", décrites par Frédéric Laloux dans son ouvrage [Reinventing Organizations](https://www.amazon.fr/dp/2354561059).

Plus de chef de projets, donc, mais un _Scrum Master_ au service de l'équipe, avec une différence fondamentale : le premier dirige, le second facilite et conseille. L’organisation interne des entreprises de services informatiques s’en trouve profondément chamboulée. Que faire du sacro-saint chef de projets ? [Certaines entreprises](http://www.theodo.fr/), parce qu'elles sont jeunes et n'ont connu que l'agilité, l'ont compris et se sont structurées en conséquence. Pour les autres, c'est un changement de culture profond.

__Cette approche suscite de fortes réticences parce qu'elle se heurte à l'idée que la prise de responsabilités managériales est la seule réussite sociale possible__. Aussi bon soit-il, un développeur de 50 ans est vu comme quelqu'un qui n'a pas réussi à s'élever socialement. Pourquoi ? Comment expliquer que la voie dite "technique" soit à ce point déconsidérée, sociétalement et salarialement ? Quand aurons-nous enfin des développeurs "stars" français, reconnus au même titre que [Martin Fowler](https://twitter.com/martinfowler), [Dan Abramov](https://twitter.com/dan_abramov) ou [André Staltz](https://twitter.com/andrestaltz) ?

Cessons de dépeindre le développeur comme un solitaire produisant frénétiquement du code sans rien comprendre du contexte dans lequel il travaille ni prendre aucune décision. Accordons lui la place centrale qu'il mérite et qu'il va souvent chercher Outre-Atlantique à défaut de la trouver en France. Développer efficacement suppose une compréhension avancée de systèmes fortement complexes, une rigueur infaillible,  une grande connaissance de soi et de belles capacités relationnelles. Qu’est-ce qu’un bon développeur sinon déjà un architecte en devenir ?

Ces propos ne remettent nullement en question l'utilité d'un management, bien au contraire. Mais souhaitons ensemble une direction recentrée sur sa fonction première : orienter, inspirer et fédérer en donnant du sens au travail. Comme [André Comte-Sponville](https://www.youtube.com/watch?v=TBuRaS1L6aI) a su l'expliquer de manière lumineuse, un manager devrait tenter de répondre à la question _"pourquoi travailler ?"_ plutôt qu'à la question _"comment travailler ?"_.


Cet article avait pour but de démontrer que l'agilité n'est pas une méthodologie projet mais bien un __projet de société__ fondé sur la confiance. Certains parleront d'utopie, soit, mais pourquoi ne pas y aspirer et faire le premier pas ? __La meilleure façon de savoir si l'on peut faire confiance à quelqu'un, c'est de lui faire confiance__.

Réagissez à ces idées ou partagez vos expériences en la matière en laissant un commentaire !

![First step]({{ site.url }}/assets/2/First_Step.jpg)

[Crédits photo](https://pxhere.com/fr/photo/749593)

_(1) Proceedings of the Third International Conference on Extreme Programming and Flexible Processes in Software Engineering (XP 2002), Alghero, Sardinia, Italy (Requirements usage: Always 7%, Often 13%, Sometimes 16%, Rarely 19%, Never 45%)._
