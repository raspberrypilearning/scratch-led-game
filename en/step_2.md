## Test your circuit

In this step, you will connect an LED and resistor to the Raspberry Pi's GPIO pins to test your circuit.

GPIO stands for **G**eneral **P**urpose **I**nput/**O**utput, which is a way to create simple machines by sending a small electrical signal out of a pin, down a wire and through an output or input, then back into a ground pin on the Raspberry Pi to create a circuit. The behaviour of the circuits you make can be programmed and controlled through programs written by you, using Scratch!

--- task ---
Your jumper wires should all have hollow 'F' ends that fit over the pins. 

Connect a jumper wire to Pin 1, making sure it is an F-F wire. Pin 1 is always on and provides 3 volts of power to whatever you connect to it.  

![circuit diagram of a jumper cable wired to 3V3 on the Raspberry Pi](images/Pi_jumper_Test1.png)

--- /task ---

--- task ---
Insert the **long leg** of your LED into the end of this jumper cable. Take a second F-F jumper cable and attach it to the **short leg** or your LED.

![circuit diagram of a jumper cable with a LED wired in series to 3V3 on the Raspberry Pi](images/Pi_LED_test2.png)

--- /task ---

--- task ---
Take a resistor and insert one of it’s legs into the other end of the jumper cable. Insert the other leg into another F-F jumper cable. We add a resistor to our circuit to control the **electrical current** passing through it, to protect the LED from burning out. 

![circuit diagram of a jumper cable with a resistor and LED wired in series to 3V3 on the Raspberry Pi](images/Pi_resistor_test3.png)
--- /task ---

--- task ---
Now, connect your circuit back to Pin 6 using the the loose end of the F-F jumper cable. As soon as you close the circuit by connecting it back to your ground pin, your LED should light up! 

![circuit diagram of a jumper cable with a resistor and LED wired in series to 3V3 on the Raspberry Pi](images/Pi_1_complete.png)

--- collapse ---
---
title: Help - My LED isn't working!
---
If your LED isn't lighting up, make sure you have the **long leg** connected to the output pin (Pin 1) and the **short leg** connected to the ground pin (Pin 6). LEDs only work one way round!

If your LED **still** isn't lighting up: check all your connections are secure and fit properly, then swap your LED for another one if it still won't work (this one might be broken).
--- /collapse ---

--- /task ---


In the next step, we will swap our working circuit to a numbered control pin so that we can drive it using code!
