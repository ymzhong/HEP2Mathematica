# HEP2Mathematica
Shell scripts that convert common HEP formats into Mathematica readable format.

[LHCOtoMathematica](LHCOtoMathematica.sh):
The format of Large Hadron Collider Olympics (LHCO) data file is explained [here](http://madgraph.phys.ucl.ac.be/Manual/lhco.html). The LHCOtoMathematica script transfer the LHCO information for every particle into an array **{particle ID, x momentum, y momentum, z momentum, energy, no of tracks}**. The no of tracks , i.e., 7th column in LHCO event, gives the number of tracks associated with the object; in the case of a lepton, this number is multiplied by the charge of the lepton.  
