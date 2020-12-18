# Fundamentals-Of-Data-Analysis-52446-Tasks
Repository containing the Tasks assessment for Fundamentals of Data Analysis in 2020, it contains all tasks within a single Jupyter Notebook.

This Repository has been created by - Keith Ryan (G00387816@gmit.ie)

The general structure of the notebook is a series of Tasks that were assigned throughout the semester. The tasks themselves are broken up into sections using Jupyter's Markdown cells and under each task is a description which is generally followed by a section on researching the task and attempting some solutions, after this subsection follows a section formalising the earlier work (usually into a function), in a few cases where I found some aspect of the task interesting I break off to explore that a bit and this is called out in the markdown to denote that it is not strictly the assigned task.

## Running the notebook
The jupyter notebook can be ran in your own python environment using either "Jupyter Notebook" or "Jupyter Lab" and there are relatively few packages used throughout.
Within your Python Environment you will need:
- numpy
- Seaborn

The remaining packages used should be present as part of a standard Python environment but just incase, they are:
- matplotlib
- strings
- IPython
- random

## Requirements for Tasks
The following sections define the requirements for the various tasks, I have not included my own interpretation for these tasks or a description of the work done for each, as these can all be found within the Markdown cells for the Tasks and will make a lot more sense when viewed alongside the context of the code cells.

### Task 1 - counts function
Write a Python function called counts that takes a list as
input and returns a dictionary of unique items in the list as keys and the number of
times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A']
should have output {'A': 3, 'B': 1, 'C': 1} . Your code should not depend
on any module from the standard library1 or otherwise. You should research
the task first and include a description with references of your algorithm in the
notebook.

### Task 2 - dicerolls function
Write a Python function called dicerolls that simulates
rolling dice. Your function should take two parameters: the number of dice k and
the number of times to roll the dice n. The function should simulate randomly
rolling k dice n times, keeping track of each total face value. It should then return
a dictionary with the number of times each possible total face value occurred. So,
calling the function as diceroll(k=2, n=1000) should return a dictionary like:
{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}

### Task 3 - coinflip heads distribution
The numpy.random.binomial function can be used to
simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a
coin is flipped many times then the number of heads is well approximated by a
bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of
getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively
low, and the chances of getting any other number of heads decreases as you move
away from 50 in either direction towards 0 or 100. Write some python code that
simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track
of the number of heads in each of the 1,000 simulations. Select an appropriate
plot to depict the resulting list of 1,000 numbers, showing that it roughly follows
a bell-shaped curve. You should explain your work in a Markdown cell above the
code.

### Task 4 - Simpson's Paradox
Simpson’s paradox is a well-known statistical paradox
where a trend evident in a number of groups reverses when the groups are combined
into one big data set. Use numpy to create four data sets, each with an x array
and a corresponding y array, to demonstrate Simpson’s paradox. You might
create your x arrays using numpy.linspace and create the y array for each
x using notation like y = a * x + b where you choose the a and b for each
x , y pair to demonstrate the paradox. You might see the Wikipedia page for
Simpson’s paradox for inspiration.
