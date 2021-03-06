---
layout: post
title: "Développeurs freelance et internes : retour d'expérience pour une collaboration efficace"
date: 2020-07-02
categories: fabnumdef
authors:
  - romain.perroud
tags: [Retex, Développement]
image: https://images.unsplash.com/photo-1513346940221-6f673d962e97?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&q=80
excerpt: >-
  À la Fabrique numérique, nous avons deux missions principales :
  réaliser nous-mêmes les meilleurs services et produits numériques & aider les autres à faire de même.

---

Pour nos premiers produits, nous nous sommes focalisés sur la première de ces deux missions. Il s'agissait surtout de faire nos preuves et montrer notre valeur ajoutée avant d'épauler les autres.

La seconde, bien qu’aussi importante, est également la plus délicate. Déjà, il est important de définir qui sont « les autres » avant de se demander « comment » les aider. Au sein du ministère des Armées nous disposons de Centres de Développement d'Applications de la Défense : les CDAD. Au nombre de quatre, répartis sur l'ensemble du territoire national, ils sont chargés de développer les outils numériques pour l'ensemble du ministère. Assez naturellement, il nous a semblé évident de commencer à collaborer avec eux. Mais si nous avons des missions assez proches et des métiers très similaires, nos contraintes ne sont pas les mêmes et nos maturités technique et [Agile](http://agilemanifesto.org/iso/fr/manifesto.html) assez inégales.

Les difficultés avec lesquelles nous devons composer sont donc structurelles. Il ne s'agit plus de monter des équipes d'experts _ad hoc_ qui connaissent leur travail, partagent généralement une même culture produit et délivrent avec la qualité qu'on attend d'eux. Il s'agit ici d'intégrer d'autres personnes venant d'entités différentes, et ayant des habitudes et méthodes de travail différentes.

Plutôt que d'essayer de [planifier dans les moindres détails](https://f14e.fr/2019/09/11/raison-restons-agiles/) comment notre collaboration future allait se passer, nous avons décidé de sauter dans le grand bain et de travailler ensemble sur un premier projet.

Si les objectifs ont été atteints (produit livré et besoins utilisateurs comblés), les résultats en terme de performance et de synergie d'équipe n'ont pas été à la hauteur de nos attentes, que ce soit côté Fabrique numérique ou CDAD.

Qu'à cela ne tienne ! Nous apprenons de nos échanges et de nos expériences et celles-ci nous ont permis de nous améliorer et d'ouvrir la voie à d'autres collaborations efficaces et fructueuses.

Sans prétendre devenir un guide, cet article vise à mettre en lumière nos erreurs passées et les bonnes pratiques que nous utilisons aujourd'hui à la Fabrique numérique lorsqu'il s'agit de travailler de concert avec une autre DSI.

## Nos trois erreurs
Le premier constat que nous avons pu faire est que nos trois principales erreurs ont été commises assez tôt dans le projet, nous empêchant de poser des bases solides pour la suite.

