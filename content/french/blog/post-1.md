---
title: "La création du site"
meta_title: ""
description: "Comment créer un site web statique à moindres coûts"
date: 2024-04-11
image: "/images/blog-1.jpeg"
categories: ["Site web", "Blog"]
author: "Pigeon Rentier"
tags: ["nextjs", "tailwind"]
draft: false
---

Tester des side hustle ou des stratégies d'investissement n'est pas une idée neuve : elle est pratiquement née avec la prolifération des publications sur ce sujet puisque toute chose ne peut exister sans son antagoniste.
Dès le début de l'aventure, il m'a paru opportun de créer un blog, journal de bord des business testés afin d'en tenir un suivi plus rigoureux et documenté que des stories / reels Instagram / TikTok.
Etant donné que je suis au jour 1 de l'expérimentation et que les euros ne se bousculent pas encore dans mes poches, mon but est de faire en sorte que la création de ce site, sa maintenance ainsi que son hébergement soient le moins coûteux possibles.

## Le site de A à C

J'ai choisi d'utiliser Hugo - https://gohugo.io/ - un générateur de site statique open-source.  

Que signifie "statique" ? Grosso modo, que le site en question n'a pas de traitement côté serveur et ne nécessite pas de base de données : les fichiers qui le composent sont servis aux visisteurs tels qu'ils sont présents sur le serveur.  
En termes d'hébergement, cela le simplifie grandement puisque tout ce que j'ai à déployer est un ensemble de fichiers et cela réduit considérablement les coûts (en opposition à un site web dynamique où il faudrait prévoir davantage de ressources.)

Sais-je faire des sites ? Pas du tout, je suis donc allé piocher un thème pré existant pour combler mes grosses lacunes en la matière. J'ai choisi Hugoplate car c'est un starter template gratuit et open-source qui mêle Hugo et TailwindXCSS pour faire des sites de toute beauté (en tout cas de la beauté nécessaire et suffisante pour mon besoin).

Le contenu du site s'écrit très simplement via des fichiers plats.