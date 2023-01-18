---
date: 2018-06-27T19:00:00
publishDate: 2018-06-21
tags:
title: "Tools In Action"
videos:
---

## Date et lieu

- Mardi 27 Juin 2018
- Dans les locaux de [Renault Digital]({{< ref "/location/renault-digital.md" >}})

Les inscriptions seront ouvertes le jeudi précédent l'évènement. Suivez aussi le Parisjug sur Twitter ([@parisjug](https://twitter.com/parisjug)) pour être informé rapidement.
- Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.
- Les inscrits à l'évènement non présents 5 min avant le début de la session, soit à 19h25, verront leur place remise à disposition
- Les non inscrits à l'évènement ne pourront donc y assister que sous réserve de places disponibles sur place 5 min avant le début de la session, soit à 19h25.
- L’inscription implique de posséder une adresse mail valide sur laquelle vous recevrez une demande de confirmation à laquelle il vous faudra répondre afin de valider votre inscription. Toute inscription non confirmée ne sera pas prise en compte !


## Détails

### 19h15 à 19h30: Accueil

### 19h30 - KSQL

Apache Kafka est une plateforme de streaming dont on connait les qualités de performance, robustesse, resilience, securité, etc.  
Je vous propose de faire une demo de KSQL qui permet de manipuler les données qui passent dans les tuyaux avec le seul langage que tout le monde connait: SQL.

Et comme nous sommes des geeks, nous ferons un petit détour sur Kafka Streams, la librairie sur laquelle repose KSQL.

Par [Florent Ramière]({{< ref "/speakers/florent-ramiere.md" >}})

### 19h50 - Mutation Testing

On écrit tous des tests (n’est-ce pas ?), mais comment savoir s’ils sont utiles ?

* Par leur nombre ? Faux, beaucoup de tests ne garantissent pas que l’application fonctionne correctement
* Avec une bonne couverture du code ? Encore faux, mieux mais pas suffisant

L’important est d'être confiant sur la capacité des tests à détecter les problèmes (c’est pourquoi en TDD un test doit échouer au début, pour etre sur qu’il teste bien quelque chose).  
Laissez-moi donc vous présenter le mutation testing !  
Cette technique modifie votre code, lance les tests et s’attend à ce qu’ils échouent.  
Si non, c’est que cette partie est mal testée…  
Dans ce talk je détaillerai les principes du mutation testing, expliquerai comment l’utiliser sur un projet scala et montrerai les résultats obtenus sur un projet réel.

Par [Loic Knuchel]({{< ref "/speakers/loic-knuchel.md" >}})

### 20h10 - Hadoop Unit

Dans une période où les tests sont de rigueurs et où l'on parle d'agilité et donc de cycle de plus en plus court, lorsque l'on utilise des technologies dites BigData comme Hadoop ou Spark, il est souvent bien difficile de mettre en place l'écosystème nécessaire aux tests (Apache Cassandra, Apache Kafka, HDFS, Hive, ElasticSearch, HBase, ...).
Venez découvrir comment Hadoop Unit permet de réaliser simplement des tests d'intégration.

Par [Khanh Tuong Maudoux]({{< ref "/speakers/khanh-tuong-maudoux.md" >}})

### 20h30 à 21h00 : Buffet

{{< figure src="../renaultDigital.png" width="150px">}}

### 21h00 - Jenkins plugin Support Core

Un plugin avec un tel nom, ça ne fait pas rêver, mais il doit être dans le couteau suisse des administrateur de Jenkins.  
Le plugin permet d'avoir un certain nombre d'information sur une instance Jenkins et connaitre le pourquoi du comment elle (l'instance) ne fonctionne pas correctement ou fonctionne au ralenti.  
On pourra aussi voir comment, chez CloudBees, on s'en sert pour passer des diagnostics automatique pour nos clients.

Par [Adrien Lecharpentier]({{< ref "/speakers/adrien-lecharpentier.md" >}})

### 21h20 - Outils de développement Cloud

A travers des exemples, nous verrons qu'il est possible d'avoir la même expérience développeur quand on utilise un cluster Kubernetes/OpenShift.  
Les cas suivants seront abordés:

* hotdeploy de code sur un cluster
* remote debug d'une application tournant sur un cluster

Par [Jeff Maury]({{< ref "/speakers/jeff-maury.md" >}})

### 22h00 à ...

3ème mi-temps des juggers dans un lieu sélectionné par votre Crew ;-)

{{< sponsor-section >}}

### Slides de la présentation

{{<iframe src="//www.slideshare.net/slideshow/embed_code/key/mG2kaRLQEYg55X" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;">}}

{{<iframe src="//www.slideshare.net/slideshow/embed_code/key/Fb2bhO53MRTZX8" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;">}}
