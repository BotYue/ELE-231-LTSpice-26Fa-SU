[← Back to overview](README.md)

# Problem 4. Nodes in a Complex Circuit

## Task

In LTSpice, build this circuit with one voltage source, one current source, and multiple resistors.

To find a current source, you can simply press ''i" on keyboard, or find it from "Edit"-> "Component"->"Current"

<img src="media/image7.png" width="400">

- Set the numerical value of the voltage source as x V.
- Set the numerical value of the current source as y A.
- x, y values have been specified on the [README page](README.md)

----

With LTSpice, you can quickly check how many distinct nodes in a circuit. To do so, configure the "Analysis" to "DC op pnt" (DC operating point analysis).

<img src="media/image8.png" width="400">

Run the Analysis. A pop-out window will show the analysis report as a list. This report lists all distinct nodes except Ground.

To identify which node corresponds to which location in your circuit:
1. Go back to your circuit schematic.
2. Hover your mouse cursor over each node/wire.
3. At the bottom of the LTspice window, a text line will show, such as "This is node N001".

-----

## :orange: Required in your homework answer

1. Include a screenshot of your circuit schematic.
2. Include a LTSpice report of the DC operating point analysis. (*direct paste the list result*)
3. Indicate how many distinct nodes are in the circuit (except Ground).
4. Based on what you learned from class/textbook, indicate which nodes are extraordinary nodes (except Ground).
