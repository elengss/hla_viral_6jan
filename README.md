# hla_viral_6jan

This documents the HLA Viral AA analysis
The code should be run in the following order
1. Prepare viral_AA_phenotype_and_covariates - this prepares the files for plink input
2. Do_plink - these are the plink commands I used
3. Redo_significant_amino_acid_association_in_R - this selects out the significant (based on q value) AA HLA pairs and repeats the analysis in all 4 subgroups in R - EUR, SA, GT3, GT1
4. Plots - this is code for forest plot as well as to prepare file for input into locuszoom server
5. Conditional_analysis - this conditions on the most significant HLA for secondary signals
6. Get_sequence_around_significant_AA - this extracts the reference sequence around significant AA for input into IEDB search for epitope and immune activity

There are some other code files in there for analysis that has not been completed
