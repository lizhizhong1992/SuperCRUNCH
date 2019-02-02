![SuperCrunch Logo](https://github.com/dportik/SuperCRUNCH/blob/master/docs/SuperCRUNCH_Logo.png)

---------------

## Overview

**SuperCRUNCH** is a python toolkit for extracting, filtering, and manipulating nucleotide data. **SuperCRUNCH** uses sequence data downloaded directly from NCBI as a starting point, rather than retrieving sequences through an intermediate step (GenBank database releases and/or NCBI Taxonomy). Sequence sets are created based on designated lists of taxa and loci, offering fine-control for targeted searches. **SuperCRUNCH** also includes refined methods for orthology detection and sequence selection. By offering the option to select representative sequences for taxa or retain all filtered sequences, **SuperCRUNCH** can be used to generate interspecific supermatrix datasets (one sequence per taxon per locus) or population-level datasets (multiple sequences per taxon per locus). It can also be used to assemble phylogenomic datasets with thousands of loci. **SuperCRUNCH** is modular in design, is intended to be transparent, objective and repeatable, and offers flexibility across all major steps in constructing phylogenetic datasets. 

## Version

The current release of **SuperCRUNCH** is v1.0.

## Installation

**SuperCRUNCH** SuperCRUNCH consists of a set of modules written in python (2.7) that function as stand-alone command-line scripts. These modules are available in the [supercrunch-scripts](https://github.com/dportik/SuperCRUNCH/tree/master/supercrunch-scripts) folder. They can be downloaded and executed independently without the need to install **SuperCRUNCH** as a PYTHON package or library, making them easy to use and edit. The scripts function independently, and do not require being contained or used from the same directory. There are several external dependencies that should be installed prior to use of **SuperCRUNCH**, including:

+ [Biopython](https://biopython.org/)
+ [NCBI-BLAST+](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=Download)
+ [CD-HIT-EST](http://weizhongli-lab.org/cd-hit/)
+ [MAFFT](https://mafft.cbrc.jp/alignment/software/)
+ [Muscle](https://www.drive5.com/muscle/)
+ [Clustal-O](http://www.clustal.org/omega/)
+ [MACSE](https://bioweb.supagro.inra.fr/macse/)
+ [trimAl](http://trimal.cgenomics.org/)

Helpful installation instructions for these dependencies can be found on the wiki installation page [here](https://github.com/dportik/SuperCRUNCH/wiki/Installation-Instructions).


## Complete Instructions for Analyses

An overview of the components of **SuperCRUNCH** can be found on the wiki overview page [here](https://github.com/dportik/SuperCRUNCH/wiki/Overview). This page outlines all major topics and navigates to detailed instructions for all major topics, including usage for all modules, proposed workflows, and common issues.

## Tutorials and Examples

Several example analyses are available on the [**SuperCRUNCH** project page](https://osf.io/bpt94/) on the Open Science Framework, including all input files, output files, and complete wiki tutorials. These analyses include:

+ **Iguania Supermatrix:** SuperCRUNCH analysis of Iguania using sequence data downloaded directly from NCBI. Direct link [here](https://osf.io/vsu5k/).
+ **UCE Supermatrix:** SuperCRUNCH analysis of UCE loci available for the frog genus *Kaloula*, using sequence data downloaded directly from NCBI. Direct link [here](https://osf.io/5rey2/).
+ **Population Dataset (*Uma*):** SuperCRUNCH analysis to retrieve population-level data for the lizard genus *Uma*, using sequence data downloaded directly from NCBI. Direct link [here](https://osf.io/49wz3/).
+ **Population Dataset (*Callisaurus*):** SuperCRUNCH analysis to retrieve population-level data for the lizard genus *Callisaurus*, using sequence data. Direct link [here](https://osf.io/6bwhf/).

Several example files are also provided in the [data folder](https://github.com/dportik/SuperCRUNCH/tree/master/data). These include locus search terms files and reference sequence sets. 

## Citation

**SuperCRUNCH** is currently described in a pre-print available on BioRxiv:

+ Portik, D.M., and J.J. Wiens. (2019) SuperCRUNCH: A toolkit for creating and manipulating supermatrices and other large phylogenetic datasets. BioRxiv, https://doi.org/10.1101/538728.

SuperCRUNCH is also in peer-review, and we hope to have a formal publication soon. 

If you use **SuperCRUNCH** for your research, please cite the above BioRxiv publication (for now).

## License

GNU Lesser General Public License v3.0

## Contact

SuperCRUNCH is written and maintained by Daniel Portik (daniel.portik@gmail.com)
