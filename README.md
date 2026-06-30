# healthy_start_power_analysis

This directory contains scripts for Healthy Start preliminary analysis and power analysis for Evaniya's AHA fellowship application

- data : directory of files 
  - LE8 biological_health factors score : directory of files for LE8 factor scoring
  - pathway_gene_lists : directory of gene lists for KEGG pathways
  - PIDS : directory of PIDs lists, for helping define subsets of interest
  
- finding_n_probes_for_power_analysis.Qmd : this script is for finding the number of probes for Aim 1 based on the genes from the pathway(s) of interest
  - healthy_start_Ms_filtered_to_probes_for_genes_of_interest.rds : this is a subset of our healthy start methylation matrix for the probes of interest

- healthy_start_webpower_analysis.Qmd : this script calculated power for Aims 1 through 3
  - healthy_start_webpower_analysis.docx : word doc output for power analysis

- LE8_calculations_and_preliminary_analysis.Qmd : this script we calculate LE8 using the information available. This script also contains some simple preliminary analysis for the defined Aims and hypotheses.
  - table1_LE8.pdf : one of the tables for the analysis
  - LE8_calculations_and_preliminary_analysis.html : html output for this script which contains many of the results and tables
  
