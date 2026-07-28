# GLIMMER<br>Microbial Gene-Finding System

## Installation and Running

Full installation and usage instructions are available in the [glim302notes.pdf](glim302notes.pdf) file 
and in the [repository wiki](https://github.com/salzberg-lab/glimmer/wiki).

## Quick Start 

- To build all Glimmer programs, go to the src directory and type make
  (or alternately gmake).  This will create all the executable files
  in the directory bin.  Note that initially directories bin, lib and
  obj are all empty.

- Scripts for running the programs are in directory scripts.  Each
  needs to be edited near the top to specify the correct location
  (give the full path) where you have the bin and scripts directories
  on your system.  Script g3-iterated.csh is generally the best to use
  to make gene predictions from a single genome sequence without other
  data.

- Some scripts (including g3-iterated.csh) use the program elph, which
  needs to be separately downloaded and installed.  You can get it from
  ccb.jhu.edu/software/ELPH/index.shtml

- Help on options and command parameters for each program can be gotten
  by running the program with a -h option.
	
## Publication

[Salzberg SL, Delcher AL, Kasif S, White O. Microbial gene identification using interpolated Markov models. Nucleic Acids Res. 1998 Jan 15;26(2):544-8. doi: 10.1093/nar/26.2.544. PMID: 9421513; PMCID: PMC147303.](https://pmc.ncbi.nlm.nih.gov/articles/PMC147303/)
