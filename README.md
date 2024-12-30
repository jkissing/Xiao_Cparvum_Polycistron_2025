# Xiao_Cparvum_Polycistron_2025
Code related to the Xiao et al 2025 C. parvum polycistron paper


## Codes and Scripts used for C. parvum polycistron manuscript

Included are all codes used for computation analysis in the polycistron manuscript.




### Shell Scripts

splice_leader_discovery: Small RNAseq based splice-leader discovery

atac_meme_run: used for processing and analyzing ATAC-seq

illumina_trimming: trim_galore based trimming for single or paired end illumna reads

long_read_process: Long-read RNAseq processing for both PacBio Iso-seq and Oxford Nanopore Direct RNA-seq

tama_processing: TAMA transcript modeling using long-read RNA-seq

short_read_rnaseq_process: Illumina RNAseq processing

long_read_abundance: Used to generate read abundance per annoated transcript models

run_sqanti3: SQANTI3 quality report for long-read RNA-seq data

polya_analysis: Direct RNA-seq based poly-A tail length analysis

start_stop_codon_sequence_extract: Analaysis of Kozak sequence and polyadenylation signal 

peptide_analysis: Analysis of peptide mapping and enrichment


### Python Scripts

polycis_finder: Taking TAMA discovered and SQANTI3 processed transcript models and apply denovo polycistron identification

polycis_chi_square_distribution and polycis_autocorrelation: Analysis for whether polycistrons 

codon_analysis: Scripts used for condon usage


### R Scriots

polya_R: R scripts used for downstream visulizing and analyzing of poly-A tail length

single_cell_analysis: All scripts used for analyzing publically available Cparvum single cell atalas

