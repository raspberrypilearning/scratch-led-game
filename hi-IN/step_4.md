## Add another LED

Add another LED to show when you are moving in the wrong direction.

--- task ---

Connect another LED bulb to your Raspberry Pi using a different numbered pin and another ground pin.

In this example Pin 20 has been used:

![A Raspberry Pi 5 circuit board connected to two LEDs, one red and one green, using resistors and jumper wires. The red LED is connected to a GPIO pin via a resistor with black and red wires, while the green LED is connected similarly with purple and black wires. The layout shows the GPIO pins in use, with the LEDs wired in a basic circuit configuration for demonstration purposes. The board includes visible HDMI, USB, and Ethernet ports, labeled with "Raspberry Pi 5" and "HDMI" text.](images/extra_LED.png)

--- /task ---

**Tip:** Make sure you remember which numbered GPIO pin you connect the long leg of your LED to - you'll need to use it in your code!

--- task ---

Right-click the script on the Stage which calculates the distance to the hedgehog, and duplicate it so there are two in your workspace.

![The image shows a coding block interface, specifically for Scratch programming. The visible block is a "forever" loop that executes a conditional ("if-else") block. It includes broadcasting messages "LEDOn" and "LEDOff" based on a condition. A dropdown menu is displayed, providing the options "Duplicate," "Add Comment," and "Delete Block," likely for modifying the selected block. The context appears to be a user interacting with Scratch's block-based coding environment, focusing on controlling an LED's behavior.](images/duplicate-script.png)

--- /task ---

--- task ---

In the new script, change the number in the `turn LED (21) on`{:class="block3extensions"} and `turn LED (21) off v`{:class="block3extensions"} blocks to the new number for your second LED.

In this example pin 20 has been used:

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (20 v) [on v] ::led extension
else
+turn LED (20 v) [off v] ::led extension
end
```

--- /task ---

--- task ---

Swap over the two `on`{:class="block3extensions"} and `off`{:class="block3extensions"} settings in your second script so it looks like this:

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (20 v) [off v] ::led extension
else
+turn LED (20 v) [on v] ::led extension
end
```

And your new LED will come on when you get further from your goal.

--- /task ---


--- save ---
