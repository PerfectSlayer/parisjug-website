---
date: 2014-01-14T19:30:00
publishDate: 2015-02-23
tags:
- young blood
title: "Soirée Young blood I"
videos:
---

## Date et lieu

- Mardi 14 janvier 2014
- Dans les locaux de l'[ISEP]({{< ref "/location/isep.md" >}})

La soirée young blood est une volonté d'offrir aux personnes n'ayant jamais fait de présentation de se lancer.

Comment ce déroule un quickies young blood ?
- C'est une présentation entre 15 et 20 minutes avec 1 seul speaker.
- Il y a 15 minutes de présentation et 5 minutes de questions
- Le speaker réponde au question pendant que le suivant s'installe.

Les inscriptions seront ouvertes le jeudi précédent l'évènement. Suivez aussi le Parisjug sur Twitter ([@parisjug](https://twitter.com/parisjug)) pour être informé rapidement.
- Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.
- Les inscrits à l'évènement non présents 5 min avant le début de la session, soit à 19h25, verront leur place remise à disposition
- Les non inscrits à l'évènement ne pourront donc y assister que sous réserve de places disponibles sur place 5 min avant le début de la session, soit à 19h25.
- L’inscription implique de posséder une adresse mail valide sur laquelle vous recevrez une demande de confirmation à laquelle il vous faudra répondre afin de valider votre inscription. Toute inscription non confirmée ne sera pas prise en compte !

## Détails

### 19h15 à 19h20 : Accueil

### 19h20 - apt-get myapp ! - Déployer ses applications Java sous Debian

Développer une application c'est bien, mais la déployer facilement sur ses serveurs ou chez ses utilisateurs c'est mieux. Les amateurs de systèmes Debian/Ubuntu ont l'habitude d'installer leurs applications en quelques secondes en tapant 'apt-get install', et cette facilité d'utilisation est aussi à la portée des développeurs d'applications Java.

