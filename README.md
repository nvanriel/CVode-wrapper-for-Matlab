CVode-wrapper-for-Matlab
========================

The CVode package generates compiled MEX (Matlab Executables) files for the simulation of Ordinary Differential Equation (ODE) models, composed of systems of coupled nonlinear ODEs.

The CVode package can generate compiled MEX files for the simulation of Ordinary Differential Equation (ODE) models, composed of systems of coupled 1st order ODEs.

The CVode Wrapper package for Matlab includes:

1) a parser to convert a Matlab m-file containing the ODE's to a C-file

2) compile the C source file and the numerical integrators from the SUNDIALS CVode package into a MEX file that can be run in Matlab

3) installation and usage instructions

4) a parser to convert a SBML model to a m-file that can be simulated with the built-in ODE-solvers of Matlab

In case you use the wrapper and publish results obtained with the software, please refer to the following paper: 
Vanlier J, Tiemann CA, Hilbers PA, van Riel NA. Bioinformatics, 2012; 28(8): 1130-5. doi: 10.1093/bioinformatics/bts088
