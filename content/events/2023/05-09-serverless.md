---
date: 2023-05-09T19:00:00
publishDate: 2023-05-02
tags:
- architecture
- cloud
- kubernetes
register: "https://eventbrite.fr/tickets-external?eid=576387599827&ref=etckt"
title: "Soirée Serverless: Kafka, Quarkus et opérateur Kubernetes"
#videos:
---

## Date et lieu

* Mardi 9 Mai 2023 à 19h00
* Dans [les locaux de Mirakl]({{< ref "/location/mirakl.md" >}})

> Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.

## Détails

### 19h00 : Accueil

### 19h30 : La quête de Bob, l'appli en fin de cycle

Bob est une vieille application, conçue en 2010, elle est encore la vache à lait et c’est bien l’unique raison pour laquelle Bob n’a pas été décommissionné.
Mais Bob sait qu’il est fragile, tous ses devs ont quitté la boite depuis bien longtemps et il se sent comme une tour de Jenga après 20 tours de jeu.

Il sait qu’il est trop tard pour lui mais il décide de partir pour une dernière quête et essaie d’aider sa boite qui souhaite se tourner vers le “Event Driven Architecture” et le Serverless.
Durant sa quête, Bob rencontrera de nombreux personnages, comme Debezium, cet être étrange qui capture les changements d’une base de données et les transfère dans une rivière magique appelée Kafka.

Vous voulez savoir comment cette quête se termine et si Bob parviendra à son but ?
Rejoignez-nous dans ce talk palpitant qui se vivra comme une aventure. 

Par [Sébastien Blanc]({{< ref "/speakers/sebastien-blanc.md" >}})

### 20h30 : Buffet

[{{< figure src="/img/sponsors/2023/mirakl.svg" alt="Mirakl" class="sponsor-svg-logo" width="250" >}}](https://mirakl.tech/)

### 21h00 : Développer un opérateur Kubernetes en Java, challenge accepted !

Il n'est plus, je pense, nécessaire de présenter Kubernetes tellement il fait parti du paysage informatique.
Avec sa généralisation, de nouveaux types de développements et de patterns sont apparus. Lors de ce talk j'aborderai l'un d'eux : les opérateurs.
Merveilleux assistants, aptes à faire énormément de choses. Mais voilà, les nombreuses documentations que l'on trouve tournent principalement autour d'un langage : Go.
Ce n'est pas que cela ne me plaise pas, mais l'idée est de pouvoir aussi le faire avec un autre langage que je connais et utilisé par de nombreuses équipes de développement : Java.

Lors de ce talk, je vous présenterai, de manière simple, la notion des opérateurs au sein de Kubernetes : à quoi ils servent et comment ils évoluent dans l'éco-système Kubernetes.
Nous verrons qu'ils peuvent être de simples aides à l'installation ou à la mise à jour d'une application au sein de Kubernetes mais aussi aller beaucoup plus loin en devenant de vrais Ops pour gérer vos applications pour vous !

Puis, nous développerons un opérateur ensemble et en Java : un bon Hello World nous permettant de prendre en main le SDK Java mais aussi les différents éléments présentés au début du talk.
Enfin, nous essaierons de nous projeter vers un opérateur faisant un peu plus que Hello World afin de voir si vraiment il sait faire de l'Ops !

À la fin de ce talk, vous aurez les différents éléments pour savoir si vous avez besoin de développer un opérateur, comment le développer, et choisir entre le faire en Java ou dans un autre langage ! 

Par [Stéphane Phillipart]({{< ref "/speakers/stephane-phillipart.md" >}})


### 22h00 : 3ème mi-temps des juggers

{{< replay-section >}}

{{< sponsor-section >}}

{{% coc-section %}}
