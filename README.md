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
3. Click **"Run"** or **"Enter + Ctrl"** to execute the full analysis and generate figures/tables.

## 3. R Session Information

The R version and package dependencies are shown at the end of `analysis.Rmd` via `sessionInfo()`.

## 4. Notes

- All file paths are relative. No hard-coded local paths are used.  
- External files such as `NHANES mortality linkages` must be requested separately from the CDC.
- However, given the large size of the NHANES database, it may be necessary to download datasets to a local hard drive for analysis as needed.

## 5. Results of sessionInfo()
R version 4.4.2 (2024-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Matrix products: default


locale:
[1] LC_COLLATE=Chinese (Simplified)_China.utf8  LC_CTYPE=Chinese (Simplified)_China.utf8    LC_MONETARY=Chinese (Simplified)_China.utf8
[4] LC_NUMERIC=C                                LC_TIME=Chinese (Simplified)_China.utf8    

time zone: Asia/Shanghai
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] here_1.0.1

loaded via a namespace (and not attached):
[1] compiler_4.4.2    rprojroot_2.0.4   tools_4.4.2       rstudioapi_0.17.1
