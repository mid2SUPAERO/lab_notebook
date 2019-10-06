# lab_notebook
Here is a one page help to help you to describe your numerical experiments (NE).


## Full Name and date
Exemple: Joseph Morlier, tuesday the 12th of September 2019

## Resume WITH A SCHEMA
In 3 lines, try to resume the big picture of your NE.



## Physics
Let's define first the physics embedded in your problem and  level of fidelity of your NE:
Exemple: Fluid and Structures
add basic physical hypothesis, linearity / NL, type of solver/tolerances
Control is a physics?

## Level of fidelity
Describe the methodology with full references
Example: in Fluid Dynamics / CFD

LO Empiricial equation /regression

L0+ lifting line

L1 DLM/VLM

L2 RANS 

L2+ LES etc...

## Mesh with a GRAPH per physics
check convergency

## Analysis
Please, Recap also the tuning of the physical solver

## Mapping
Describe the methodology with full references

space/time/both

## MDO with the XDSM
Describe the methodology with full references

If you are using openMDAO, please use the last version

## Surrogate Modeling
Describe the methodology with full references (RBF, GP, ...)

Please describe how you constructed and validated your surrogate
Precise the Kernel, and hyperparameter tuning

## Reduced Order Modeling
Describe the methodology with full references (SVD, ...)

## Type of variables
x can be continuous, discrete, categorial ...hybrid

## Optimization with GRAPHS: Optimality / Feasibility 
Describe the methodology (Gradient Based, GA, Bayesian Optimization/EGO ...)

Constrained or unconstrained ?
Use derivative or not ?
Sensibility computed using ? FD, Complex step, Analytic, Semi Analytic

Clearly define the objective function (mono, multi) and the constraints (equality, inequality)

min f(x)

wrt g(x)<=0

    h(x)==0
    
and bounds for x

Can you write a linear system for constraints?
    
define the optimizer (SLSQP for example) and associated tolerances and or stopping criteria


Provide X0, Xn, X* (sometimes it's nice to see the evolution at n, please choose n)



Multistart ?

## Packages Used
Upload here your codes and precise here the dependencies
    
    







