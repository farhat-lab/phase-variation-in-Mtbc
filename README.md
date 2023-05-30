# phase-variation-in-Mtbc
This repository contains the Jupyter Notebooks used in data processing and analysis for the article "Phase variation as a major mechanism of adaptation in Mycobacterium tuberculosis complex" (Vargas et al. 2023, PNAS in-press).

Notebooks were run in order from top to bottom as listed below. Most code was written in Python 2 (with some in Python 3) and running code within these notebooks requires installing the necessary python packages, bioinformatics pipelines & changing the directory paths within the notebooks.

Note: If a notebook doesn't render on GitHub, you can view it by pasting the GitHub hyperlink to it here https://nbviewer.jupyter.org/ 

__Notebooks__

1 genotypes wrangling and processing/
* (A) PB_IL_Empirical_Base_Recall_score_positions_to_drop
* (B) Scraping_WGS_DB_for_Genotypes_Matrix
* (C) Lineage_and_Sublineage_assignment_MGE_filtering
* (D) Cluster_isolates_into_groups_by_Lineage_and_Sublineage_assignments
* (E) Genotypes Matrix_to_pairwise_SNP_distance_Matrix_convert
* (F) Scraping_WGS_DB_for_Genotypes_Matrix_indels
* (G) Genotypes Matrix_to_pairwise_INDEL_distance_Matrix_convert

2 phylogeny and ancestral reconstructions/
* (A) Phylogeny Construction for Global Lineages
* (B) TopDis Homoplasy SNP Collection Pipeline
* (C) TopDis Homoplasy INDEL Collection Pipeline
* (D) SNPPar_ancestral_sequence_reconstruction

3 SNP and INDEL mutation analyses and visualizations/
* (A) SNP Homoplasy count from SNPPar and TopDis
* (B) INDEL Homoplasy count from TopDis 2
* (C) INDEL Homoplasy Analysis (HT, SSR, non-HT-SSR INDELs)
* (D) SNP and INDEL Homoplasy Analysis Manhattan Plots
* (E) SNP and INDEL Recency Ratio Plots
* (F) SNP and INDEL mutational density calculations for genes
* (G) t-SNE_on_pairwise_SNP_distance_Matrix and by-lineage plot
* (H) t-SNE visuals by tree group, glpK, upstream espA-espK
* (I) t-SNE visuals separate by tree group-within-lineage diversity

4 null distribution simulations/
* (A) Null Distribution Simulations for SNVs across genome and frameshifts in HTs
* (B) Null Distribution Simulations for SNV mutational density per gene

5 repetitive region analyses and simulations/
* (A) check EBPR for top HT and SSR hits
* (B) check EBPR for top SNV hits
* (C) repetitive region sims - map HT and SSR sequences between H37Rv and assemblies
* (D) repetitive region sims - alter assembly sequences and simulate reads
* (E) repetitive region sims - call variants from simulated reads
* (F) repetitive region sims - analyze variants from simulated reads

6 PNAS rebuttal tasks/
* (A) check complete PacBio sequences for HT upstream espA
* (B) check whether multi-allelic INDELs affect HT Hs scores
* (C) geographical distribution of sample
