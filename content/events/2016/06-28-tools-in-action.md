---
date: 2016-06-28T19:00:00
publishDate: 2016-06-21
tags:
- security
title: "Soirée Tools In Action"
---

## Date et lieu

- Mardi 28 Juin 2016
- Dans [les locaux de l'ESIEA]({{< ref "/location/esiea.md" >}})

- Sauf exception, les sessions se dérouleront désormais à l'ESIEA au 9 rue Vesale 75005 Paris.
- Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.
- Les inscrits à l'évènement non présents 5 min avant le début de la session, soit à 19h25, verront leur place remise à disposition
- Les non inscrits à l'évènement ne pourront donc y assister que sous réserve de places disponibles sur place 5 min avant le début de la session, soit à 19h25.
- L’inscription implique de posséder une adresse mail valide sur laquelle vous recevrez une demande de confirmation à laquelle il vous faudra répondre afin de valider votre inscription.

Toute inscription non confirmée ne sera pas prise en compte !

## Photos

{{< flickr id="72157667772546113" img="https://live.staticflickr.com/7383/28027626376_c19928ca4a_h.jpg" >}}

## Détails

### 19h15 à 19h30: Accueil

### 19h30 - Secure Real Time Edition (Cryptpad/Xwiki)

In 2013, XWiki SAS began work on the Chainpad project, which utilizes a minimal Operational Transformation (OT) algorithm with Blockchains (a technology popularized by Bitcoin) for Collaborative Real Time Editing (CRTE) that does not depend on a central server. XWiki SAS has since continued to build an ecosystem of collaborative editors that depend on Chainpad, most notably our RealTime WikiText and RealTime CKEditor WYSIWYG plugins in XWiki Enterprise, and Cryptpad: a standalone webserver written in Nodejs which serves a growing suite of prototypes.

Since Cryptpad's server only acts as a relay, it can store and deliver messages without requiring knowledge of their content. It derives its name from the fact that all its applications encrypt their messages before they are sent to other clients, ensuring that the server remains oblivious.

A browsers' native behaviour is to never send URL hashes in HTTP requests. We exploit this behaviour to make it possible for users to share symmetric encryption keys through URLs, making encrytion more accessible to a wider range of users.

I will demonstrate our most recent developments: arbitrary DOM synchronization via "HyperJSON", multi-user form applications, serverless collaboration using WebRTC, collaborative lists and maps via realtime JSON, and collaborative canvas editing via FabricJS. I'll discuss the challenges presented by each of these projects, their current status, what we'd like to accomplish next, and how developers can take advantage of our work in their own applications.

Par [Ludovic Dubost]({{< ref "/speakers/ludovic-dubost.md" >}}) et [Aaron MacSween]({{< ref "/speakers/aaron-mac-sween.md" >}})

### 19h50 - D3 - Data-Driven Document (la Dataviz facile… ou pas!)

D3 est une bibliothèque graphique JavaScript qui permet l'affichage de données numériques sous une forme graphique et dynamique. Successeur de Protoviz, elle utilise des technologies telles que le SVG, le Javascript et les CSS et facilite la manipulation du DOM.

Par [Tom Comte]({{< ref "/speakers/tom-comte.md" >}})

### 20h10 - Loop, améliorez votre workflow de développement d'application Web

Travailler un framework Web full-stack comme Play ou Rails permet un workflow de développement productif: les changements apportés au code entraine automatiquement le rechargement de l'application, et un pipeline dédié de compilation des assets (JS, CSS, ...) est intégré au build principal.

Mais lorsque l'on doit travailler avec des micro-frameworks ou des système de build hétérogènes, tout ça se complique. Laissez moi vous présenter Loop.

Loop gère vos différents système de build, redémarre votre serveur au besoin, bloque l'accès à l'application tant qu'elle n'est pas prête, affiche directement les erreurs de compilation dans le navigateur.

Loop est indépendant de la technologie et saura gérer vos build Maven, SBT, Gradle, grunt, gulp, make, cargo, (etc.) pour améliorer votre workflow de développement d'application Web en Javascript, Java, Scala, Python, Rust, Go, (etc.).

Par [Guillaume Bort]({{< ref "/speakers/guillaume-bort.md" >}})

### 20h30 à 21h00 : Buffet

### 21h00 - Ocelotds : communication facile entre java EE et javascript

Ocelotds est un framework open source basé sur CDI et les Websockets, permettant de faire communiquer une application javaee avec une UI en javascript/html.

Supprimant le code inutile, Ocelotds permet de se concentrer sur le métier de l'application. Outre les appels de services java à partir de javascript, Ocelotds inclut un mécanisme élégant de cache sur le navigateur piloté par le métier.

Avec websocket, Ocelotds inclut des fonctions de push/notification similaires aux topics JMS.

Par [François Apache]({{< ref "/speakers/francois-apache.md" >}})

### 21h20 - Framework de Key Value Mapping chez les furets
Model-map, le framework de Key Value Mapping développé chez LesFurets : Il nous offre un mapping bidirectionnel du modèle métier vers des structures de données plus simples (listes, tableaux et maps) pour que les manipulations de données deviennent alors extrêmement simples à réaliser

Par [Gilles Di Guglielmo]({{< ref "/speakers/gilles-di-guglielmo.md" >}}) et [Mathieu Gandin]({{< ref "/speakers/mathieu-gandin.md" >}})

### 22h00 à ...

3ème mi-temps des juggers au Les Négociants (23 Avenue des Gobelins,75005 Paris)

{{< sponsor-section >}}

{{% coc-section %}}
