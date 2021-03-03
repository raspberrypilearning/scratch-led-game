--- question ---

---
legend: Question 3 of 3
---

You want your LED to come on when your sprites are touching, but go off when they are not. 

What blocks would you add to this script to make it work that way?

```blocks3
when green flag clicked
forever
if <(touching[Sprite2]) > then
  ...
else
  ...
end

--- choices ---

- ( ) Add a `Turn LED (21)[off v]`{:class="block3extension"} block to the top **if-then** slot and a add a `Turn LED (21)[on v]`{:class="block3extension"} block to the bottom **else** slot.

  --- feedback ---
No, not quite. You have the right idea, but you want your LED to turn **on if** the Sprites are touching, but **off** otherwise (else).
  --- /feedback ---

- (x) Add a `Turn LED (21)[on v]`{:class="block3extension"} block to the top **if-then** slot and a add a `Turn LED (21)[off v]`{:class="block3extension"} block to the bottom **else** slot.

  --- feedback ---
Yes! This means that **if** your sprites are touching, the LED will be on. Otherwise (else) it will turn off. 
  --- /feedback ---

- ( ) Add a `Broadcast (LED=on)`{:class="block3events"} block to the top **if-then** slot and a add a `Broadcast (LED=on)`{:class="block3events"} block to the bottom **else** slot. 

  --- feedback ---
No, using broadcast blocks won't directly affect the GPIO pins. Think about which `extension`{:class="block3extension"} you used in this project to control the LED.
  --- /feedback ---

- ( ) Add a `set [LED V] to (on)`{:class="block3variables"} block to the top **if-then** slot and a add a  `set [LED V] to (off)`{:class="block3variables"} block to the bottom **else** slot.

  --- feedback ---

No, using variables won't directly affect the GPIO pins. Think about which `extension`{:class="block3extension"} you used in this project to control the LED.

  --- /feedback ---

--- /choices ---

--- /question ---
