# Fitting oscillation mode frequencies with a Correlated Systematic Noise Model (CSNM)

# Overview

Welcome to Tanda's repo. This repo presents a fitting method for asteroseismic modelling (detailed modelling). Detailed descriptions of the method can be seen in Li et al. (2022), MNRAS, submitted (link to be update.)

The detailed modelling of stellar oscillations is a powerful approach to characterise stars. However, poor treatment of systematics in theoretical models leads to misinterpretations of stars. Here we propose a better statistical treatment for the systematics to be applied to fitting individual mode frequencies with a typical stellar model grid. We introduce a correlated noise model based on a Gaussian Process (GP) kernel to describe the systematics given that mode frequency systematics are expected to be highly correlated. We show that tuning the GP kernel can reproduce general features of frequency variations for changing model input physics and fundamental parameters. Fits with the correlated noise model better recover stellar parameters then traditional methods which either ignore the systematics or treat them as white noises. 

# Understand the method

0. Please start with the paper (link to be update) for detailed descriptions of the method and why we want this noise model in the asteroseismic fitting.
1. The jupyter notebook named '1_study_note.ipynb' demostrates the underlying priciple of the correlated systematic nosie model. 
2. An application of the method to a fake star is demostrated in the notebook named '2_fitting_a_fake_star.ipynb'.
