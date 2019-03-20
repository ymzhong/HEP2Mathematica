# HEP2Mathematica
Shell scripts that convert common HEP formats into Mathematica readable format.

## LHCOtoMathematica
The Large Hadron Collider Olympics (LHCO) format is explained [here](http://madgraph.phys.ucl.ac.be/Manual/lhco.html). The LHCOtoMathematica script transfer the LHCO information for every particle into {particle ID, p_x, p_y, p_z, energy, special}. 
```
./LHCOtoMathematica /path/to/event.lhco >> /path/to/event.dat
```
