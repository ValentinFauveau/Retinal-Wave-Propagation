# Retinal-Wave-Propagation
Simulation of the wave propagation during development based on the model described by Godfrey et al. (2007)

I propose a code implemented in Matlab in order to simulate the behavior described in the paper "Retinal Wave Behavior through Activity-Dependent Refractory Periods" by Godfrey et al. in 2007.

## Introduction

Before the light which enter through the eye, activate the rods and cones, this light must travel through the thickness of the retina. Therefore, the photoreceptors absorb the photons and transform the stimulus into an electrical message that stimulates all the succeeding neurons of the retina. The amacrine cells are interneurons that interact at the second synaptic level. The spontaneous activity of the retinal amacrine cells during the development takes the form of spreading patches through the retina contributing on the visual system organization during the development. 
In order to understand the mechanism behind this behavior, the model presented in the paper takes account that spontaneous depolarization of amacrine cells can drive a wave, the locally connection of them and that cells receiving more input during their depolarization are then less responsive and have a longer inter-depolarization period.

For modeling the amacrine cells we use a hexagonal grid of nxn cells. 

## Graphical User Interface 
The user has to select the size of the hexagonal matrix, the studied specie, the duration of the analysis and if he wants to add or not noise to the experiment.

![gui](https://user-images.githubusercontent.com/35737567/45521327-710fd400-b78b-11e8-8408-a7624716adcd.png)
