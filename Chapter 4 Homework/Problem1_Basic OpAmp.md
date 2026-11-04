[← Back to overview](README.md)

# Problem 1. Basic OpAmp Built-up

## Tutorial
All Op-Amp circuits in our ELE 231 course will be in the setting of **ideal op-amp with negative feedback.**

This tutorial shows you how to set up a simple voltage follower (also called as buffer amp) in LTSpice.

- [ ] For the component, select from **"Component -> OpAmps folder -> opamp"**, as shown in this pic.

<img src="media/single_pole_amp.png" width="500">

- [ ] To make schematic look clean, put input source symbols aside, instead of directly connecting input source symbols to the op-amp. 
- [ ] To do this, use **Label Net**. Two pins with the same net label are electrically connected, even if no wire is drawn between them.
- [ ] You can also set net labels as **Input** or **Output** to make schematic easier to understand.

- [ ] To conduct simulatation, add this to **SPICE Directives**

```
.lib opamp.sub
```

- [ ] Finally, perform DC operating points analysis **DC op pnt**.
- [ ] The final schematic looks like such:
      


## Task

In LTSpice, build this circuit with resistors.

Set the **R1** and **R4** values, based on the **x, y**  on the [README page](README.md)

<img src="media/single_pole_amp.png" width="600">



-----

## :orange: Required in your homework answer

1. Include a screenshot of your circuit schematic.

2. Include a LTSpice report of the DC operating point analysis. (*direct paste the list result*)

3. Provide a detailed, step-by-step nodal analysis to this circuit. You should write it as detailed as the instructor showed in class. (step 1...step 2... step 3...)
   <br> You are expected the get the same final results as the simulation.

   *(You may write the calculation by hand, take a clear photo, and insert the photo into the same document that you work on.)*



