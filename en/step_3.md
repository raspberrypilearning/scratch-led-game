## Code your circuit

Write Scratch code so that your LED lights up when the player is near the hedgehog.

--- task ---

Take the jumper wire off Pin 1 and attach it to **Pin 21** instead. Pin 21 is a pin which can be controlled with Scratch code.

![Circuit diagram of a jumper wire with a resistor and LED wired to 3V3 on a Raspberry Pi.](images/Pi_21_Complete.png)

--- /task ---

--- task ---

On the Raspberry Pi, download and open the [starter project](https://rpf.io/p/en/scratch-led-game-get){:target="_blank"}.

--- collapse ---
---
title: Opening a downloaded Scratch 3 Desktop project
---

Once you have downloaded the zip file from the link above, open your file manager and navigate to the **Downloads** folder.

Find the file you just downloaded. It will end in `.zip`.

Right click on the file and choose 'Extract here' to extract them to your downloads folder.

In Scratch 3 Desktop, click the `File` menu and choose `Load from your computer`.

Navigate to your downloads folder again and select the file `scratch-physcomp1.sb3`. 

Click `OK` or press `Enter`.

--- /collapse ---

--- /task ---

--- task ---

Make sure you have the **Stage** selected.

![A section of the Scratch interface with a purple header labeled "Stage." Below, there is a small thumbnail image of a scenic forest background featuring trees, grass, and abstract green shapes.](images/choose-stage.png)

--- /task ---

--- task ---

Using the `Simple Electronics`{:class="block3extensions"} extension from the blocks menu, add the following blocks into the `if`{:class="block3control"} block.

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (21 v) [on v] ::led extension
else
+turn LED (21 v) [off v] ::led extension
end
```

If the distance to the hedgehog is less than it was before (ie. a number less than 0), the LED turns on — `else`{:class="block3control"} it turns off.

--- /task ---

--- task ---

Click on the green flag. Use the arrow keys and the LED to hunt the hedgehog!

--- /task ---

--- save ---
