# Impact of COVID-19 on grading distributions

The goal of this project is to investigate the influence of the COVID-19 pandemic on grade distributions for a university class spanning 6 semesters.

**DATA**<br /> 
Grades for a large, undergraduate intro level course over six semesters: Spring 2019 to Fall 2021. These semesters span from pre-pandemic (SP19 & FA19) to pandemic (SP20-FA21). Raw grade data (found in 'grade-data') has already been anonymized through the removal of identifying information and randomization of indices.

**QUESTIONS**<br /> 
Did the pandemic have an influence on grade distributions?
Design a machine learning model for the data. Which machine learning model is most effective? Which features are most predictive of final grade?

**APPROACH**<br /> 
We first load the data from each semester into dictionaries (each semester has a different number of students so dictionaries are easier to use than loading all the data into a single dataframe). We then remove missing data and plot the data.

**ANSWERS**<br /> 
(Did the pandemic have an influence on grade distributions?) - A: Yes, but only for SP20. The effect was short-lived, with grades rebounding by SP21.
(Design a machine learning model for the data. Which machine learning model is most effective? Which features are most predictive of final grade?) - A: The Random Forest Classifier and Polynomial Kernal SVM models perform similarly (r2 ranges from 80% to 85%). The "Assignments" feature was most predictive of final letter grade.

**CURRENT QUESTIONS**<br /> 
Did variance of each student's grade throughout a semester increase during pandemic (semester-on-semester)?
Obtain more data from other classes; which courses were most impacted? What features of the classes indicated how much grades were impacted?
