--- question ---

---
legend: Question 3 sur 3
---

You want your LED to come on when your sprites are touching, but go off when they are not.

Quels blocs ajouterais-tu à ce script pour qu'il fonctionne de cette façon ?

```blocks3
when green flag clicked
forever
if <touching[Sprite2]> then

else

end
```

--- choices ---

- ( ) Add a `Turn LED (21)[off v]`{:class="block3extension"} block to the top **if-then** slot and a add a `Turn LED (21)[on v]`{:class="block3extension"} block to the bottom **else** slot.

  --- feedback ---

No, not quite. Tu as la bonne idée, mais tu veux que ta LED **s'allume si** les sprites se touchent, mais **éteinte** dans les autres cas (sinon).

  --- /feedback ---

- (x) Ajoute un bloc `Turn LED (21)[on v]`{:class="block3extension"} à l'emplacement du haut **si-alors** et ajoute un bloc `Turn LED (21)[off v]`{:class="block3extension"} à l'emplacement du bas **sinon**.

  --- feedback ---

Yes! Cela signifie que **si** tes sprites se touchent, la LED sera allumée. Sinon (sinon), elle s'éteindra.

  --- /feedback ---

--- /choices ---

--- /question ---
