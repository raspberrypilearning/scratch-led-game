## Code your circuit

In this step, you will connect your completed circuit to an output pin on the Raspberry Pi and control it using the `Simple Electronics`{:class="block3extensions"} extension.

Currently, your circuit is tested and working, and your LED is on; but you want it to light up when something happens in your Scratch program. 

To do that, you need to connect your LED circuit to an output pin on the Raspberry Pi.

--- task ---
Take the jumper wire off of Pin 1 and attach it to any other numbered pin. In this example, I’ve used Pin 21 (because it’s easy to get to) but you can use any numbered general purpose (GP) pin on your Raspberry Pi. 


![Circuit diagram of a jumper wire with a resistor and LED wired to 3V3 on a Raspberry Pi.](images/Pi_21_Complete.png)

If you use a pin other than Pin 21, make sure that you change the number **everywhere** it appears in your code.

--- /task ---

--- task ---

Download and open the starter project [available here](https://rpf.io/p/en/scratch-led-game-get){:target="_blank"}.

--- collapse ---
---
title: Opening a downloaded Scratch 3 Desktop project
---

Once you have downloaded the zip file from the link above, open your file manager and navigate to the **Downloads** folder.

Find the file you just downloaded. It will end in `.zip`.

Right click on the file and choose 'Extract files'. Extract them to your downloads folder.

In Scratch 3 Desktop, click the `File` menu and choose `Load from your computer`.

Navigate to your downloads folder again and select the file `scratch-physcomp1.sb3`. 

Click `OK` or press `Enter`.


--- /collapse ---

--- /task ---

--- task ---

Make sure you have the Stage selected and you can see the following scripts:
![Screenshot of scripts. When green flag clicked.](images/stage_code.png)

--- /task ---

--- task ---

Using the `Simple Electronics`{:class="block3extensions"} extension, add the following blocks into the `if`{:class="block3control"} block so that if `distance`{:class="block3variables"} is less than `10`, the LED comes on — `else`{:class="block3control"} it turns off.

```blocks3
when green flag clicked
forever
if <[0] < (dist) > then
+turn LED (21 v) [on v] ::led extension
else
+turn LED (21 v) [off v] ::led extension
end
```

--- /task ---

--- task ---

Now click on the green flag, and see if you can hunt the hedgehog!

--- /task ---

--- save ---
