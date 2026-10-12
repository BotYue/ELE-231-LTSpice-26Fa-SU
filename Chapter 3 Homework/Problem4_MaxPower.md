[← Back to overview](README.md)

# Problem 4. Max Power Transfer

## Task

We will study the Maximum Power Transfer of this circuit.

- [ ] You  pick a specific $R_{src}$ value based on your major.
- [ ] $R_{load}$ value will wait to be studied.
      
|Major|$R_{src}$|
|---|---| 
|ME| 220 Ω|
|AE| 330 Ω|
|EE|  470 Ω|
|CE| 560 Ω|
|Other| 680 Ω|


<img src="media/maxpower1.png" width="400">

-------

Second, In LTSpice, build circuit as such way.
- [ ] A similar video walk-thru can be found in https://youtu.be/BqnUZj3eUE0 
- [ ] Set $R_{load}$ value as {R}
- [ ] In LTSpice "Directive", enter such statement

```
.step param R 50 1000 10
```
- [ ] Run the DC operating points Analysis ("Analysis" -> "DC op pnt").
- [ ] Use the meassurement pen to plot
    * the node voltage above the $R_{load}$
    * the current thru the $R_{load}$
- [ ] In the plot, continue to configure by entering the algebric expression of power, such as `V(n002)*I(Rload)`.


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



