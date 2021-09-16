Getting Started
===============

With this first assignment, we will introduce and install several different
software tools. This can be somewhat overwhelming, but with a bit of work,
reading, and using the tools you will quickly be able to use the tools. With a
bit more practice, you will become comfortable using the tools. The goal in this
first assignment is to get you using these tools quickly, and make sure you have
the resources to continue developing your skills with the tools throughout the
semester. Specifically, the goals for this assignment are for you to be able to:

1.  Use the fundamentals of the python language to write simple programs and
    functions.
2.  Use the Jupyter notebook system for scientific data analysis and plotting.
3.  Use Git basic commands to create a local Git repository, add files to that
    repository, and commit changes.
4.  Work with GitHub to fork a repository, clone it to your local computer,
    commit changes, and push changes back to the online repository and use pull
    requests to submit and discuss work.

Assignment
==========

For this assignment:

-   Read about the software packages in the [Software Introduction](Software_Introduction.pdf) document.
-   Install the software tools on your personal computer as instructed in [Software Installation](Software_Installation.pdf).
-   With your software, work through the **Resources** listed in the [Software Introduction](Software_Introduction.pdf) document.
-   Go through the [Git Tutorial](https://try.github.io/levels/1/challenges/1).
-   Check out the other resources listed in the [Git Introduction](Git_Introduction.pdf) document.
-   Create your own repository for this assignment and clone it to your computer following the [Instructions for Cloning Assignment](Instructions_for_Cloning_Assignment.pdf)
-   Using [The Python Tutorial](https://docs.python.org/3/tutorial/) and [Simple Programs](https://wiki.python.org/moin/SimplePrograms), create a single python file, named 'First.py', which:
	-    Prints 'Hello World'.
	     *Note:  In python 3.0 and above, print is a function, not a statement.  So, 'print "Hello World"' will give an error.  Use 'print("Hello World")' instead.*
	-    Uses a [loop strucuture](https://docs.python.org/tutorial/controlflow.html#more-control-flow-tools) to print the numbers 1 - 10.
	-    Uses another loop structure as well as [a list](https://docs.python.org/3/tutorial/introduction.html#lists) to print the number names, "one, two, three ..." from zero to ten.
-   Create a Jupyter notebook, titled 'FirstNotebook'. In that notebook, complete the tutorial titled [Using Jupyter Notebook with PyCharm](https://www.jetbrains.com/help/pycharm/2016.1/tutorial-using-ipython-jupyter-notebook-with-pycharm.html) from JetBrains’ website. In doing so, you will:
    -    Create a Jupyter notebook file (Please create this file in this project, and be sure to add it to the git repository.)
    -    The tutorial does not include it, but demonstrate that it can calculate that 2 + 2 is 4.
    -    Import a python module.
    -    Create a graph.
    -    View the notebook in a web browser.
    -    The tutorial does not have you do this, but edit the notebook in the browser.
    -    Also have the notebook perform calculations (press shift – enter while on a cell).
    -    Add some headings – View these in the web browser as well.
    -    Write an equation in LaTeX and display it. You can make a simple one using the LaTeX code `a^2+b^2=c^2`.
    -    The tutorial does not have you do this, but:
         -    Close PyCharm
         -    At the command line type jupyter notebook (Assuming Acaconda was added to your path variable)
         -    Open your browser to view the jupyter interface.  The address is probably [127.0.0.1:8888](http://127.0.0.1:8888/)
         -    Add a heading 'Final Calculation' to the end of the document and in the following cell, calculate 10*10-100
-   If we have time: Investigate solving $\frac{\textrm{d}P}{\textrm{d}t}=rP$ using numerical methods
    -   Write a python function that uses finite difference methods to simulate the population growth. Like the example in your text, use $P_0=100$, $r=0.1$, and a time step size of 0.005, $\Delta t =0.005$. You may want to write out pseudocode before you write in python.
    -   Create a Jupyter notebook and plot your simulation results for population vs. time. Add an appropriate title and axis labels to this graph.
    -   In your previous graph, have the population data displayed with red hexagon markers with a transparent face. You might want to check the [matplotlib documentation for plot](http://matplotlib.org/api/pyplot_api.html#matplotlib.pyplot.plot). Also, setting the color alpha value to zero will make the marker transparent as described on [this stackoverflow discussion](http://stackoverflow.com/questions/15928539/matplotlib-how-to-make-the-marker-face-color-transparent-without-making-the-li).
    -   On a single graph, have plots for the population vs time for different time step sizes,$\Delta t$. Create at least four different plots with $\Delta t$ values ranging from 0.005 to 1.
    -   Create a plot of the simulation error vs time for the simulations you created in the previous step. Note that the simulation error is the difference between the exact value and the simulation value. For this, you may want to look at the [range function](https://docs.python.org/3.5/tutorial/controlflow.html#the-range-function) in python.
    -   As a final step in understanding the effect of the step size on simulation error. Plot the value of the population at $t=100$ as a function of time step size, $\Delta t$.
    -   Document your work and turn in this problem. In doing so, you need to create appropriate headings and add text regions which discuss your work. You need to include at least one LaTex equation. For this, you should check out the linked pages on [markdown formatting](http://daringfireball.net/projects/markdown/basics), and [LaTeX](http://www.auburn.edu/~tamtiny/Symbols.pdf).
