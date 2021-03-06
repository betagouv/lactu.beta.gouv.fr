---
layout: post
title: "Améliorer la documentation beta.gouv : 12 mois d'apprentissage !"
date: 2021-05-18
authors:
  - lery.jicquel
categories: dinsic
image: /img/posts/photo-1457369804613-52c61a468e7d.jpg
excerpt: >-
  Depuis plus d'un an, je m'investis avec d'autres collègues sur un sujet
  transverse : l'amélioration de la documentation à destination des membres des
  incubateurs et des Startups d'Etat ou de Territoires.

  Je vous partage nos apprentissages.
---
## La documentation, c'est quoi exactement ?

L'encyclopédie en ligne Wikipédia fournit deux définitions assez simples : 

* Documenter est l'action de sélectionner, classifier, utiliser, et diffuser des documents. 
* Une documentation informatique est un système qui fournit à la demande des réponses supposées pertinentes, sélectionnées dans un ensemble de connaissances préalablement mémorisées.

## Un pré-requis : aimer documenter !

Avant de vous en dire plus sur ce chantier de la documentation de beta.gouv, je pensais utile de vous expliquer pourquoi je me suis naturellement penché sur la question et quelle était mon expérience passée sur le sujet. 

Je pense utile d'en parler car en 12 mois, ce fut un de mes apprentissages : pour beaucoup de monde c'est barbant de documenter même si tout le monde est content d'en profiter.

Améliorer de la documentation n'est donc pas fait pour tout le monde et c'est bien normal.

Depuis plus de dix ans, j'ai une appétence pour l'écriture au sens large : 

