---
layout: documentation
hide_hero: false
hero_image: 17HE12-1204S-500x500.jpg
hero_darken: true
image: 17HE12-1204S-500x500.jpg
component_toc: true
doc_header: true
type: hardware

title: Moteur pas-à-pas
subtitle: Pour se déplacer précisemment
description: Cette page détaille le fonctionnement du moteur pas-à-pas ains ique les étpaes de mise en oeuvre
manufacturer:
  - name: OMC-stepperonline
    link: "https://www.omc-stepperonline.com/"

todo: 10
---

Le moteur pas à pas est un composant essentiel dans de nombreuses applications de robotique et de contrôle de mouvement, offrant une grande précision de positionnement par rapport aux moteurs à courant continu, sans nécessiter de composants électroniques supplémentaires, comme des encodeurs. Contrairement aux moteurs à courant continu classiques, le moteur pas à pas est conçu pour se déplacer par "pas" fixes, permettant ainsi un contrôle très précis du déplacement angulaire.

On retrouve ces moteurs dans de nombreuses applications courantes, comme les imprimantes 3D, les imprimantes classiques, les scanners, ainsi que les machines à commande numérique (CNC) utilisées pour la gravure ou la découpe.

## Principe de Fonctionnement

Un moteur pas à pas fonctionne en convertissant les impulsions électriques en mouvements angulaires discrets. Chaque impulsion appliquée au moteur le fait tourner d'un certain angle, appelé "pas". En contrôlant la séquence d'impulsions, il est possible de faire tourner le moteur dans les deux sens, de manière plus ou moins rapide.

Le fonctionnement repose sur le principe des électroaimants qui entourent le rotor. Ces électroaimants sont activés dans un ordre précis pour faire tourner le rotor de manière progressive. Cela signifie que la rotation du moteur est proportionnelle au nombre d'impulsions reçues, ce qui permet un positionnement précis et facile à contrôler.