---
date: 2016-01-12T19:00:00
publishDate: 2016-01-05
tags:
- young blood
title: "Young blood III : No Retreat"
videos:
---

## Date et lieu

- Mardi 12 janvier 2016
- Dans [les locaux de l'ESIEA]({{< ref "/location/esiea.md" >}})

Les inscriptions seront ouvertes le jeudi précédent l'évènement. Suivez aussi le Parisjug sur Twitter ([@parisjug](https://twitter.com/parisjug)) pour être informé rapidement.
- Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.
- Les inscrits à l'évènement non présents 5 min avant le début de la session, soit à 19h25, verront leur place remise à disposition
- Les non inscrits à l'évènement ne pourront donc y assister que sous réserve de places disponibles sur place 5 min avant le début de la session, soit à 19h25.
- L’inscription implique de posséder une adresse mail valide sur laquelle vous recevrez une demande de confirmation à laquelle il vous faudra répondre afin de valider votre inscription. Toute inscription non confirmée ne sera pas prise en compte !


## Comment se déroule un Quicky Young Blood ?

- C'est une présentation entre 15 et 20 minutes avec 1 seul speaker.
- Il y a 15 minutes de présentation et 5 minutes de questions
- Le speaker répond aux questions pendant que le suivant s'installe.
- Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.
- Les inscrits à l'évènement non présents 5 min avant le début de la session, soit à 19h25, verront leur place remise à disposition
- Les non inscrits à l'évènement ne pourront donc y assister que sous réserve de places disponibles sur place 5 min avant le début de la session, soit à 19h25.
- L’inscription implique de posséder une adresse mail valide sur laquelle vous recevrez une demande de confirmation à laquelle il vous faudra répondre afin de valider votre inscription. Toute inscription non confirmée ne sera pas prise en compte !


## Photos


{{< flickr id="72157675432872413" img="https://live.staticflickr.com/528/31447028714_5d15fff354_h.jpg" >}}


## Détails

### 19h15 à 19h30: Accueil

19h30 - Réaliser une bonne recette grâce au concombre

À travers un live-coding, je vais mettre en pratique un exemple de BDD (Behavior Driven Development) avec Cucumber.

Nous allons voir comment réaliser un backend en Java exposant une API REST définie dans des fichiers Gerkin, testée à l'aide de cucumber-jvm. Cette démonstration nous permettra de constater qu'un backend peut être couvert par des tests fonctionnels et qu'une couverture de code importante peut être obtenue en adoptant de bonnes pratiques de développement et avec un effort modéré.

Pour aller plus loin j'introduirais comment travailler avec le Métier pour que les tests fonctionnels soient en adéquation avec leur besoins et comment ceux-ci peuvent les amener au TDR (Test-Driven Requirements) dans la gestion et le suivi de projet.

Par Shoun Ichida ([Présentation](ICHIDA-Young Blood 2016.pdf))


### 19h50 - Spock, un framework de test venu d’une autre planète
Les tests unitaires peuvent parfois provoquer de fortes émotions chez le développeur. Heureusement pour nous, Spock nous permet de maitriser ces émotions grâce à la logique et l’expressivité. Durant ce talk, je vous ferait faire un tour d’horizon rapide de Spock et de ses capacités.

Par Xavier Detant

## 20h10 - Une stack logicielle de géolocalisation et geofencing à faible consommation d’énergie pour applications mobiles
En quelques années, la localisation est devenue l’une des données personnelles les plus prisées. Un grand nombre d’applications web et mobile utilisent cette information pour proposer des résultats plus pertinents (sites d’information, réseaux sociaux...) ou se reposent sur les systèmes de géolocalisation des terminaux des utilisateurs pour proposer des fonctionnalités supplémentaires (navigation, réalité augmentée…).

Aujourd’hui, il n’existe pas d’architecture généraliste standard permettant la mise en place simple de ce genre de services, et le développement de telles fonctionnalités en dehors de tout framework nécessite par ailleurs beaucoup de travail tout en soulevant un ensemble de problèmes techniques : diversité des terminaux clients et des méthodes de géolocalisation, précision, consommation énergétique, stockage et exploitation des données géographiques…

Dans ce talk, je présenterai un exemple de stack logicielle permettant la mise en place efficace de ces services : Android et son API Location pour le client mobile, Google Cloud Messaging pour le système de notifications push, Tomcat pour le backend serveur et PostgreSQL/PostGIS pour la manipulation des données géographiques.

Je montrerai ensuite comment un tel écosystème permet d’implémenter des fonctionnalités avancées comme l’analyse statistique des données de géolocalisation ou le geofencing (envoi de notifications déclenché par l’entrée de l’utilisateur dans une zone géographique donnée).

Je terminerai en proposant quelques concepts d’applications mobiles basées sur ces technologies et des pistes de réflexion dans le domaine de la géolocalisation.

Par Romain Vernoux


### 20h30 à 21h00 : Buffet Sponsorisé par Innovation-Box

{{< figure src="/img/sponsors/2016/innovation-box.png" alt="InnovationBox" class="sponsor-svg-logo" >}}


### 21h00 - Pour un front plus digeste, saupoudrez de feuilles de thym !!

Le sujet principal de la présentation est Thymeleaf. L'idée est de montrer à quel point il est simple d'utiliser Thymeleaf au sein d'un de ses projets et de le customiser afin qu'il réponde à toutes vos attentes.Voici le plan de la présentation :

- Qu'est ce que Thymeleaf ?
- La syntaxe Thymeleaf...
- Intégration avec les frameworks (Spring, Spring-boot, Play, Spark, ...)
- Niveau customisation ? La magie des ""dialects"" !
- En terme de perf : Thymeleaf face à ses concurrents.
- Petite démo

Par Patrick Allain ([Présentation](thymeleaf.pdf))


### 21h20 - La recette pour déployer des applications microservice avec Ansible
Durant le présentation, je vais exposer une recette pour déployer une architecture micro-service avec Spring Boot hautement disponible avec Ansible, Haproxy et SupervisordLa quicky est composé de trois parties :

- Première partie : La présentation (10 mn) nous allons introduire Ansible et ses concepts (play-book, inventery-file, les modules ) , Haproxy et supervisord.
- Deuxième partie : La recette (5 mn ) dans cette partie nous allons expliquer la recette pour pour le déploiement et l'interaction entre ces composants pour assurer la haute disponibilité.
- Troisième partie : La démo (5 mn ), Durant la démo , on va déployer la stack sur des vm , puis en tuant une instance , on montrera comment le service reste toujours assuré et un nouveau sera lancer en parallèle
Pour le moment le nom n'est pas très accrocheur , mais si la présentation est accepté je vais en trouvé un plus sexy ;)

Par Walid Chergui



### 21h40 - Java Agent en Action

Les agents java permettent d’observer et de modifier des programmes exécutés sur une JVM. Bien que présents depuis le JDK 1.5, ils sont très peu utilisés hormis par des outils avancés comme New Relic, JProfiler ou JRebel.A travers un exemple concret, on verra sur quels principes les agents se reposent et comment en créer un facilement.

Par Yoann Buch ([Présentation](Java-Agent-en-Action.pdf))

# 22h00 - Maven, c'est bien, SBT c'est mieux!

Sous ce nom de session trollesque se cache une présentation de l'outil SBT. L'idée est de mettre en avant ce que SBT peut apporter en plus dans le quotidien du développeur comparé aux outils reconnus tel que maven.

Nous parlerons ici de son utilisation au sein de projets Java même s'il s'est développé conjointement avec le scala. Durant cette présentation, nous verrons les fonctionnalités clefs qui pourront influencer vos choix sur vos projets.

Par Fabrice Sznajderman ([Présentation](SBT-parisJug2016.pdf))


### 22h20 - Résultats


### 22h10 à ...

3ème mi-temps des juggers dans un lieu sélectionné par votre Crew ;-)

{{< sponsor-section >}}

{{% coc-section %}}
