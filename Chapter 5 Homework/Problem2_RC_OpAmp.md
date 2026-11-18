[← Back to overview](README.md)

# Problem 2. RC Op Amp

## Task

In LTSpice, build this RC circuit.

<img src="media/RC.png" width="400">

Set the capacitance value R = 100kΩ, C=1uF, RL=20kΩ

Input will be a periodic triangle signal, with the first period as:

$$v(t)= \begin{cases} -2+4t, & 0\le t<1\\\\[4pt] 6-4t, & 1\le t<2 \end{cases}  $$


--------
To represent such switch behavior, there is an easy way in LTSpice: **Advanced Voltage Source**

-----

## :orange: Required in your homework answer

1. Include a screenshot of the plot of the current thru the voltage source, $I_x$.

2. Include a quick calculation of Equivalent Resistance $R_{eq}$ based on $R_{eq}=V_x/I_x$.

3. Include a detailed derivation and calculation of Equivalent Resistance $R_{eq}$ based on series-parallel reduction, like what you show in recitation worksheet. 

   *(You may write the calculation by hand, take a clear photo, and insert the photo into the same document.)*
