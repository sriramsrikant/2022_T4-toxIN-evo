# 2022_T4-toxIN-evo
This is the code-base used in the analysis of the T4 experimental evolution to overcome toxIN. Submitted to support manuscript being prepared.

Code is maintained in Jupyter notebooks written in Python using the listed package dependencies. Work done in the lab of Dr Michael Laub, MIT.

## Contents
1. data/coverage_maps - Raw fold-coverage data calculated from bwa assembly of illumina reads to reference genomes in provided python notebooks. Fold-coverage is plotted in Figures 1D, S1C, 4D, 5A, S5B, 6C.
2. data/plot_data - Raw data used of plate reader experiments of phage infecting growing bacteria used to plot graphs of Figures 2C, 3C, S3C provided in Excel file. Raw data used to generate heatmaps of evolving phage populations (Figure 4B) and ability to infect alternate hosts (Figure 6B) provided in separate csv files.
3. data/ref_genomes - Reference genomes of T4 ancestor used in evolution experiment and T4(bgt-mutant) used to generate tifA disruptions. Illumina reads were aligned to NCBI reference, and a new reference genome was generated. Fully annotated genome provided as genbank files.
