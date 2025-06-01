# Reproducible Analysis: SIRI and Mortality in RA Patients (NHANES 1999–2018)

This repository provides R code and documentation for reproducing the analysis presented in the manuscript:  
"Systemic Inflammation Response Index and Long-Term Mortality in Rheumatoid Arthritis: A NHANES-Based Cohort Study"

## 1. Data Access

- NHANES data portal: https://wwwn.cdc.gov/nchs/nhanes/Default.aspx  
- NHANES-NDI linked mortality data: https://www.cdc.gov/nchs/data-linkage/mortality-public.htm  
- This analysis uses data from the 1999–2018 cycles.

Please download the necessary datasets and place them in the `/data` folder.

## 2. How to Run

1. Open `analysis.Rmd` in RStudio.  
2. Ensure all required packages are installed.  
3. Click **"Knit"** to execute the full analysis and generate figures/tables.

## 3. R Session Information

The R version and package dependencies are shown at the end of `analysis.Rmd` via `sessionInfo()`.

## 4. Notes

- All file paths are relative. No hard-coded local paths are used.  
- External files such as `NHANES mortality linkages` must be requested separately from the CDC.
