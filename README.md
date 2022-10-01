# School_District_Analysis

## Objective
The objective of this analysis is to clean up and analyse the new_full_student_data.csv and present the findings to the school board

## Method
The data was first cleaned, any rows with missing data were dropped so as not to skew the analysis. The data types were checked to ensure they were correct and those that were not were changed. The data was analyed with summary statistics and then grouped to provide further analysis.

# Summary
Below is the first 5 lines in the dataset:

<img width="660" alt="student_df_head" src="https://user-images.githubusercontent.com/112291888/193430854-8fa562f0-0bfa-4423-9a16-8809d34b6b57.png">

After cleaning the data and changing the necessary data types a summary statistics analysis was preformed to provide some insights to the dataset as a whole, the produced table is below

<img width="466" alt="student_df_sum_stats" src="https://user-images.githubusercontent.com/112291888/193430933-bf5282ec-1460-49ba-bde8-db2dfabb1ead.png">

Continuing with the analysis the average reading and math score were determined for selected grades

To finish the analysis, the data was grouped in several different ways; first, to show the average math scores in the different school types, Charter and Public, for each grade. And then grouped again to list the total number of students in each school.

<img width="206" alt="student_df_math_score" src="https://user-images.githubusercontent.com/112291888/193431043-84e13b56-65de-4045-b007-74e6349e1ea2.png">

<img width="235" alt="student_df_school_count" src="https://user-images.githubusercontent.com/112291888/193431054-8c12da6a-ecf6-4777-b9ec-1b97d8de0676.png">
