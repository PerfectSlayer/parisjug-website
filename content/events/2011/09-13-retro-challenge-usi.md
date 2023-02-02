---
date: 2011-09-13T19:00:00
#draft: true
publishDate: 2011-09-13
#register: "https://eventbrite.fr/tickets-external?eid=xxxx"
tags:
title: "Retrospective Challenge USI"
#videos:
#- https://www.youtube.com/watch?v=xxxx
---

## Date et lieu

* Mardi 13 Septembre 2011
* Dans [les locaux de l'ISEP]({{< ref "/location/isep.md" >}})

> Inscriptions closes

## Détails

Le Challenge USI 2011 est un concours de code organisé par Octo Technologies dans le cadre de l’Université du SI 2011.  
Il s’agissait de coder une application de quizz.  
Sur les 20 équipes sélectionnées, une douzaine ont réalisé une application fonctionnelle: certaines en Java “pur”, d’autres en Scala, en Erlang, en C, et JavaScript (node.js)...  
Dans le cadre du Paris JUG, nous vous proposons une rétrospective avec certaines équipes ayant participé au challenge, dont les 3 équipes finalistes (2 utilisant Java, 1 avec un serveur codé en C “à la main”).  
La présentation de chaque projet se décomposera en trois parties :

* Description de l'architecture
* Dire ce qui a marché
* Dire ce qui n'a pas marché 

### 19h15 à 19h30 : Accueil

### 19h30 à 20h30 : Première partie

* Présentation du challenge et de la plateforme technique
* Présentation des résultats au global
* Architecture de l’application gagnante

### 20h35 à 21h05 : Buffet

Offert par la société [VMWARE](https://www.vmware.com/)
{{< figure src="/img/sponsors/2011/vmware1.PNG" alt="VMWARE" class="sponsor-gold-svg-logo" >}}

### 21h05 à 22h00 : Deuxième partie

* Présentation de l'application n° 2
* Présentation de l'application n° 3
* Présentation des autres applications

### Composition des équipes et architectures choisies

* **1ere place**
  * Julien Buret et Seven Le Mesle
  * Architecture : Netty + Gemfire+ Linux Virtual Server
* **2eme place**
  * Nicolas Romanetti, Florent Ramière, Bernard Pons et Julien Dubois
  * Architecture : Netty + Cassandra + Linux Virtual Server
* **3eme place**
  * Quentin Ambard et Matthieu Mouminoux
  * Architecture : serveur C custom evenementiel basé sur libevent + Redis + wackamole pour les vip
* **Participants non finalistes**
  * Alexis Agahi, Francois Armand et Arnaud Bailly
  * Architecture : Scala + Netty + Akka + Berkeley DB Java Edition
* **Participants non finalistes**
  * Manuel Boillod, Marc Godin et Pierre Queinnec
  * Architecture : Tomcat + Async Servlets + Spring + GemFire
* **Participants non finalistes**
  * David Gageot et Mathieu Bolla
  * Architecture : Simple, Jackson, Terracotta, haproxy
* **Participants non finalistes**
  * David Launay et Yann Pichot
  * Architecture : Scala, Akka, Coherence, MySQL

### 22h00 à ... : 3ème mi-temps des juggers au [Vavin](https://www.google.com/maps/dir//48.84398,2.330533/@48.8439685,2.2603067,12z)

{{< sponsor-section >}}
