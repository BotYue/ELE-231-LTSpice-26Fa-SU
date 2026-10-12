[← Back to overview](README.md)

# Problem 3. Thevenin

## Task

First, for this circuit, find its Thevenin equivalent circuit at terminals (a,b)

Obtain $V_{Th}$ and $R_{Th}$. You need to show your detailed calculation by hand.

<img src="media/Vth1.png" width="600">

-------



Second, In LTSpice, build this circuit with resistors.

<img src="media/Vth2.png" width="600">

* Top one is the original circuit with a large load $R_{load} =99 \Omega$
* Bottom one is the equivalent one with the same load $R_{load} =99 \Omega$
* For the bottom one, you will set up the voltage source **V2** as the green arrow indicated.
  <br> The DC value of **V2** will be your caulcated $V_{Th}$.
  <br> The series resistance of **V2** will be your calculated $R_{Th}$.
* Run the 

--------
Run the DC operating points Analysis ("Analysis" -> "DC op pnt"). 

A pop-out window will show the analysis report as a list. This report lists all distinct nodes except Ground.

To identify which node corresponds to which location in your circuit:

1. Go back to your circuit schematic.
2. Hover your mouse cursor over each node.
3. At the bottom of the LTspice window, a text line will show, such as "This is node n001".

-----

## :orange: Required in your homework answer

1. Include a screenshot of your circuit schematic.

2. Include a LTSpice report of the DC operating point analysis. (*direct paste the list result*)

3. Provide a detailed, step-by-step nodal analysis to this circuit. You should write it as detailed as the instructor showed in class. (step 1...step 2... step 3...)
   <br> You are expected the get the same final results as the simulation.

   *(You may write the calculation by hand, take a clear photo, and insert the photo into the same document that you work on.)*



