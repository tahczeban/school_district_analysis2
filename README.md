# School_District_Analysis_Challenge
module 4 school district analysis
PyCitySchools/Panda

**Resources:**
-Anaconda(1.7.2)
-Conda(4.10.3) 
-Python(3.8.8)
-Jupyter(4.7.1, notebook 6.3.0)
-Pandas
-Numpy

**OVERVIEW OF SCHOOL DISTRICT ANALYSIS:**

  The purpose of this analysis was to perpare a comparison of district school data for Maria, the Chief Data Scientist, to easily peruse for insights regarding the performance trends at school district levels. Math and reading scores were manipulated and analyzed for the Board presentation. Upon review, it was determined that the ninth grade class data from Thomas High School revealed various sustpect anomolies. For a comparison the ninth grade data was removed as NaN and the analysis was performed again. This compiled analysis utilized the following methods for data retreival:
  1) reading raw CSV files and convert to Pandas DF
  2) Find missing values and handle
  3) inspect and fix student names
  4) inspect and clean data
  5) merge data
  6) retreive # schools, students and budget, scores and averages
  7) create DF format and reorder columns, create visualizations for ease of presentation/comprehension
  8) Generate School Summary (set index, obtain data)
  9) Find top/bottom performing schools
  10) group schools by spending per student, by school size and by school type
  
**RESULTS:** (please refer to PYCitySchools.docx for full results with charts, as this part was completed on word due to GitHub issues 11/27/21)

_District Summary_
There is not much of a change in data between the two analyses across the 15 schools in the district in terms of math, reading and overall scores for ninth grade Thomas High School(THS) students. The test scores did not change significantly when removing 491 out of 39,170 students.

_School Summary_
A comparison of the original data and the grade nine THS data, a significant decrease in  percent math (93.27%-66.91%), reading (97.30-66.66%) and overall passing (90.94-65.07%). 

_Effects of 9th grade NaNs for THS vs other schools_
The top five and top bottom performing schools revealed that THS was second in the top and became 8th in rank out of 15 HS for the comparison analysis.

_Effects on math and reading scores by grade_
The ninth grade scores at THS are displayed as NaN. There was not a great difference between the comparison criteria when analysing the math and reading scores by grade.

_Effects on scores by school spending_
The spending range comparison revealed that there was not a big differential between the average math and reading scores for the spending range of $630-644 per student spending.

_Effects on scores by school size_
The school size was compared and it showed that the average math and reading scores did not change much, once the THS ninth grade scores were removed. Medium sized schools fared better than the small or large schools.

_Effects on scores by school type_
In terms of school type there was nominal change in scores by school type; however,  Charter schools performance was far better than the district schools over all



**SUMMARY**
1. The following four changes were observed in the updated school analysis after reading/math scores for 9th graders at THS     were replaced with NaN’s
2. Test scores did not change significantly when removing the THS ninth graders test scores
3. THS demonstrated a significant decline in math, reading and overall passing rates when with 9th grade NaN implementation             (91-65%)
3. THS’s rank decreased from 2nd to 8th out of 15 district HS
4. Charter school passing percentages declines; however, remained higher than district overall.



**REFERENCES**
 -BSC
 -Google
 -GitHub
 -StackOverflow
