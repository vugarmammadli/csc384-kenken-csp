# CSC384 - Introduction to AI, Summer 2017

## Homework Assignment 2: Constraint Satisfaction

[Kenken puzzle](https://en.wikipedia.org/wiki/KenKen) has the following formal description:
* Kenken consists of an **nxn** grid where each cell can be assigned a number 1 to n, so that no digit appears more than once in any row or column. Grids range in size from 3x3 to 9x9. Additionally, Kenken grids are divided into heavily outlined groups of cells - or 'cage'. The numbers in the cells of each 'cage' must produce a certain 'target' value when combined using a specified mathematical operation. These operations may be either addition, subtraction, multiplication or division. Note that values in a 'cage' can be combined in any order; the first number in a 'cage' may be used to divide the second, for example, or vice versa.

### Introduction

There are two parts to this assignment:

* the implementation of two constraint propagators – a Forward Checking constraint propagator, and a Generalized Arc Consistence (GAC) constraint propagator, along with the variable ordering heuristic of Minimum Remaining Values (MRV),
* the encoding of a CSP model to solve the logic puzzle, “Kenken”, as described above.

### Propagators and Variable ordering

Implemented python functions to realize two constraint propagators – a Forward Checking constraint propagator and a Generalized Arc Consistence (GAC) constraint propagator, and the variable ordering heuristic Minimum Remaining Values (MRV). The files cspbase.py, propagators.py and orderings.py provide the complete input/output specification of the three functions you are to implement.

### Kenken model

Implemented a CSP encoding to solve the logic puzzle, Kenken. The file kenken_csp.py provides the complete input/output specification of the CSP encoding you are to implement.

## Extra details

To get extra details about the specifications of the assignment, please read [Assignment Handout](A2.pdf).
