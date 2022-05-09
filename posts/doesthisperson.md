---
layout: post
title: Does this person exist ?
---


# Un compte twitter pour savoir si une photo est (potentiellement) issue de thispersondoesnotexist.com

## A quoi ça sert

Depuis un moment maintenant, des faux comptes Twitter utilisent pour leur photo de profil le site [thispersondoesnotexist.com](http://thispersondoesnotexist.com), qui génère des images de visages qui n'existent pas. Le phénomène, qui n'est pas nouveau, a pu être évoqué [ici](https://twitter.com/AntoineBondaz/status/1471190807369719819) ou [ici](https://twitter.com/VictorBaissait/status/1454854928443269121). J'ai donc bricolé [un compte Twitter](https://twitter.com/DoesThisPerson) pour tenter de les détecter.

## Comment ça marche

L'avantage de [thispersondoesnotexist.com](http://thispersondoesnotexist.com), c'est que leur algo positionne les yeux toujours à peu près au même endroit. Le principe du bot est donc simple : vous lui tweetez une image, il analyse la position des yeux, et s'ils sont localisés à des coordonnées x et y comprises dans une fourchette (établie à partir d'un échantillon de TPDNE), il répond qu'il est probable que l'image vienne de ce site.

Et [ça se passe ici](https://twitter.com/DoesThisPerson).


## Attention

Il y a de nombreuses limites (impossible d'être sûr à 100% ; certaines images de TPDNE peuvent échapper à l'algo ; on peut facilement tromper le bot...), et il y a sûrement des réglages à faire. J'ai surtout fait ce bot pour expérimenter et essayer de nouvelles librairies (dlib pour la détection des éléments du visage, tweepy pour le bot Twitter).

Depuis, j'ai vu passer différents outils très probablement plus performants, comme [cette extension Chrome](https://twitter.com/OSINTtechniques/status/1508310343927402503).