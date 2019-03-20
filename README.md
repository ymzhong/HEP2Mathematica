# HEP2Mathematica
Shell scripts that convert common HEP formats into Mathematica readable format.

## LHCOtoMathematica
The format of Large Hadron Collider Olympics (LHCO) data file is explained [here](http://madgraph.phys.ucl.ac.be/Manual/lhco.html). The LHCOtoMathematica script transfer the LHCO information for every particle into an array **{particle ID, p_x, p_y, p_z, energy, special}**. 
```
./LHCOtoMathematica /path/to/event.lhco >> /path/to/event.dat
```
