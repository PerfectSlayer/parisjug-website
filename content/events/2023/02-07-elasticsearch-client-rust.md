---
date: 2023-02-07T20:38:00
publishDate: 2023-02-01
title: "Rust pour les développeurs Java et le nouveau client Elasticsearch"
#videos:
---
## Date et lieu

* Mardi 7 Février 2023 à 19h00
* Dans [les locaux de Datadog]({{< ref "/location/datadog.md" >}})

> Les sessions sont filmées et le public est photographié. Les photographies sont ensuite publiées sur le site du Paris JUG et autres médias de l'associations Paris JUG. En acceptant cette invitation, vous autorisez le Paris JUG à publier votre photo sur les médias sus-mentionnés.

Pour cet évènement, [Sylvain Wallez]({{< ref "/speakers/sylvain-wallez.md" >}}) nous fait l'honneur de venir depuis Toulouse.

## Détails

### 18h45 à 19h00: Accueil

### 19h30 : 400 endpoints d'API et 2000 types : le nouveau client Java pour Elasticsearch

Un nouveau client Java pour Elasticsearch est sorti en octobre 2021.  
Plus léger, plus rapide, plus ergonomique et… généré à 99% !

L'API d'Elasticsearch a grandi de façon organique depuis 10 ans et compte près de 400 points d'API et 2000 structures de données.  
Jusqu'à 2021 il n'y avait pas de spécification formelle de cette API.  
Gênant pour générer du code…  
On a rapidement vu que OpenAPI était difficilement applicable et pris une approche originale, en modélisant l’API avec des types TypeScript “compilés” dans un modèle servant de base à la génération de code.

Comment ensuite, à l’usage, s’y retrouver dans cette API très riche ?  
On verra avec quelques exemples que l’utilisation de fluent functional builders et de tagged unions (un peu de formalisme pour des choses simples) permet une écriture proche d’un DSL où on se laisse guider par l’autocomplétion de l’IDE sans jamais avoir à taper un nom de classe, dans des structures arborescentes et polymorphiques proposant parfois plus de 50 variantes.

### 20h30 : Buffet

[{{< figure src="/img/sponsors/2022/datadog.svg" alt="Datadog" class="sponsor-svg-logo" width="250" >}}](https://www.datadoghq.com/)

### 21h00 : Introduction à Rust pour les développeurs Java

Rust est le langage qui monte.  
Initialement conçu pour remplacer C++ dans Firefox, sa robustesse et son expressivité font que Rust est maintenant utilisé pour tous types d'applications.  
Nous ferons une exploration de Rust et son écosystème en comparaison avec Java : syntaxe et système de types, gestion de la mémoire et le fameux borrow checker, la grande originalité de Rust, gestion de la concurrence.

Et comme un langage n'est rien sans son écosystème, nous verrons comment développer un serveur d'API web et JSON avec accès à une base SQL, avec une comparaison de taille et de performances avec la JVM classique et GraalVM.

### 22h00 : 3ème mi-temps des juggers
 
{{< replay-section >}}

{{% coc-section %}}