* Je publie des articles toutes les deux semaines depuis plus de 6 ans sur un blog personnel consacré au secteur du vélo ;
* Je publie régulièrement sur le blog de bêta comme la série de [10 interviews d'intrapreneures et d'intrapreneurs](https://blog.beta.gouv.fr/pole-emploi/2020/07/17/paroles-dintrapreneuses-4-sylvie-lebel-de-la-startup-zen-de-pole-emploi/) ;
* Durant mon parcours à la Cour des comptes, 50% de mon activité était consacrée à la rédaction des rapports contenant entre 50 et 120 pages dans un style très administratif. Le reste était consacré à l'analyse et aux contrôles ;
* Lorsque j'étais intrapreneur, j'avais un peu l'obsession de tout documenter : [nos rituels d'équipe](https://blog.beta.gouv.fr/dinsic/2020/05/25/retex-rituels-de-sprint-de-lequipe-e-controle-titre-provisoire/), [mes apprentissages](https://blog.beta.gouv.fr/dinsic/2019/02/13/comment-recolter-les-irritants-dun-maximum-d-utilisateurs-en-tres-peu-de-temps/), nos notes de réunions...
* Quand je travaillais en collectivité territoriale, j'ai "pondu" de nombreuses notes synthétiques pour aider à la prise de décision des élus et de la direction générale ;
* Je propose des formations à la rédaction de posts engageants sur les réseaux sociaux ;
* Enfin, je suis no-codeur à mes heures perdues et je suis capable de passer une heure à naviguer dans les documentations de ces solutions quand elles sont vraiment bien conçues;

J'ai donc un biais naturel pour "l'écriture" même s'il m'arrive de faire des fautes d'orthographe et que je n'ai pas encore de roman à mon nom.

![Page d'accueil de notre documentation](/img/posts/doc-beta.jpg)

**Page d'accueil de notre documentation**

## Beta.gouv a, par essence, une forte culture de la documentation

Quand on pense, comme moi, que la documentation est un levier d'amélioration continue d'un groupe, d'un service ou d'une organisation, on ne peut pas rêver mieux que de travailler chez beta.gouv.
Ce programme lancé en 2013, n'a cessé de documenter ses apprentissages et son mode de fonctionnement depuis ses origines. En effet, parmi les piliers de l'approche "Startup d'Etat" on retrouve les notions de transparence (montrer/exposer ce qu'on fait) et d'amélioration continue (montrer ce qu'on a appris). 
Ainsi, par rapport à d'autres organisations, beta.gouv était déjà très en avance en la matière néanmoins il restait encore des choses à améliorer. 

## Une documentation riche mais dispersée

Concrètement, on retrouvait l'application de ces principes de transparence et d'amélioration continue dans les témoignages, interviews et retours d'expérience disponibles sur notre blog mais aussi dans divers autres espaces : un "wiki" Github, des pads (sorte de documents en ligne de prises de notes) et divers espaces de stockages de documents en ligne.
Malgré cette riche documentation, elle était dispersée et pas suffisamment découvrable.
Alors que nous sommes en forte croissance, le "coût d'entrée" pour les nouveaux était parfois jugé élevé. Il était difficile pour eux de savoir où trouver ces informations et parfois même de simplement connaître leur existence.
En outre, pour les plus anciens qui détenaient ses connaissances ou qui étaient capables de naviguer d'un espace de documentation à l'autre, ils pouvaient avoir le sentiment de devenir de véritables goulots d'étranglement. Ils étaient sollicités plusieurs fois par semaine pour la même chose alors que l'information était disponible dans un pad ou sur une page du wiki.
Ainsi seule une minorité de membres de la communauté était autonome pour exploiter pleinement cette riche documentation. 
Enfin l'amélioration de cette documentation était ralenti par la méconnaissance de son existence par une majorité de nos membres.

C'est pour essayer de résoudre ces difficultés qu'avec un petit groupe, nous avons décidé de nous intéresser un peu plus à l'amélioration de la documentation de beta.gouv. Nous y avons passé quelques heures chaque mois.

![Admin gitbook beta](/img/posts/admin-gitbook.jpg "Page d'administration du Gitbook de beta.gouv")

**Page d'administration du Gitbook de beta.gouv**


## Comment avons-nous amélioré notre documentation ?

### Première itération : rassembler et communiquer (Avril à septembre 2020)

Voici les étapes que nous avons suivi : 

1. **Monter une petite équipe de volontaires**. Avec Jérémie et Mathilde, nous avons débuté à trois. Au fil des étapes exposées ci-dessous, nous avons été rejoins par de nouveaux collègues ;
2. **Référencer et trier les différents "espaces"** où dénicher de la documentation de beta.gouv ;
3. **Solliciter les apprentissages de la communauté : "quels sont les outils que vous pourriez nous recommander en matière de documentation ?"**. De nombreuses équipes nous ont recommandé [Gitbook](https://www.gitbook.com/). Elles utilisent cette solution SAAS pour leurs Startups d'Etat ou de Territoires. Nous avons démarré avec cette solution qui est par ailleurs gratuites pour les ONG et les services publics.
4. **Rassembler toute[ la documentation dans Gitbook](https://doc.incubateur.net/communaute/)** en éclatant les contenus en trois guides : les infos pour les membres, pour la communauté et un focus design. Ce fut notre première erreur sur laquelle nous reviendront plus bas. Enfin, nous avions pris le parti de ne pas modifier le contenu des documents et supports regroupés.
5. **Rendre découvrable cette documentation** : 

   * proposer un créneau récurrent et mensuel à ceux qui souhaitent en savoir plus, 
   * intégrer des liens vers la documentation dans chaque infolettre hebdomadaire, 
   * présenter cette documentation lors des sessions d'embarquement pour les nouveaux (elles ont lieu toutes les 6 semaines) ;
   * créer des messages automatiques dans notre messagerie d'entreprise renvoyant vers certaines pages de notre documentation. Par exemple, si quelqu'un écrit "documentation de beta" dans un message, alors il obtient une réponse automatique contenant un lien vers la documentation de beta ;
   * création d'un canal de discussion spécifiquement sur la documentation afin de répondre aux questions ou aux demandes ;
   * enfin un lien vers dans la documentation dans les emails de bienvenus adressés aux nouveaux membres ; 
6. Essayer de **faciliter les contributions à la documentation**. Cette étape est encore à améliorer. Nous en parlerons plus bas ;
7. **Mesurer l'usage de cette documentation et rendre cette information publique**. Les statistiques d'usage de notre documentation sont donc disponibles [en ligne](https://datastudio.google.com/reporting/1016657e-1ee3-4013-919d-0e0fb284e352/page/1M). Vous saurez le nombre de visiteurs et les pages les plus consultées ;
8. **Considérer la documentation comme un produit** et donc l'améliorer en continu.

Cette démarche nous a permis de rassembler toute la documentation dans trois guides thématiques gérés par un seul outil : Gitbook.
Nous avons également communiqué de façon continue pour faire connaître cette documentation à tous les membres de la communauté. 

![Stat documentation de beta](/img/posts/stat-beta.jpg "Stat documentation de beta")

**[Page de stats ](https://datastudio.google.com/u/0/reporting/1016657e-1ee3-4013-919d-0e0fb284e352/page/1M)de la documentation de beta.gouv**

### Deuxième itération : fusionner et réécrire (Septembre à Mars)

Les premiers résultats étaient encourageants.
Nous avions à la fois des retours qualitatifs positifs à travers des verbatims récoltés à l'écrit ou à l'oral.

Néanmoins, nous récoltions également des critiques : 

* "Je ne sais jamais où retrouver le guide"
* "je ne comprends pas la différence entre les trois guides"
* "J'ai du mal à trouver l'information que je cherche dans le guide"
* "Je ne comprends pas comment sont organisés les guides"
* "Comment je peux modifier les guides? ce n'est pas clair pour moi"
* "Les informations utiles sont un peu noyées car les contenus sont denses"

En résumé, nous avons appris que nous étions sur le bon chemin car nous délivrions déjà de la valeur ajoutée mais qu'ils nous restaient encore quelques défis à relever : simplifier et rendre plus actionnable.

Nous avons donc lancé plusieurs démarches en parallèle pour y arriver.

#### 1. Fusionner les deux principaux guides grâce au "tri par cartes"

Nous avons sollicité la communauté pour réorganiser le contenu des deux principaux guides afin de les fusionner. Avec l'aide de Raphaël Yharrassarry, designer, nous avons appliqué la méthode du tri par cartes. Je vous recommande [l'article](https://blocnotes.iergo.fr/concevoir/les-outils/tri-par-cartes-card-sorting/) de Raphaël sur le sujet. 
Comme il l'explique : 

> Le principe du tri par cartes est de demander aux utilisateurs de regrouper des intitulés de rubriques ou de pages d’un site ou d’un service, dans des catégories et de nommer ces catégories. Suite à cela, un traitement statistique permet de faire apparaître les regroupements faits par l’ensemble des utilisateurs. C’est un outil extrêmement puissant pour impliquer un grand nombre d’utilisateurs et simple à mettre œuvre.

Nous avons obtenu 50 contributions (sur une communauté de 500 membres) et avons pu fusionner les deux guides en un seul. Nous nous sommes appuyés sur les résultats du tri par cartes pour fabriquer le sommaire et le classement de l'information.

Voici quelques illustrations d'Optimal Workshop, la solution utilisée pour nous aider à organiser l'information de notre guide : 

![diagramme doc](https://user-images.githubusercontent.com/43180136/118452442-72d98480-b6f6-11eb-8999-bbec24f0cf8f.JPG "Extrait de la vue 3D des groupes d’information")

**Extrait de la vue 3D des groupes d’information**

![similatry](https://user-images.githubusercontent.com/43180136/118452564-943a7080-b6f6-11eb-8c95-efcdd2ba5234.JPG "Extrait d’une partie de la matrice carte par carte")

**Extrait d’une partie de la matrice carte par carte**

#### 2. Améliorer la rédaction des 10 pages les plus consultées

Avec l'aide d'Anne-Sophie Tranchet, également designer, nous avons réalisé quelques séances de corédaction (pair-writing) afin d'améliorer le contenu des 10 pages les plus consultées. 
A la différence d'un texte administratif qui cherche à être exhaustif et précis, ou d'un article de blog qui vise à retenir le lecteur le plus longtemps possible, une documentation vise au contraire à apporter le plus rapidement possible l'information utile aux visiteurs (l'inverse du texte que vous êtes en train de lire...). 
D'une certaine manière, on pourrait dire que moins un visiteur passe du temps sur une documentation mieux c'est. L'objectif est de lui fournir le plus efficacement possible ce qu'il recherche. 
Ainsi :

* les boutons d'action ont été ajoutés en haut de page ;
* les redondances dans une même page ont été effacées ;
* les idées contenues dans les paragraphes ont été éclatés en "puces" ;
* l'information a été découpée et schématisée (tableau, fiche...) ; 
* surtout le contenu a été réduit au maximum.

![visio](https://user-images.githubusercontent.com/43180136/118453240-42deb100-b6f7-11eb-92fb-19c41348dff3.JPG "Illustration")

**Illustration d'une page retravaillée**

#### 3. Rendre encore plus découvrable la documentation en la rendant accessible depuis le site de beta.gouv.fr

L'équipe en charge de la refonte du site internet de beta a décidé d'ajouter un lien direct vers notre documentation.
Ainsi, le point d'entrée le plus naturel pour retrouver le lien vers notre guide est le site internet. Rien de plus normal mais on y avait pas pensé plus tôt!

![Landing page beta.gouv.fr](/img/posts/landing-page.jpg)

**Page d'accueil de beta.gouv.fr avec lien vers la documentation**

### Prochaine itération ?

Ces dernières itérations nous ont permis de simplifier la documentation et de la rendre plus digeste et découvrable.

Néanmoins, il reste encore des difficultés à résoudre : 

* si le nombre de contributeurs à la documentation a augmenté, de nombreux collègues buttent encore à y arriver. Plusieurs causes peuvent l'expliquer : le syndrome de l'imposteur et une synchronisation parfois déficiente entre les répertoires github et notre espace Gitbook.
* l'usage d'un outil propriétaire. Gitbook pourrait décider du jour au lendemain de rendre son usage payant.
* il existe encore quelques guides autonomes comme celui des designers de beta ou celui consacré à la phase de transfert qui pourraient être rapatriés dans le guide principal.

- - -

Si vous souhaitez échanger sur le sujet de la documentation, n'hésitez pas à me contacter par email lery.jicquel@beta.gouv.fr ou sur [Linkedin](https://www.linkedin.com/in/l%C3%A9ry-jicquel/).