## Mathematica Software for the Numerical Generation of Given Distribution with Exponential Autocorrelation Function

This directory includes Mathematica files for generation of samples of a random processes with a given probability density function (PDF) and  with an exponential autocorrelation function (ACF). These files also provide a statistical validation of the resulting processes.

The following files are included:
- `ProcessWithExpACF.nb` and `ProcessWithExpACF.m`: Mathematica module for random process generation.
- `Laplase_Dist_Example.nb`: Module applied for generation of Laplace distribution.
- `Chi-Square.nb`, `HalfNormal_Dist.nb`, `Laplase_Dist_Example_with_Validation.nb`: The generation module is applied for χ2, half-normal and Laplase distributions together with validation of code results.
- `Laplase_Dist_nomod.nb`: The process generation is performed inside the same file without module applied.

Note: The length of generated sequence influences the validation results. For the best visual results the number of samples, **length**>= 5*10^6. The main drawback is that takes time...

[comment]: # (supplementary downloadable material, provided by the authors of the paper:)
[comment]: # (D. Bykhovsky and V. Lyandres, "**On the Numerical Generation of Positive-Axis-Defined Distributions with Exponential Autocorrelation Function**")

This source code was created and verified with version 11 of Mathematica.