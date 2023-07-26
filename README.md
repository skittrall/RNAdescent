RNAdescent

A package to find highly conserved regions in alignments of RNA sequences, by casting the problem as one of finding unusually large descents in a random walk.


INSTALLATION
The code is supplied as a Mathematica notebook, and just the notebook can be downloaded and run in interactive mode on a machine with a Mathematica installation.  The code was originally written in Mathematica 12.  The notebook contains examples that can be uncommented and run, or information on codon usage from an alignment can be imported.


CITATION
If you use this code in your work, please cite:
1. Jordan P. Skittrall, Nerea Irigoyen, Ian Brierley, Julia R. Gog.  ``A novel approach to finding conserved features in low-variability gene alignments characterises RNA motifs in SARS-CoV and SARS-CoV-2''.  Scientific Reports (2023) 13:12079. doi:10.1038/s41598-023-39207-1
and
2. Julia R. Gog, Andrew M.L. Lever, Jordan P. Skittrall.  ``A new method for detecting signal regions in ordered sequences of real numbers, and application to viral genomic data''.  PLoS ONE (2018) 13(4):e0195763. doi:10.1371/journal.pone.0195763

If you use the code that handles gaps in alignments (enabled by default, but not necessary/used if your alignment does not contain any gaps), please also cite:
3. Jordan P. Skittrall, Carin K. Ingemarsdotter, Julia R. Gog, Andrew M.L. Lever.  ``A scale-free analysis of the HIV-1 genome demonstrates multiple conserved regions of structural and functional importance''.  PLoS Computational Biology (2019) 15(9):e1007345. doi:10.1371/journal.pcbi.1007345


BUG REPORTS/QUERIES
Bug reports may be sent to jps55@cam.ac.uk.


v1.1 CHANGES
-Updated citation information in Mathematica notebook
-Bugfix to the function that collates significant regions, to stop highlights of regions found after a check for interfering regions if the region found on the second pass does not coincide with the region found on the first pass.
