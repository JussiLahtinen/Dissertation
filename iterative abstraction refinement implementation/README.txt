
The algorithm has at least the following dependencies:
- NuSMV-2.5.4 model checker
- ABC/ZZ bip model checker
- python
- zsh shell
- AIGER 1.9.9 tool package
- liveness-to-safety reduction tool (see l2s4lmcs_Revised)
- smvflatten tool (optional, NuSMV flattening also supported)

The 'patches' directory contains a patch that fixes a 
problem with the smvtoaig tool in the AIGER tool package.

Linux/unix based systems are supported. 
On windows it is recommended that for example VirtualBox with Ubuntu is used.
There are some problems when Windows is used with cygwin and this option is not fully supported.


The zip-file also contains a fictional model that
can be used for testing the algorithm.
The command to do this is e.g.:
python algorithm_2014.py --specfile "fictional-model\specs.txt" "fictional-model\main_annotated.smv"
