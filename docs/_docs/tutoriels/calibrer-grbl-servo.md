---
layout: documentation
hide_hero: false
hero_image: image.png
hero_darken: true
image: image.png
component_toc: true
doc_header: true
type: tuto

title: GRBL-Servo : Calibration servo
subtitle: Ajustez les impulsions PWM pour contrôler votre servo
description: Ajustez les impulsions PWM pour contrôler votre servo

time: 1
difficulty: 1

---

Dans ce tutoriel, vous allez ajuster les réglages de GRBL-Servo afin d’adapter le signal envoyé à votre servomoteur.

Vous l’avez peut-être remarqué : une fois GRBL flashé, le servo ne fonctionne pas tout à fait comme prévu. 
En théorie, quand on envoie **M3**, depuis UGS, le stylo doit **descendre**. Quand on envoie **M5**, il doit **remonter**.
Dans notre cas, il **vibre**, **chauffe**, et **semble bloqué** en butée au lieu de se déplacer entre ses deux positions.

---

{% include step-tuto.html 
greyBackground = true
title="Pourquoi le servo ne fonctionne pas"
content="
Un traceur à alimentation continue est une machine capable de dessiner ou d’imprimer sur un support en rouleau. Elle est couramment utilisée pour les plans d’architecture ou les impressions longues, car elle permet de produire des dessins sans limite de longueur. Le support est déplacé sous la tête de dessin grâce à des rouleaux motorisés. Ce type de machine convient bien pour des travaux répétitifs nécessitant de grandes surfaces." 
image="image.png"
image_2="image-1.png"
image_3="image-2.png"
image_4="image-3.png" %}

{%
  include card_collections.html
  title="Pour aller plus loin"
  description="Trouvez d'autres tutoriels en lien avec le projet"
  type="servo"
%}

---

{%
  include card_collections.html
  title="Pour aller plus loin"
  description="Trouvez d'autres tutoriels en lien avec le projet"
  type="tuto"
%}