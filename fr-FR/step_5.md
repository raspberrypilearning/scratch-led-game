## Améliorer ton projet

Maintenant, tu peux ajouter une autre LED pour indiquer lorsque tu te déplaces dans la mauvaise direction. Tu devras connecter une autre ampoule LED à ton Raspberry Pi en utilisant une broche numérotée différente et une autre broche GND.


**Astuce :** assure-toi de te rappeler à quelle broche GPIO numérotée tu connectes la longue patte de ta LED, tu devras l'utiliser dans ton code !

Une fois que tu as connecté la LED à ton Raspberry Pi, fais un clic droit sur le script du sprite Player qui calcule la distance jusqu'au hérisson, et duplique-le pour qu'il y en ait deux dans ton espace de travail.

Dans le nouveau script, change le numéro dans les blocs `turn LED (21 v) [on v]`{:class="block3extensions"} et `turn LED (21 v) [off v]`{:class="block3extensions" } avec le nouveau numéro de ta deuxième LED.

Dans cet exemple, j'ai utilisé la broche 3 :

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (3 v) [on v] ::led extension
else
+turn LED (3 v) [off v] ::led extension
end
```

Le script détermine à quelle distance du hérisson se trouve actuellement le joueur et la compare à la dernière distance calculée. Si la distance est plus petite, la LED s'allume. Inverse les deux paramètres `on`{:class="block3extensions"} et `off`{:class="block3extensions"} dans ton second script, donc il ressemble à ceci :

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (3 v) [off v] ::led extension
else
+turn LED (3 v) [on v] ::led extension
end
```
Et une lumière s’allumera lorsque tu t'éloigneras de ton objectif.

--- collapse ---
---
title: Le projet achevé
---

Tu peux voir le [projet terminé ici](https://scratch.mit.edu/projects/486719199/){:target="_blank"}.

--- /collapse ---

Tu peux également « remixer » le projet pour apporter les modifications que tu souhaites. Tu peux ajouter des effets sonores au jeu ou à d'autres sprites ou arrière-plans, ou définir l'effet de couleur et les costumes du personnage du joueur. Peut-être ajouter un autre sprite caché qui active une autre LED ?


--- save ---
