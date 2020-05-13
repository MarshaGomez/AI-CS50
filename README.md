# AI-CS50
Artificial Intelligence Example power by CS50. Python using Depth-First (Stack) and Breath-First (Queue) algorithms.

# Main Idea
The main idea of this code is solve to figure out how to actually get form the point A to point B, like a puzzle solution. We apply some concepts of Artificial Intelligence like Depth-First and Breadth-First search for generate the optimal solution.

An easy example of the input is that you have the Point **A** (Initial state), the Point **B** (goal test) and for simulate the blocked spaces we add **#**: 

```
#####B#
##### #
####  #
#### ##
     ##
A######
```

The path cost is represented by:

```
█████B█
█████ █
████  █
████ ██
     ██
A██████
```


And the Solution adding the optimal path with an asterisc *:

```
Solving...
States Explored: 11
Solution:

█████B█
█████*█
████**█
████*██
*****██
A██████
```
