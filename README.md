# Overview

A program projecting population growth given a transition matrix and initial abundances of each age/stage/class. The program graphs abundance and proportional abundance over time, and outputs key values such as stable age distribution (right eigenvector of the transition matrix), stable growth rate (dominant eigenvalue of transition matrix), and both abundance and proportional abundances at the final time step.

<br/>

# Files

## Figures

**PP_Plots_1** *(.jpeg)* - Plots of abundance as a function of time for a hypothetical population with four different life stages.

**PP_Plots_2** *(.jpeg)* - Plots of proportional abundance as a function of time for a hypothetical population with four different life stages.

## Scripts

**PP_Script** *(.R)* - Script for running simulations and generating figures.

<br/>

# Featured Images

Abundance as a function of time for a hypothetical population with four different life stages. In this example, the starting population was 200, with 50 individuals per stage.

<kbd>![](https://github.com/TrevorHD/PopProjection/blob/master/Figures/PP_Plots_1.jpeg)</kbd>

Proportional abundance as a function of time for the same population shown in the previous image. The proportional abundance of each life stage eventually stabilises as time goes on, with the distribution of ages equal to the right eigenvector of the transition matrix.

<kbd>![](https://github.com/TrevorHD/PopProjection/blob/master/Figures/PP_Plots_2.jpeg)</kbd>
