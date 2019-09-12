# lab_notebook
Here is a one page help to help you to describe your numerical experiments.




Let's define first the physics embedded in your problem and  level of fidelity of your  experiments:

## Physics

Fluid and Structures for example
basic physical hypothesis, linearity / NL, solveur

## Level of fidelity
LO Empiricial equation /regression
L0+ lifting line
L1 DLM/VLM
L2 RANS 
L2+ LES etc...

Examples in Fluid Dynamics / CFD


## Mesh 

Is it really important ?

## Analysis

Please, Recap also the tuning of the physical solver


## Mapping

Describe the methodology with full references


## MDO

If you are using openMDAO, please use the last version

Add an image (with source) of your XDSM

## Surrogate Modeling

Please describe how you constructed and validated your surrogate

## Reduced Order Modeling

Please describe the methodology (SVD, ...)


## Optimization

Constrained or unconstrained
Use derivative or not ?
Sensibility computed using FD, Complex step, Analytic, Semi Analytic

Clearly define the objective function (mono, multi)


min f(x)
wrt g(x)<=0
    h(x)==0
and bounds for x
    
define the optimizer (SLSQP) and associated tolerances and or stopping criteria

## Packages Used

Upload here your codes and precise here the dependencies
    
    







