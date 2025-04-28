# Orthorubulavirus_HPIV
This repository contains the analyses described in the article.

## Data Summary
SupplementaryTable1.xlsx contains metadata and NCBI accession numbers for the genomes from western Washington State.

## Directory Structure and Content
### Within_Viral_Species_Analyses/
This folder includes:	
#### Maximum Likelihood trees constructed with IQ-TREE from complete genomes or HN gene sequences (from both complete and HN-only sequences). File extension .treefile
#### BEAST2 phylodynamic analyses from complete genomes, considering gene partition, or V/P and HN genes codon partitions. File extension of the trees .tre, and BEAST2 log files detailing parameter sampling during MCMC runs in .log files.
#### Annotation files (*.txt) for visualizing associated metadata (sample origin, date) alongside the trees.
#### HPIV-2_p-distance.xlsx: Pairwise p-distance estimates between genotypes calculated using MEGA X, used to validate HPIV-2 genotype classification.

### Within_Taxonomic_Family_Analyses/
This folder includes Phylogenetic trees based on amino acid alignments of viral proteins from representative species of the Paramyxoviridae family.
#### Alignments trimmed to remove regions with poor homology (see Trimmed_Alignment/).
#### Maximum Likelihood trees generated using IQ-TREE (see _rep1 to _rep3 folders). File extension .treefile
#### Bayesian inference trees generated using MrBayes (see mrbayes/ folder). File extension .tre
#### Annotation file (Tree_annotation.txt) allows integration of taxonomic metadata (genus, subfamily, species) into visualization tools.
