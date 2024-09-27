## Upgrade your project

Now, you can add another LED to show when you are moving in the wrong direction. You will need to connect another LED bulb to your Raspberry Pi using a different numbered pin and another ground pin.


**Tip:** Make sure you remember which numbered GPIO pin you connect the long leg of your LED to - you'll need to use it in your code!

Once you have connected the LED to your Raspberry Pi, right-click the script on the Player sprite which calculates the distance to the hedgehog, and duplicate it so there are two in your workspace.

In the new script, change the number in the `turn LED (21 v) [on v]`{:class="block3extensions"} and `turn LED (21 v) [off v]`{:class="block3extensions"} blocks to the new number for your second LED.

In this example I have used pin 3:

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (3 v) [on v] ::led extension
else
+turn LED (3 v) [off v] ::led extension
end
```

The script works out how far away from the hedgehog the player currently is, and checks that against the last distance it calculated. If the distance is smaller, it turns the LED on. Swap over the two `on`{:class="block3extensions"} and `off`{:class="block3extensions"} settings in your second script so it looks like this:

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (3 v) [off v] ::led extension
else
+turn LED (3 v) [on v] ::led extension
end
```
And one light will come on when you get further from your goal.

--- collapse ---
---
title: Completed project
---

You can view the [completed project here](https://scratch.mit.edu/projects/486719199/){:target="_blank"}.

--- /collapse ---

You can also 'remix' the project to make any changes you like. You could add sound effects to the game or other sprites or backdrops, or set the colour effect and costumes of the player character. Maybe add another hidden sprite that activates another LED?


--- save ---
