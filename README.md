# HEP2Mathematica
Shell scripts that convert common HEP formats into Mathematica readable arrays. It can be used for parton-level output from MadGraph. It can be also used for Delphes ROOT output after converting it to LHCO format through root2lhco. 

[LHCOtoMathematica](./LHCOtoMathematica):
The script transfers the [LHCO](http://madgraph.phys.ucl.ac.be/Manual/lhco.html) information of a particle into an array of **{[particle ID](https://twiki.cern.ch/twiki/bin/view/Main/PdgId), x momentum, y momentum, z momentum, energy, number of tracks}**. Note that in the case of a lepton, the number of tracks is multiplied by the charge of the lepton (i.e. a muon -1, a positron +1).


[LHEtoMathematica](./LHEtoMathematica):
The script transfers the [LHE](https://arxiv.org/abs/hep-ph/0609017) information of a particle into an array of **{[particle ID](https://twiki.cern.ch/twiki/bin/view/Main/PdgId), x momentum, y momentum, z momentum, energy}**. 

## Usage
1. Ensure the script is executable (i.e. - run chmod a+x scriptname)
2. Run
```
./LHCOtoMathematica /path/to/event.lhco >> /path/to/event.dat
```
or
```
./LHEtoMathematica /path/to/event.lhe 1 1 1 >> /path/to/event.dat
```

## License
MIT
