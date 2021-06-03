# Matplotlib-Challenge

## Background

* Used pandas to merge mouse data and study results. 

* Performed data cleaning by removing duplicate data points. 

* Utilized groupby function to aggregate statistical summary for the different drug regimens.


## Images/Analysis 

## Observations 

1) There is a positive correlation (correlation coefficient of 0.84) between mouse weight and tumor volume within the Capomulin treatment cohort. This is confirmed by the regression analysis completed below.

2) Final tumor volumes below 36.83290495 (mm3) were identified as possible outliers within the Infubinol cohort. Mouse ID c326 had a final tumor volume of 36.321346 (mm3) making it a potential outlier within the Infubinol cohort and possibly skewing the effectivness of Infubinol's ability to minimize tumor volume.

3) Occasionally fluctuating, the tumor volume of mouse b128 (arbitrarily selected) appears to have dramatically decreased from 45(mm3) at timepoint 0 days to 38(mm3) at timepoint 35 days.