Cette présentation propose de montrer comment construire facilement un package Debian avec jdeb (http://github.com/tcurdt/jdeb), ou plus difficilement avec les outils Debian mais avec à la clef la possibilité d'une distribution dans l'archive officielle Debian.

Par Emmanuel Bourg

### 19h40 - JVM Tools: The hard way

Cette session vous propose une piqûre de rappel (ou découverte) des outils fournis dans le JDK, mais pas n'importe lesquels: oubliez fenêtres, contrôles, les couleurs et les graphes animés, il sera essentiellement question du terminal!

Que vous soyez un nerd ne jurant que par la pureté de la ligne de commande ou bien simplement un dev à la recherche d'un kit de survie dans un environnement dépourvu d'interface graphique, venez passer en revue les informations que la JVM tient à votre disposition et qui permettent d'en apprendre énormément sur comportement de vos applications: de la configuration de la JVM, en passant par l'état de la mémoire, des threads ou encore l'activité du Garbage Collector et du JIT.

Par Brice Leporini

### 20h00 - Les IHM riches en Java ne sont pas mortes : tour d'horizon de Java FX

Dans cette présentation, nous découvrirons ensemble celui qui se pose désormais en successeur de Swing, j'ai nommé Java FX 2 (ou 8, pour ceux qui aiment les developper preview).

Décoration en css, spécification des ihm en xml, animations et effets graphiques, accélération matérielle, rendu web (WebKit), bindings, mais aussi impression, support multimédia (y compris l'enregistrement), support du multitouch... Il y en a sous le capot!

Alors embarquez pour un petit tour d'horizon de cette techno, pour vous convaincre que le client riche n'est pas mort :)

Par Simon Basle

### 20h20 - Des recommandations au service du business
Le but de cette présentation est d'aborder les systèmes de recommandations du point de vue business.

Que peut apporter un système de recommandations ? Pourquoi le mettre en place ? Que peut-on en attendre ?

L'objectif de la présentation est de répondre à ces interrogations en s'appuyant sur différents cas d'utilisation concrets.

Les grandes lignes de la présentation :

- qu'est-ce qu'un système de recommandations ?
- quel est le but d'un système de recommandations ?
- comment rendre son système plus efficace ?
- quels sont les enjeux actuels ?

Par [Loïc Knuchel]({{< ref "/speakers/loic-knuchel" >}})

### 20h30 à 21h00 : Buffet

{{< figure src="/img/sponsors/2015/innovation-box.png" alt="Innovation Box" class="sponsor-svg-logo" >}}

### 21h10 - Recommandation avec PredictionIO

Sur Amazon, n'avez-vous pas déja remarqué cette fameuse phrase ""Les clients ayant consulté cet article ont également regardé..."" ?

Derrière cette phrase, il y a un moteur de recommandation (un des domaines du machine learning).

Envie de faire la recommandation, mais pas top calé sur les algorithmes de machine learning ? Envie de découvrir l'envers du décor ?

PredictionIO est un serveur qui permet justement de faire de la recommandation sans avoir trop de pré-requis.

L'idée de cette présentation est de montrer comment l'utiliser via des uses cases, puis de voir ses avantages et limitations.

Par Ludwine Probst

### 21h30 - Pimp my Inter Thread Communication (aka Inter-Thread Messaging Architecture) "

Pour faire transiter des messages entre threads on utilise le plus souvent une queue comme medium de transport.
C'est par compliqué à mettre en œuvre, et l'api est assez simple.
En revanche si on veut passer du HelloWorld (1 thread qui produit -> une Queue comme medium -> un/plusieurs thread qui consomme) à une archi plus complexe par exemple:

1. Un producteur avec plusieurs consommateur qui consomment en parallèle le même message.
2. Un producteur avec plusieurs consommateur qui consomment en parallèle des messages différents
3. Une architecture Diamond [Producer ->(consumer-1 parallèle à consumer-2) -> consumer 3

La tache se complique, sans oublié la gestion du locking.
Une solution qui allie simplicité, élégance mais aussi haute performance et open source est proposée par LMAX (Plateforme de trading), qui se prénomme Disruptor.
Durant cette présentation, nous allons voir le cœur du Disruptor (RingBuffer aka CircularBuffer) et aussi comment implémenter ces différents cas d'utilisation vu au dessus.
Voici le pitch de LMAX sur disruptor (http://www.lmax.com/disruptor)
LMAX Disruptor is a software pattern and software component for high performance inter-thread communication that avoids the need for message queues or resource locking.
LMAX Exchange has open-sourced the Java implementation of the Disruptor component and a number of other libraries.

Par Hichame El Khalfi

### 21h50 - Apéritif dinatoire avec Clojure et Overtone

Clojure est un langage fonctionnel puissant qui peut être très utile pour des traitements parallèles ou la manipulation de grand nombre de données.
Mais Clojure peut être aussi utile pour faire de la musique !
Je vous propose donc au cours de ce quickie récréatif une séance de livecoding qui présentera pas à pas quelques exemples de code musicaux basés sur Clojure et Overtone.

Par Mathieu Gandin

### 22h10 - résultats

## 22h10 à ... : 3ème mi-temps des juggers au Vavin

### Télécharger les présentations

- Apéritif dinatoire avec Clojure et Overtone : https://github.com/mgandin/lightning-talk-clojure-overtone
- [apt-get myapp ! - Déployer ses applications Java sous Debian](2014-01-04ParisJUG-PackagingDebianpourJava.pdf)
- [JVM Tools: The hard way](jvmtools.pdf)
- [Les IHM riches en Java ne sont pas mortes : tour d'horizon de Java FX](JavaFxTour.pdf)
- [Des recommandations au service du business](Desrecommandationsauservicedubusiness-15minJUG.pdf)
- [Recommandation avec PredictionIO](PredictionIO5.pdf)
- [Pimp my Inter Thread Communication (aka Inter-Thread Messaging Architecture)](prez-disruptor-young-blood-2014.pdf)
- [Apéritif dinatoire avec Clojure et Overtone](parisjug-clojure-overtone.pdf)
