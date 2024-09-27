## Réflexion

Tu as appris beaucoup de choses ! Réponds aux questions ci-dessous pour réfléchir à ce que tu as appris.

--- question ---

---
legend: Question 3 sur 3
---

"Tu veux que ta LED s'allume lorsque tes sprites se touchent, mais s'éteigne lorsqu'ils ne se touchent pas.

Quels blocs ajouterais-tu à ce script pour qu'il fonctionne de cette façon ?

`blocks3
when green flag clicked
forever
if <(touching[Sprite2]) > then
  ...
sinon
...
fin`

--- choices ---

- ( ) Ajoute un bloc `Turn LED (21)[off v]`{:class="block3extension"} à l'emplacement du haut **si-alors** et ajouter un bloc `Turn LED (21)[on v]`{:class="block3extension"} à l'emplacement du bas **sinon**.

  --- feedback --- Non, pas tout à fait. Tu as la bonne idée, mais tu veux que ta LED **s'allume si** les sprites se touchent, mais **éteinte** dans les autres cas (sinon). --- /feedback ---

- (x) Ajoute un bloc `Turn LED (21)[on v]`{:class="block3extension"} à l'emplacement du haut **si-alors** et ajoute un bloc `Turn LED (21)[off v]`{:class="block3extension"} à l'emplacement du bas **sinon**.

  --- feedback --- Oui ! Cela signifie que **si** tes sprites se touchent, la LED sera allumée. Sinon (sinon), elle s'éteindra. --- /feedback ---

--- /choices ---

--- /question ---