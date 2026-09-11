[← Back to overview](README.md)

# Problem 5. LED

## Task

In LTSpice, build this circuit with resistor and LED.

||
|---|
|<img src="media/led - Copy.png" width="600">|

- [ ] To find the led, go to "Component", then "LED"
- [ ] Once placed on schematic, right click the led symbol, go to "Pick New Diode"
- [ ] You  pick a specific diode **based on your major**: 
<br> EE, CE: LXZ1-PB01; ME: LXZ1-PD01; AE: LXZ1-PE01; Other: LXZ1-PH02
<br> These all appear at the very end of the list.

<img src="media/led2 - Copy.png" width="600">

- [ ] Then "Configure Analysis", "DC sweep", source as "V1", linear, start 0, stop 5, increment 0.01.
- [ ] OK, then click the current thru the led, you will get an $i-v$ curve


-----

## :orange: Required in your homework answer

1. Include a screenshot of the plot of the current flowing thru R1
2. Include a screenshot of the plot of the voltage drop across R1
3. Include a screenshot the power dissipation of R1 shown by LTSpice
4. Calculate the power dissipation of R1 yourself. Use the formula $P=V\cdot I$, and with the current and voltage readings from LTSpice.
