---
layout: post
title: L'extension OriginVideo
---


# Une extension Chrome pour retrouver la vidéo originale sur Twitter

## A quoi ça sert

Sur Twitter, il arrive qu'une personne repartage une vidéo, en "citant" la vidéo originale. Par exemple : 

![tweet Booba](/files/originvideo/booba.png)

Le problème que cela peut poser, c'est que le tweet original, qui est cité, peut remonter à bien longtemps avant le retweet en question, et il est difficile de le savoir. Par exemple, cette vidéo de David Dufresne dénonce un cas de violences policières. Le tweet initial de DavDuf date de février 2019, mais elle a été repartagée en masse, dont par lolo91, en janvier 2020, en laissant suffisamment de doute pour qu'on pense que les faits sont récents.

![tweet DavDuf](/files/originvideo/davduf.png)

Or, pour retrouver le tweet de David Dufrene, dans lequel la vidéo originale a d'abord été partagée, Twitter ne nous facilite pas la tâche. Il faut cliquer sur le profil de David Dufresne, et scroller sa timeline jusqu'à retrouver la vidéo en question. Ce qui peut être très long.

C'est là que l'extension intervient. Début décembre 2019, Jane Manchun Wong a indiqué [une manip' simple](https://twitter.com/wongmjane/status/1202293089395568640) pour retrouver le tweet initial. J'ai juste récuépré son bout de code pour en faire une extension, pour qu'en un clic ça soit réglé.

![Gif exemple](/files/originvideo/exemple.gif)

## Comment l'installer

Pour installer l'extension, il suffit d'aller sur le [repo Github correspondant](https://github.com/briceleborgne/OriginVideo). Téléchargez le dossier ZIP, dézippez le tout dans un dossier en local. Puis dans chrome, allez dans "Extensions", activez le mode développeur. Cliquez sur "chargez l'extension non empaquetée", sélectionnez le bon dossier en local, et zou.

![Github](/files/originvideo/github.png)

## Attention

Contrairement à ce que certaines personnes ont cru, cette extension n'est d'aucune utilité si l'on cherche à savoir qui a posté les images en premier. Ca n'est pas du tout une recherche inversée, en gros. Mais malgré tout, ça reste un minimum utile.