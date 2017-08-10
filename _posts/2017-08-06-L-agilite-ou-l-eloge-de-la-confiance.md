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

Des études ont montré qu'à ce jour, dans un contexte où les méthodologies séquentielles prédominent (cascade et cycle en V), __50% des fonctionnalités conçues et réalisées ne sont jamais utilisées__. Cela signifie que nous pourrions faire des applications tout aussi utiles en deux fois moins de temps ou avec un budget deux fois moindre ! Comment en sommes-nous arrivés là ?

Les méthodologies séquentielles introduisent elles-mêmes un premier biais : concevoir un système dans son intégralité avant de le mettre en œuvre est certes un gage de cohérence fonctionnelle et technique qui a de la valeur, mais la peur d'oublier une fonctionnalité et de ne pas pouvoir revenir en arrière conduit bien souvent à une recherche effrenée d'exhaustivité. Lotir n'est pas une solution, car on retombe dans le même écueil au sein de chaque lot, les lots étant constitués de périmètres fonctionnels indépendants. Seule une approche réellement itérative permet d'en sortir.

Le caractère itératif repose sur la prise en compte du retour d'expérience de l'utilisateur. C'est là que réside le second biais : nous, informaticiens, sommes habitués à concevoir des applications sans vraiment demander son avis à l'utilisateur. Parce qu'après tout, avouons-le nous, on sait quand-même mieux que lui ce dont il a besoin, non ?

Non.

Non, car quand bien même nous connaîtrions exactement le métier des utilisateurs (c'est le cas des applications grand public : chacun sait comment réserver un billet de train), nous ne serions pas représentatifs de la population des utilisateurs :
1. Nous concevons les applications au lieu de les découvrir, l'interaction s'en trouve modifiée ;
2. Nous "pensons informatique" et connaissons la grammaire implicite des systèmes informatiques ;
3. Nous sommes quelques concepteurs (disons moins de 10) quand les utilisateurs se comptent en centaines, milliers, dizaines ou centaines de milliers voire en millions, voire... Facebook :)
4. Mais surtout, concevoir une application, ce n'est pas l'utiliser. Le temps et la répétition sont seuls à pouvoir apporter certaines réponses, seuls aussi à pouvoir poser certaines questions.

__Nous, informaticiens, devons donc nous déclarer "incompétents" et faire confiance à l’utilisateur pour savoir ce dont il a besoin.__

C'est justement l'une des vertus de l'agilité que de remettre l'utilisateur au centre : le _Minimum Viable Product_, le rythme soutenu des mises en production, les tests utilisateurs (sur maquettes, sur prototype, AB-Testing...) sont autant de moyens d'organiser le recueil régulier du feedback utilisateur, sans lequel il n'est pas de bonne application.


### Gagner la confiance du client
Posons-le tout de suite : le besoin étant dicté au fur et à mesure par l’utilisateur et non le client, __agilité et cadre contractuel forfaitaire ne sont pas compatibles__. Un fournisseur ne peut pas s'engager à réaliser "quelque chose" (engagement de résultat) quand ce "quelque chose" n'est pas identifié au départ. L'agilité implique donc un engagement de moyens de la part du fournisseur.

A noter que cela n'empêche en rien le client d'établir un budget pour l'application qu'il souhaite mettre en œuvre, ce budget représentant ce qu'il est capable de dépenser et prêt à dépenser. Seulement ce budget n'est pas associé à un périmètre fonctionnel clairement défini. Le _budget_ d'un client n'est donc pas l'_engagement forfaitaire_ d'un fournisseur, et notre client devra peut-être défendre un budget de 500K€ sur base d'une note d'intention A4 recto-verso, et ultérieurement rendre des comptes sur ce budget !

Nous mettons ainsi le doigt sur l'une des principales difficultés de l'agilité : une très grande confiance doit exister entre un client et son fournisseur pour qu'un projet puisse se dérouler dans le cadre d'un engagement de moyens. Parce que la confiance règne, le client sait qu'il en aura pour son argent. Mais une telle modalité implique concrètement que le risque financier soit entièrement assumé par le client. En cela, ce dernier reconnaît combien ses actions déterminent la maîtrise des coûts et des délais, actant de ce fait la __responsabilité__ qui est la sienne dans la réussite globale du projet. Le [Guide Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf) ne dit pas autre chose : _"Le Product Owner est responsable de maximiser la valeur du produit et du travail de l’Équipe de Développement"_. Dans les faits, cela signifie : prioriser les fonctionnalités à mettre en œuvre, fournir les informations à temps et décider sans délai.

Atteindre ce niveau de confiance est un défi difficile à relever. C'est d'ailleurs pour cette raison que l'agilité est une modalité que l'on rencontre souvent en dehors du cadre contractuel client-fournisseur, au sein de start-up, éditeurs de logiciels ou de grands groupes dont les équipes sont constituées exclusivement de salariés.

