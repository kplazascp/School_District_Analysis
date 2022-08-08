# School_District_Analysis
In this analysis, we are using Jupyter Notebool to analyse two csv files that contain school and students data.
We are also going to verify the data, clean it, merge it and format it so that we can have a unified and clean dataset for further analysis.
We are going to deep dive into Thomas High School where ninth graders appear to have been altered.

## Results: 

- How is the district summary affected?
![District_Original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/Distrct_summary_original.PNG)
![District_Updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/Distrct_summary_updated.PNG)
The district summary is affected with a low percentage of decrease in Math score and the percentage passing in Math, reading and overall.

- How is the school summary affected?
This is where we can evidence the loss of score for Thomas High School after dropping the altered values, the overall passing percentage goes from 91% to 65%.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Both percentage of passing for Math and Reading, drop more than 20% for each one of them. For Math it went from 93% to 67% and for reading from 97% to 67%. 
![THS_Original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Original.PNG)
![THS_Updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Overall_updated.PNG)


### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
The data corresponding to Thomas High School is replaced with NaN values, for the rest of schools it remains the same.
![Math_original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Math_Scores_Original.PNG)
![Math_updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/Math_updated.PNG)
![Reading_original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Reading_Original.PNG)
![Reading_updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/Reading_updated.PNG)

- Scores by school spending
It doesn´t affect the school spending because the ninth-graders are not taken into account in this attribute (10-12 graders).
![spending_original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Original_Budget.PNG)
![spending_updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/School_spending_updated.PNG)

- Scores by school size and scores by school type
It occurs the same as the school spending and school type, it doesn´t affect the school spending because the ninth-graders are not taken into account in this attribute (10-12 graders).
![Size_original](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/THS_Size_Original.PNG)
![Size_updated](https://github.com/kplazascp/School_District_Analysis/blob/main/Resources/size_updated.PNG)



Summary: 
- Decrease in District Summary after changes in reading and math scores for ninth grade students at Thomas High Scool
- Decrease in Overall passing percentages for Thomas High School
- Decrease in passing Math and Reading in aproximately 20% each.
- Scores by school spending, school size and school type don´t vary because ninth grades are not taken into account, for further analysisis it would be very usefull to consider them and see the overall effect on these categories.
