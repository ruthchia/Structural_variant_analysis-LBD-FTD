This directory contains jupyter notebook in ipynb and html format that contain scripts/code used in the study.

**NIH_LBD_FTD_SVs_for_sharing.ipynb/html** main contents:
1. Creation of vcf files for the high-quality subset of structural variant data
2. Descriptive statistic generation
3. Short-read structural variant validation versus Nanopore long-read sequencing data
4. TPCN1 deletion replication assosiaction analysis
5. Neurodegenerative disease gene rare-variant analysis
6. Original shiny app code (for up-to-date code see shinyapp directory of this repository)
7. Plotting
8. BigBed file creation

**KK_edited_2022-07-04_DataPrep_FTD.LBD_merge.SV-1perc-fdr_and_SNV_forSharing_Github** main contents:
1. Post-GATK-SV data filtering
2. Data merging with SNV data
3. PC generation
4. step() to determine for which covariates adjustment is needed in association analyses

**KK_edits_2022-07-05_Readme.SV.GLM.{LBD/FTD}.4Kcontrols.merged.SNVindels_SV-1perc-fdr_updatedFilters_forSharing_Github** main contents:
1. Running GLM with PLINK2 to perform genome-wide association analyses
2. Post-hoc filtering of e.g. centromeric, telomeric, VDJ regions and sites with inoptimal quality.
