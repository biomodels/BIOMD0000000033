

Contact Ryan Gutenkunst (rng7@cornell.edu) for any questions on the
SBMLization or annotation of this model.

KS Brown KS and JP Sethna  
"Statistical mechanical approaches to models with many poorly known
parameters."  
Physical Review E 68:021904 (2003)  
PMID: 14525003

KS Brown, CC Hill, GA Calero, CR Myers, KH Lee, JP Sethna, and RA Cerione  
"The statistical mechanics of complex signaling networks: nerve growth factor
signaling"  
Physical Biology 1:184-195 (2004)  
PMID: not yet indexed

### Notes:

The figures in the paper show results from computations performed over an
ensemble of all parameter sets that fit the avaiable data. This file contains
only the best fit parameters. The full ensemble of parameters is available at
http://www.lassp.cornell.edu/sethna/GeneDynamics/PC12DataFiles/ (Also, the
best-fit parameter set produces a curve for DN Rap1 that is less "peakish"
than the ensemble average.)

The conversion factors for EGF and NGF concentrations account for their
molecular weights and the density of cells in the culture dish. These
concentrations are saturating, so the exact values are not critical.

Because the Erk data fit to measure only fold changes in activity, there is no
absolute scale for the y-axes. Thus the curves from this file have different
magnitudes than those published.

To reproduce the figures from the paper:  
2a) For EGF stimulation, set the initial concentration of EGF to 100 ng/ml *
100020 (molecule/cell)/(ng/ml) = 10002000.  
For NGF stimulation, set the initial concentration of NGF to 50 ng/ml * 4560
(molecule/cell)/(ng/ml) = 456000  
5a) To simulate LY294002 addition, set kPI3KRas and kPI3K to 0.  
5b) To simulate a dominant negative Rap1, set kRap1ToBRaf to 0.  
To simulate a dominant negative Ras, set kRasToRaf1 and kPI3KRas to 0.  

Almost all the data fit with this model by the authors are from Western blots.
Given the uncertainties in antibody effectiveness and other factors, one can't
a priori derive a conversion between the arbitrary units for a given set of
data and molecules per cell. So the authors used an adjustable "scale factor"
that converts between molecules per cell and Western blot units.

For the EGF stimulation data in figure 2a) the scale factor conversion is
1.414e-05 (U/mg)/(molecule/cell). For the NGF stimulation data in figure 2a)
it is 7.135e-06 (U/mg)/(molecule/cell).

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

