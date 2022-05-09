---
layout: post
title: Instabot
---


# Un bot pour envoyer par mail les stories Instagram d'un ami

## A quoi ça sert

Un jour, une amie, A., m'a répété à quel point elle était triste de louper les stories Instagram hautement qualitatives de notre ami H. Mais A. ne veut vraiment pas avoir Instagram. J'ai donc codé un bot qui envoie à A., par mail, les stories de H. (qui était au courant et consentant).

## Comment ça marche

Il s'agit d'un script python en 2 parties. Une première avec Instaloader, qui va vérifier si H. a posté une nouvelle storie Instagram. Et une deuxième qui envoie le fichier par mail, si fichier il y a, grâce à smtplib. Le tout est installé sur un serveur VPS chez OVH, et tourne tous les matins à 7h, grâce à un cron.

