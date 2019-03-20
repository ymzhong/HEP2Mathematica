# HEP2Mathematica
Shell scripts that convert common HEP formats into Mathematica readable format.

[LHCOtoMathematica](./LHCOtoMathematica):
The script transfers the [LHCO](http://madgraph.phys.ucl.ac.be/Manual/lhco.html) information for a particle into an array of **{particle ID, x momentum, y momentum, z momentum, energy, no of tracks}**. Note that in the case of a lepton, the no of tracks is multiplied by the charge of the lepton.  
