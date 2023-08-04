---
date: 2023-06-13T19:00:00
publishDate: 2023-06-07
tags:
- devops
- tools
register: "https://www.eventbrite.fr/tickets-external?eid=652197047927&ref=etckt"
title: "Soirée OpenTelemetry"
videos:
- https://www.youtube.com/watch?v=nDBiXpWCL-k
- https://www.youtube.com/watch?v=ghXeqF2VaFs
- https://www.youtube.com/watch?v=fiK4m26XBnw
---

## Date et lieu

* Mardi 13 Juin 2023 à 19h00
* Dans [les locaux de Mirakl]({{< ref "/location/mirakl.md" >}})

> Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.

## Détails

### 19h : Accueil

### 19h30 : Observabilité et OpenTelemetry, deux bouleversements du monde du monitoring

Le monde du monitoring a connu de nombreux bouleversements.
D’abord l’adoption des architectures Cloud Native qui a rendu obsolète l’état de l’art de la supervision au point de faire émerger des nouvelles bonnes pratiques appelées “Observabilité”.
Ensuite l’émergence du standard Open Source OpenTelemetry qui, s’il n’est pas une solution miracle, change radicalement l’éventail des solutions disponibles.

Après une revue de ces bouleversements, nous verrons comment la définition d’une stratégie d’observabilité est passée d’une question de choix de vendeur à un enjeu de définition d’architecture et à un choix d’écosystèmes avec les questions d’interopérabilité qu’ils amènent.

Par [Cyrille Le Clerc]({{< ref "/speakers/cyrille-le-clerc.md" >}})

### 20h20 : Buffet

[{{< figure src="/img/sponsors/2023/mirakl.svg" alt="Mirakl" class="sponsor-svg-logo" width="250" >}}](https://mirakl.tech/)

### 20h45 : Retour d'expérience sur l'utilisation d'OpenTelemetry chez Ubisoft

Chez Ubisoft, nous utilisons OpenTelemetry dans différentes équipes, pour unifier la collecte et la correlation entre les logs, metrics et traces.

Dans cette présentation nous commencerons rapidement par voir comment on utilise OpenTelemetry: via l'API/SDK et/ou le collector, quelles types d'évènements (logs, metrics, traces), et comment on l'intègre avec l'existant (prometheus/elasticsearch, stack grafana, etc).

Mais nous reviendrons surtout sur les challenges que nous avons rencontrés, tant sur le plan technique que sur le plan organisationnel.
Côté technique, il s'agit essentiellement de la gestion des différents niveaux de maturité de différents composants, et de l'intégration dans un écosystème existant: incompatibilité entre les conventions d'OpenTelemetry et d'OpenMetrics, comment l'utiliser en local facilement, etc.
Côté organisationnel, il s'agit de casser les silos existants (logs, metrics qui sont gérés par des équipes différentes...).

Par [Vincent Behar]({{< ref "/speakers/vincent-behar.md" >}})

### 21h25 : Instrumenter vos applications Java avec OpenTelemetry

En incubation depuis 3 ans, OpenTelemetry est le second projet le plus actif de la CNCF (Cloud Native Computing Foundation) derrière Kubernetes, et s’est déjà imposé comme un standard incontournable de l’observabilité.
Ce framework permet d’instrumenter vos applications, de générer, collecter et exporter des traces, logs, et métriques de façon interopérable sans vendor lock-in.

Durant cette présentation, nous verrons en pratique les différentes façons d’instrumenter vos applications Java via les outils d’OpenTelemetry tels que son API / SDK, les différents supports des frameworks, et les instrumentations automatiques à base d’agent.
Vous serez alors en mesure de générer des traces et de commencer à contribuer à l’observabilité de vos systèmes.

Par [Bruce Bujon]({{< ref "/speakers/bruce-bujon.md" >}})

### 22h15 : 3ème mi-temps des juggers

{{< replay-section >}}

## Feedback

{{< tweet user="__sunix_" id="1668706110340055046">}}
{{< tweet user="bqiao_eu" id="1668739955927941120">}}

{{< sponsor-section >}}

{{% coc-section %}}

