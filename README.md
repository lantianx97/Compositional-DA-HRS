# Compositional-DA-HRS
Three data sets from the HRS were used:  

(1) The flow cytometry data can be found at: https://hrsdata.isr.umich.edu/data-products/vbs-2016-flow-cytometry  

(2) The RAND longitudinal data (randhrs1992_2018v2) can be found at: https://hrsdata.isr.umich.edu/data-products/rand-hrs-archived-data-products  

(3) The 2016 VBS data can be found at: https://hrsdata.isr.umich.edu/data-products/2016-venous-blood-study-vbs


The data processing.Rmd contains code used to:

(1) Re-compute the percentage measures of T and B subset cells based on the proposed tree structure.  

(2) Merge cell data with socio-demographic information and health outcomes across three different data sets.

The data analysis.Rmd contains code used to perform step-wise RDA, network analysis, and linear penalized log-contrast regression.
