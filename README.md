# iHealthChallenge

This project is to analyze blood pressure and blood glucose data organized by time stamp. 

Below are the overview of two datasets:

| **Name**                                 | **Alias**      | **Description**                                              | **Level** | **Column  (listed selectively)**                             |
| ---------------------------------------- | -------------- | ------------------------------------------------------------ | --------- | ------------------------------------------------------------ |
| Health_Sample  dataset_SBP by month.xlsx | Sample  Data   | average systolic BP readings of each patient with a timestamp | Monthly   | #memberId;   #month;   #systolic_mmHg                        |
| iHealth Time Series - v1 .xlsx           | Original  Data | blood pressure and blood  glucose readings organized by time stamp | Daily     | #EPR  ID; #datetime_utc;  #age_range;  #Gender;  #arrhythmic;  #systolic BP_mmHg;  #diastolic BP_mmHg |

We've had some implications related to patients' BP status patterns and their vital monitoring activity. More  observations with longer time period are required for further analysis.

For full code for analysis, please refer to: solution.ipynb.

For detailed analsis report, please refer to iHealth Data Challenge.pptx.