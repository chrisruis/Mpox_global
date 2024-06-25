# Mpox_global
Data used in "Global genomic surveillance of monkeypox virus"

## data
This directory contains data used in the manuscript. Note that due to data sharing agreements, sequence alignments do not contain sequences from GISAID.

### alignments
This directory contains sequence alignments excluding GISAID sequences. These alignments are:
* CladeI.fasta contains 96 high quality Clade I sequences. Note that sequences from the Kamituga area were obtained from https://github.com/inrb-labgenpath/Mpox_sequencing_Kamituga so do not have accession numbers
* CladeIIa.fasta contains 25 high quality Clade IIa sequences
* CladeIIb_A.fasta contains 87 high quality Clade IIb A lineages sequences
* lineage_B.1.fasta.gz contains 6424 high quality lineage B.1 sequences. This file has been compressed due to its large size

### beast
This directory contains Clade1_combined.log which is the combined log file from BEAST run on Clade I. Note that because this file has been combined from multiple runs with burnin removed, burnin does not need to be removed from this log file

### mutational_spectra
This directory contains mutational spectra for the major MPXV clades, calculated by MutTui (https://github.com/chrisruis/MutTui). Each of the clades has 3 files:
* unscaled_SBS_spectrum.csv contains the SBS mutation counts from MutTui
* SBS_spectrum.csv contains the SBS spectrum rescaled by genome composition
* SBS_spectrum.pdf contains a plot of the SBS spectrum rescaled by genome composition
