# Matplotlib-Challenge

## Datasets 

[Mouse Data](/data/Mouse_MetaData.csv)

[Study Results](/data/Study_results.csv)

## Background

* Analyzing tumor volume of mice after undergoing drug regimens. 

* Used pandas to merge mouse data and study results. Performed data cleaning by removing duplicate data points. Utilized groupby function to aggregate statistical summary for the different drug regimens.


<img src="/Images/DataMerge.PNG" alt="My cool logo"/>



## Images/Analysis 

### Total measurements taken by drug regimen: 

<img src="/Images/TotalMeasurementsTaken.PNG" alt="My cool logo"/>

### Pie Chart showing distribution of mice by gender: 

<img src="/Images/Distribution by Gender.PNG" alt="My cool logo"/>

### Box and whisker plot to show outliers within the dataset. 

<img src="/Images/BoxPlotFinalTumorVolume.PNG" alt="My cool logo"/>

### Tumor volume of randomly selected Mouse b128

<img src="/Images/Capomulin Mouse B128.PNG" alt="My cool logo"/>

### Used a scatter plot to show distribution of dataset. Used a red line to demonstrate the simple regression line.


<img src="/Images/Correlation_Regression.PNG" alt="My cool logo"/>








## Observations 

1) There is a positive correlation (correlation coefficient of 0.84) between mouse weight and tumor volume within the Capomulin treatment cohort. This is confirmed by the regression analysis completed below.

2) Final tumor volumes below 36.83290495 (mm3) were identified as possible outliers within the Infubinol cohort. Mouse ID c326 had a final tumor volume of 36.321346 (mm3) making it a potential outlier within the Infubinol cohort and possibly skewing the effectivness of Infubinol's ability to minimize tumor volume.

3) Occasionally fluctuating, the tumor volume of mouse b128 (arbitrarily selected) appears to have dramatically decreased from 45(mm3) at timepoint 0 days to 38(mm3) at timepoint 35 days.
