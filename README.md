# Lab 26: Glorious Plotting!

##### April 10, 2020
---

Today is to be an introduction to the fundamentals of plotting in Matplotlib with the object-oriented api (interface). So such, learning objectives will focus on:
- [ ] Creating basic figure and axes objects
- [ ] Adding plots to axes objects
- [ ] Modifying properties of plots
- [ ] Adding labels and title to plots

_For practice today, even if you are a whizz at using the `numpy` library, please restrict yourself to the standard python library. The only imports should be for Matplotlib itself and then `math` library for access to $\sin(x)$._

## Instructions
The goal today is to create a visualization that has a few parts to it. In particular, we want to make a single figure that holds two axes objects (how they are oriented is completely up to you) which will plot:
* $\frac{\sin(x)}{x}$ over the interval -10 to 10
* The Fibonnacci sequence over the first 20 terms

#### Part A)
Create a figure and insert two axes objects into that figure. How you want to do that or how you want to orient or size the axes relative to one another is completely up to you. Make sure you give the axes (and figure) names (or handles) so that you can access them later!

#### Part B)
Construct two lists which contain the x and y values to plot the function sin(x)/x from -10 to 10. You should choose your intervals between points to be small enough so that the curve will look smooth. Add this plot to the first of your axes. Make it a dashed green line with a width of 3.

_Warning: If your sequence of x values includes exactly 0, this function will explode! So make sure it does not!_

#### Part C)
Construct two lists which contain the x and y values to plot the first 20 terms of the Fibonnacci sequence. You'll probably want to define or grab a previous definition of the Fibonnacci function to use in this instance. The x values should be the term number and the y values the value of that term of the sequence. Add your plot to the second axes object. Use large markers connected by red lines.

#### Part D)
Add meaningful axes labels to all your axes objects. Also add an axis title to both axes objects and include a figure title as well.
