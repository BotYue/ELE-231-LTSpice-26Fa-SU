[← Back to overview](README.md)

# Problem 2. Voltage-Controlled Current Source (VCCS)

## Task

In LTSpice, build this circuit with resistors.

<img src="media/dual_loop_diagram.png" width="600">

#### How to build a voltage-controlled source in LTSpice

Go to "Component", find the one named "g2".

<img src="media/ltspice_g2.png" width="500">

Add other components, make the circuit schematic look like such,

<img src="media/ltspice_g2_dual_loop.png" width="700">

Next, we need to realize the $I=2V_{AB}$ in this circuit. 
- [ ] To do so, we use the "Label Net" in LTSpice to establish the electrical connection from Node A, NodeB to the dependent source.
- [ ] Label two nodes on the left loop as "A" and "B"; Then label the two extra terminals of the dependent source also as "A" and "B".
<br> In Label Net, "Node Type" all set to "None"

- [ ] Final schematic should look like such. Also don't forget to use your assigned x, y values from [README page](README.md)


---------

Configure Analysis -> Transient.

Stop Time: 0; Time to start saving data 0; Max timestep: 1

Hover your mouse cursor over each resistor. At the bottom of the LTspice window, you can see the power dissipation of that resistor.

-----

## :orange: Required in your homework answer

1. Include a screenshot of the plot of the current flowing thru R1
2. Include a screenshot of the plot of the voltage drop across R1
3. Include a screenshot the power dissipation of R1 shown by LTSpice
4. Calculate the power dissipation of R1 yourself. Use the formula $P=V\cdot I$, and with the current and voltage readings from LTSpice.
