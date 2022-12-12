This directory contains BigBed files with what the high-quality structural variant data can be visualized in e.g. Ensembl and UCSC genome browsers as custom tracks.

# Background

This folder contains four bigBed files that contain information of structural variants in Lewy body dementia cases, LBD controls, frontotemporal dementia/amyotrophic lateral sclerosis cases and FTD/ALS controls. LBD and FTD/ALS control samples are largely overlapping.

Structural variants and samples included are of the filtered, high-quality subset. Tracks can only be used in **hg38/GRCh38**

# Usage in Ensembl genome browser
BigBed tracks can be used in Ensembl location tab (location of your choice) by going Add/Remove Tracks > Personal Data tab > Add name of your choice paste file URL of choice and add file type bigBed

LBD cases: https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/LBD_cases_analyzed.bb?raw=true
LBD controls: https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/LBD_controls_analyzed.bb?raw=true
FTD/ALS cases: https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/FTD_cases_analyzed.bb?raw=true
FTD/ALS controls: https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/FTD_controls_analyzed.bb?raw=true

# Usage in UCSC genome browser
BigBed tracks can be used in UCSC genome browser in My Data > Custom tracks and pasting the line(s) of choice to URL box (starting from track name and ending to type=bigBed)

LBD cases:  
track name="LBD cases" itemRgb=On db=hg38 visibility=3 bigDataUrl=https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/LBD_cases_analyzed.bb?raw=true type=bigBed

LBD controls:  
track name="LBD controls" itemRgb=On db=hg38 visibility=3 bigDataUrl=https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/LBD_controls_analyzed.bb?raw=true type=bigBed

FTD/ALS cases:  
track name="FTD cases" itemRgb=On db=hg38 visibility=3 bigDataUrl=https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/FTD_cases_analyzed.bb?raw=true type=bigBed

FTD/ALS controls:  
track name="FTD controls" itemRgb=On db=hg38 visibility=3 bigDataUrl=https://github.com/ruthchia/Structural_variant_analysis-LBD-FTD/blob/main/BigBed_files/FTD_controls_analyzed.bb?raw=true type=bigBed