Relever ce défi nécessite de travailler plus que jamais dans __une optique de partenariat__ sincère et "généreuse" avec son client, cette générosité devant s'exercer dans les deux sens. Nous devons lutter pour retrouver cet esprit, enterré depuis longtemps par les notions de _périmètre_ et d'_écarts de périmètres_ qui cristalisent les crispations.

De ce point de vue, la __proximité physique__ des membres de l'équipe est un atout considératible : quand distance rime avec défiance, la proximité, elle, est source de confiance. Quoi de mieux en effet que la multitude d'interactions informelles qu'offre une journée de travail pour apprendre à se connaître ? Quoi de mieux que le langage corporel pour savoir que l'on peut faire le premier pas et accorder sa confiance à autrui ? Des rendez-vous ponctuels et formels peuvent-ils vraiment rivaliser avec cela ?


### Faire confiance à l’équipe de développement
Il serait temps, enfin, de faire confiance aux membres de l'équipe de développement, qu'il s'agisse d'analystes/concepteurs fonctionnels ou de développeurs. Quelqu'un pourrait-il mieux que ces derniers évaluer la complexité d'une fonctionnalité à mettre en œuvre ? Ces derniers ne sont-ils pas suffisamment autonomes et responsables pour, d'eux-mêmes, améliorer continuellement leur façon de travailler en équipe ?

Mon expérience personnelle m'a conforté dans l'idée que l'on obtient le meilleur de chacun en adaptant son style de management à ses besoins tout en favorisant son autonomie et sa responsabilisation. L'agilité, ou à tout le moins [le cadre méthodologique Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-FR.pdf), tire les conséquences logiques de ce postulat et propose de faire confiance à l'équipe elle-même pour améliorer avec le temps son fonctionnement et sa productivité. Cela fait écho aux nouvelles organisations du travail, plus horizontales et responsabilisantes, décrites par Frédéric Laloux dans son ouvrage [_Reinventing Organizations_](https://www.amazon.fr/dp/2354561059).


Plus de chef de projet, donc, mais un _Scrum Master_ __"au service de l'équipe"__, avec une différence fondamentale : le premier dirige, le second facilite et conseille. Intellectuellement, passer d'un positionnement à l'autre n'a rien de bien compliqué, mais la difficulté réside dans l'importance qu'accorde actuellement l'industrie informatique au chef de projet. Le management y voit un demi-dieu tant il se fait rare, en tout cas un homme providentiel sachant tout faire, un meneur d'hommes qui incarnera fièrement le projet. Le développeur ou l'analyste fonctionnel nouvellement promu chef de projet se voit quant à lui enfin élevé au premier niveau de hiérarchie, parce que c'est ça, réussir socialement.

Loin de moi l'idée que l'on puisse se passer de management, bien au contraire. Mais souhaitons ensemble un management recentré sur sa fonction première : orienter, inspirer, fédérer, c'est-à-dire donner du sens au travail, ce qu'[André Comte-Sponville](https://www.youtube.com/watch?v=TBuRaS1L6aI) a su expliquer de manière lumineuse. Autrement dit, un management qui s'intéresse au _"pourquoi"_ plus qu'au _"quoi"_ (l'utilisateur) et en tout cas pas au _"comment"_ (l'équipe elle-même).

L’organisation interne des entreprises de services informatiques s’en trouve donc profondément chamboulée. Que faire de tous ces chefs de projets ? [Certaines entreprises](http://www.theodo.fr/), parce qu'elles sont jeunes et n'ont connu que l'agilité, l'ont compris et se sont structurées en conséquence. Pour les autres, c'est un profond changement de culture.

C'est aussi à mes yeux l'occasion de donner au développeur la place centrale qu'il mérite, et qu'il va souvent chercher Outre-Atlantique à défaut de la trouver en France. Comment expliquer que la voie dite "technique" soit à ce point déconsidérée, avec des écarts de salaires du simple au double séparant un développeur d'un chef de projet ? De l'expertise technique et l'expertise managériale, l'une vaut-elle plus que l'autre ? Cessons de croire qu'un développeur est un "pisseur de code", comme je l'ai parfois entendu. Développer efficacement suppose une compréhension avancée de systèmes très complexes, une rigueur infinie, beaucoup de connaissance de soi et de grandes capacités relationnelles. Qu’est-ce qu’un bon développeur sinon déjà un architecte en devenir ?


### Conclusion
La confiance, c’est le lâcher-prise. Accepter de faire le premier pas. La meilleure façon de savoir si l'on peut faire confiance à quelqu'un, c'est de lui faire confiance.
Phase de transition : tenter notre chance sur des appels d’offres à moindres enjeux pour constituer nos premières références.