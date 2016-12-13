## Mathematica Software for the Numerical Generation of Given Distribution with Exponential Autocorrelation Function

This directory includes Mathematica files for generation of samples of a random processes with a given probability density function (PDF) and  with an exponential autocorrelation function (ACF). These files also provide a statistical validation of the resulting processes.

The generation method is based on creation of an appropriate stochastic differential equation (SDE) of the first order and solving it by implicit Milstein methods.

The following files are included:
- `ProcessWithExpACF.nb` and `ProcessWithExpACF.m`: Mathematica module for random process generation.
- `Chi-Square.nb`, `HalfNormal_Dist.nb`, `Laplase_Dist.nb`: The generation module is applied for χ2, half-normal and Laplase distributions.
- `Laplase_Dist_nomod.nb`: The process generation is performed inside the same file without module applied.

Notes: 

1. The length of generated sequence influences the validation results. For the best visual results the number of samples, **length**>= 5*10^6. The main drawback is that takes time...
2. χ2 and half-normal distributions are defined only for positive values, i.e. f(x)=0 for x<0. Moreover, a half-normal distribution has a discontinuity in the orign.

[comment]: # (supplementary downloadable material, provided by the authors of the paper:)
[comment]: # (D. Bykhovsky and V. Lyandres, "**On the Numerical Generation of Positive-Axis-Defined Distributions with Exponential Autocorrelation Function**")

This source code was created and verified at version 11 of Mathematica.
