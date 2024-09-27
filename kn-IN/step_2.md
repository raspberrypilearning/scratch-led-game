## Test your circuit

In this step, you will connect an LED and resistor to the Raspberry Pi's GPIO pins to test your circuit.

GPIO stands for **G**eneral **P**urpose **I**nput/**O**utput. GPIO pins allow you to create simple machines by sending a small electrical signal out of a pin, down a wire, through an output or input, and back into a ground pin on the Raspberry Pi to create a circuit. The circuits you make can be programmed and controlled by you, through programs written using Scratch!

<p style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>
The jumper cables we use for prototyping have what are called **dupont connectors** on the ends of them to make it easy to create circuits and connect components. These connectors come in two main types: **Pin** and **Socket**. **Pin** connectors are so called because they have a small metal pin sticking out, while **socket** connectors have a small port that accepts a pin to make a connection.
</p>

--- task --- Your jumper wires should all have hollow socket ends that fit over the pins of your Raspberry Pi.

Connect a jumper wire to Pin 1. Pin 1 is always on and provides 3.3 volts to whatever you connect to it.

![Circuit diagram of a jumper wire connected to 3V3 on a Raspberry Pi.](images/Pi_jumper_Test1.png)

--- /task ---

--- task --- Insert the **long leg** of your LED into the other end of this jumper wire. Take a second socket to socket jumper wire and attach it to the **short leg** of your LED.

![Circuit diagram of a jumper wire with an LED wired in series to 3V3 on a Raspberry Pi.](images/Pi_LED_test2.png)

--- /task ---

--- task --- Take a resistor and insert one of its legs into the free end of the second jumper wire. Insert the other leg into another socket to socket jumper wire. Adding the resistor to your circuit reduces the **electrical current** passing through the circuit; this will protect the LED from burning out.

![Circuit diagram of a jumper wire with a resistor and LED wired in series to 3V3 on a Raspberry Pi.](images/Pi_resistor_test3.png) --- /task ---

--- task --- Now, connect your circuit back to Pin 6 using the loose end of the socket to socket jumper wire. As soon as you close the circuit by connecting it back to your ground pin, your LED should light up!

![Circuit diagram of a completed circuit with a jumper wire with a resistor and LED wired in series to 3V3 on a Raspberry Pi.](images/Pi_1_complete.png)

--- collapse ---
---
title: Help – My LED isn't working!
---
If your LED isn't lighting up, make sure you have the **long leg** connected to the output pin (Pin 1) and the **short leg** connected to the ground pin (Pin 6). LEDs only work one way round!

If your LED **still** isn't lighting up, check all your connections are secure and fit properly, then swap your LED for another one if it still won't work (this one might be broken). --- /collapse ---

--- /task ---


In the next step, you will swap your working circuit to a numbered control pin so that you can drive it using code!
