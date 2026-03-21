# Overview

A program projecting population growth given a transition matrix and initial abundances of each age/stage/class. The program graphs abundance and proportional abundance over time, and outputs key values such as stable age distribution (right eigenvector of the transition matrix) stable growth rate (dominant eigenvalue of transition matrix), and both abundance and proportional abundances at the final time step.

<br/>

# Files

## Scripts

**PopProjection** *(.R)* - Script for simulating stage-based population growth given initial conditions and a transition matrix.

## Figures

**PPPlots1** *(.jpeg)* - Plots showing, for a hypothetical population, abundance for each age/stage/class as a function of time.

**PPPlots2** *(.jpeg)* - Plots showing, for a hypothetical population, proportional abundance for each age/stage/class as a function of time.

<br/>

# Featured Images

Plots showing, for a hypothetical species with four different life stages, the abundance of each stage as a function of time after starting at a population of 200 with 50 individuals per stage.

<kbd>![](https://github.com/TrevorHD/PopProjection/blob/master/Figures/PPPlots1.jpeg)</kbd>

Plots showing, for the same hypothetical species with four different life stages, how the proportional aboundance of each stage for the aforementioned population changes over time and eventually stabilises.

<kbd>![](https://github.com/TrevorHD/PopProjection/blob/master/Figures/PPPlots2.jpeg)</kbd>