### Erreur n°1 : choix de la _stack_ non consensuel
Déjà, le choix de la stack technique n'a pas été consensuel. À la Fabrique numérique nous avons pour habitude de laisser libre le choix des langages pour nos développeurs _freelance_. Le problème ici est que les CDAD sont contraints sur certaines technologies. Cette décision non concertée à générer quatre problèmes :
- Impossibilité de reprise du projet pour le CDAD (et donc problématique de l'atterrissage post-incubation du produit) ;
- CDAD et _freelance_ ont travaillé sur des parties très différentes du projet avec peu de communication et peu ou pas de revue de code ;
- Cela a conduit au développement de choses en double, pas toujours compatibles et peu pertinentes (qu'il a fallu parfois refaire) ;
- L'impression d'avoir deux projets dans le projet.

### Erreur n°2 : insuffisance de temps de travail avec toute l'équipe en présentielle
Ensuite, nous n'avons pas suffisamment pris en compte le risque d'avoir des membres de l'équipe à distance : d'un côté ceux du CDAD, de l'autre ceux de la Fabrique numérique. Le travail à distance n'est généralement pas un problème quand tout le monde est aligné, transparent et avec un niveau de connaissance assez proche. Mais ici, en plus du décalage technique nous avions également un fossé géographique. Notre erreur a été de ne pas suffisamment réunir l'équipe, au moins au tout début du projet, afin de comprendre le contexte et l'environnement professionnels de chacun, et instaurer ainsi une plus grande confiance et synergie entre les membres de l'équipe. Par conséquent, nous avons dû faire face à :
* Un manque de méthode homogène ;
* Un manque de communication ;
* Un manque d'empathie sur les situations de chacun ;
* Des incompréhensions sur les délais et la qualité attendus, et finalement livrées.

### Erreur n°3 : insuffisance de routines et cérémonies
Finalement, peu de cérémonies et de routines ont été mises en place. Il est parfois compliqué de suivre à la lettre les cérémonie « scrum » ou agile surtout quand il s'agit de travailler avec des _freelances_ qui ne sont pas particulièrement adeptes de celles-ci, et qui les perçoivent parfois comme une perte de temps. Partant du principe que l'agilité doit être embrassée et non imposée, et surtout s'adapter aux individus, nous avons fait l'impasse sur un certain nombre de réunion pour n'en garder que quelques unes : un point hebdomadaire d'une heure pour l'ensemble de l'équipe et des réunions plus ponctuelles en fonction des besoins. Si cela fonctionne très bien sur des start-up d'État constituées de deux développeurs _freelances_, les carences ont été assez évidentes dans le cadre de ce projet réunissant quatre développeurs :
* Absence de communication sur ce qui fonctionne et ne fonctionne pas ;
* Frustration et incompréhension ;
* Manque de synergie et impact sur la dynamique de développement ;
* Limitation de la confiance entre les membres qui ne se parlent pas librement de ce qui ne va pas ;
* Finalement les problèmes sont redescendus par la hiérarchie des CDAD de façon assez inattendue, nuisant ainsi à l'autonomie de l'équipe.


## À quelque chose malheur est bon
Ces trois erreurs ont eu des conséquences directes sur l'équipe du projet :
1. Pour les développeurs du CDAD, un sentiment d'exclusion. Ceux-ci se sont sentis dépossédé du produit sur lequel ils travaillaient et ont eu l'impression de travailler « pour nous » et non pas « avec nous » ;
2. Pour les _freelances_, le sentiment de devoir travailler avec une partie de l'équipe qui les ralentis et les empêchent de délivrer aussi vite et fréquemment qu'ils le souhaiteraient.

Clairement le projet en a pâtit. Si dans les derniers mois nous avons pu redresser la barre, nous n'avons jamais totalement trouvé la fluidité et l'aisance qui font la réussite d'une équipe. Mais cette expérience nous a permis de grandir et d'apprendre sur ce qu'il faut et ne faut pas faire.

Les projets avec d'autres CDAD qui ont suivi nous ont permis de mettre en application ces enseignements. Désormais trois principaux préceptes sont respectés :
* La stack technique est discutée et choisie collectivement. Le choix de cette stack est principalement guidée par le besoin utilisateur et le produit à développer. Elle doit être comprise et utilisable aussi bien par les CDAD que les _freelances_ composants l'équipe. Ces projets sont d'ailleurs l'occasion pour les CDAD de développer des produits sur des technologies nouvelles pour eux et d'apprendre sur le terrain.
* Avant le début des développements, l'ensemble des développeurs se retrouvent pour plusieurs jours de travail (idéalement une semaine) afin de s'aligner sur les méthode de développement et les outils utilisés, en particulier pour la chaîne DevOps.
* L'équipe dans son ensemble s'accorde et s'engage sur les cérémonies à suivre et leur fréquence. L'utilité de chaque cérémonie est discutée et expliquée. Rien n'est jamais figé et nous nous adaptons semaine après semaine.

Nous constatons que ces trois étapes vont permettre à l'équipe :
* d'avoir une cartographie globale des compétences de ses membres. Connaître nos forces et faiblesses, pour s'appuyer sur les premières et atténuer les secondes ;
* de voir les contraintes des uns et des autres (horaires décalés, accès aux informations, à internet, etc.) et composer avec ;
* d'améliorer la confiance et l'esprit d'équipe ;
* de parler plus ouvertement des problèmes à venir ;
* d'améliorer en continu les défaillances organisationnelles ou techniques ;
* de pallier autant que possible aux contraintes de la distance.

## Conclusion
L'approche décrite ici n'est ni exhaustive, ni exclusive. Elle constitue avant tout une première réponse face à une situation défaillante. D'autres limites et problèmes existent et existeront et d'autres solutions devront être appliquées pour les corriger.

Néanmoins, il apparaît clairement que la communication et la transparence de l'information sont essentielles à la réussite d'un produit/projet. Elles n'impliquent pas de fait le succès mais les négliger entraîne inévitablement des difficultés, parfois difficile à surmonter. Cela peut paraître une évidence pour nombre d'entre nous, mais il est éloquent de voir qu'il s'agit pourtant de la principale source de problèmes.

À la Fabrique numérique nous restons convaincu que le principe à la base d'une collaboration efficace est l'égalité des membres d'une équipe face aux choix qui l'impactent dans son ensemble. C'est pourquoi nous œuvrons du mieux possible pour que nos valeurs de bienveillance, d'humilité, de confiance et de transparence soit une réalité plutôt que seulement des mots affichés sur un mur.
