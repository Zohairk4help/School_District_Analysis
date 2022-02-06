# School_District_Analysis
The application of Jupyter Notebook to analyse on PyCity-schools' data by using Anaconda software in python environment(PythonData)



## **Overview of the school district analysis:**
I learnt how to use and apply the anaconda's Jupyter Notebook to import the data from local directory into the notebook. After that, I learnt and applied how to calculate and get the required/needed information from the data after making its dataframes. When the the neeeded data is successfully imported in the notebook as a dataframe, the table is then successfully exportred to the local directory. 

Hence, in this module, I observed and learnt how mathematics skills can be applied to determine the needed information for the school district. 

The analysis was done on the eleven schools:
Huang High School, Figueroa High School, Shelton High School, Hernandez High School, Griffin High School, Wilson High School, Cabrera High School, Bailey High School, Holden High School, Pena High School, Wright High School, Rodriguez High School, Johnson High School, Ford High School, and Thomas High School. 



## **The purpose of this analysis:**
The purpose is to see the effects on the overall-already-calculated-data after replacing the 9th grade-students-scores with 'NaN' as there was some fraudulant activity happemed in Thomas High school 9th grades. 

## **Results:**
---> The effect on the district summary dataframe: Average Math score is decreased by 0.1%; % passing Math is decreased by 0.2%; % passing reading scores is decreased by 0.3% and % passing of overall score is decreased by 0.1%. All in all, the range of percentage is decreased in the columns is very insignificant. 
<figure>
  <img src="Challenge-folder2-2-2022\district_summary_df_comparisons.png" width="450" height="250">
  <figcaption>Picture 1: comparisons of the dfs: District_summary_df.</figcaption>
</figure>
---> The effect on the Dataframe -- school summary: In the row of Thomas high school, there is insignificant increase/decrease in percentages in the following:

1. Average Math Score by 0.07% ↓
2. Average Reading Score by -0.05% ↑
3. % Passing Math by 0.09% ↓
4. % Passing Reading by 0.290% ↓
5. % Passing Overall by 0.318% ↓

<figure>
  <img src="Challenge-folder2-2-2022\per_school_summary_df_comparisons.png" width="450" height="250">
  <figcaption>Picture 2: comparisons of the per_school_summary_dfs.</figcaption>
</figure>

---> The replacement of the ninth graders’ math and reading scores have no affect Thomas High School’s performance relative to the other schools. The only obvious change is the 9th Grade students' scores are replaced with "NaN" in both of the Dataframes ("math_scores_by_grade" and "reading_scores_by_grade")

<figure>
  <img src="Challenge-folder2-2-2022\MATH_scores_by_grades_comparisons.png" width="100" height="100">
  <figcaption>Picture 3: comparisons of the math_scores_by_grade_dfs.</figcaption>
</figure>
 <figure>
  <img src="Challenge-folder2-2-2022\Reading_scores_by_grades_comparisons.png" width="100" height="100">
  <figcaption>Picture 4: comparisons of the reading_scores_by_grade_dfs.</figcaption>
</figure>

---> Similarly, Scores by school spending, school types and school size summary tables have no affect after changing the ninth grade students' scores with "Nan". 

 <figure>
  <img src="Challenge-folder2-2-2022\spending_summary_comparisons.png" width="100" height="100">
  <figcaption>Picture 5: comparisons of the spending_dfs.</figcaption>
</figure>


 <figure>
  <img src="Challenge-folder2-2-2022\size_summary.png" width="100" height="100">
  <figcaption>Picture 6: comparisons of the sizing_dfs.</figcaption>
</figure>

 <figure>
  <img src="Challenge-folder2-2-2022\type_summary_df_comparisons.png" width="100" height="100">
  <figcaption>Picture 7: comparisons of the type_summary_dfs.</figcaption>
</figure>

## **Summary:**

 After chaning the fraudulant 9th graders' scores to "NaN", overall the district summary dataframe shows insignificant % decrease. When comparing the challenge and modules' tables, the following changes are noticed:

1. Average Math score is decreased by 0.1%; 
2. % passing Math is decreased by 0.2%; 
3. % passing reading scores is decreased by 0.3% 
4. % passing of overall score is decreased by 0.1%.
