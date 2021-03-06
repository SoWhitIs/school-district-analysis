# _What Do The Scores Say?_ || PyCity School District Analysis 

## Overview of Project

On task with assisting the Chief Data Scientist of the PyCity School District. Analysis consisted of review and "clean-up" of standardized test score data from local high schools, by which findings would later give insights as to strategic planning of future budgets and priorities by the school board and superintendent.

Upon completion of initial analysis, it was brought to attention that file: students_complete.csv, a source for said analysis, containing Math and Reading testing results from Thomas High School ninth graders, respectively, had been altered.

While, the extent of the alteration is unknown, to uphold the state-testing standards, the _ "remedy"_ was to re-do the analysis excluding the former Thomas High School ninth grade test results data (subsequently using the _only_ data from tenth to twelfth grade). 

## Resources

* Data Source (s): students_complete.csv, schools_complete.csv

* Software: Python 3.7.6 64-bit | Python Libaries:Pandas, Numpy | Jupyter Notebook** | Anaconda
	
	* Data Access: Workaround, [Project Jupyter: jupyter nbviewer](https://nbviewer.jupyter.org/), a Jupyter Notebook renderer **
		* Some DataFrames on PyCitySchools_Challenge file may not present intact. Specifically, data is not aligned or showcased under its appropriate column in GitHub appearing “jumbled up”. Please, use provided workaround.



<p align="center">
  <i><b>GitHub: "Jumbled" Data
  </b></i> 
 </p>


<p align="center">
  <img src="additional resources/data_combined_in_github.png" />
</p>

   
<p align="center">
  <i><b>Project Jupyter: nbnbviewer Homepage</b></i> 
 </p>
<p align="center">
  <img src="additional resources/nbviewer_ jupyter.png" </p>
	
	
***
***	

## Results
### What has been impacted? 

Aforementioned, the basis of re-analysis was due to inaccuracies in reported ninth grade Math and Reading standardized scores from Thomas High School. Though replacing this data with NaNs (Not a Number), the analysis consisted of the same general calculations, methodology, and overall objectives with additions or edits in code to address the data set change.

<p align="center">
  <i><b> ---- District Snapshot ----</b></i> 
 </p>

 * Initial Analysis Dataset: 39,170 students, 15 Schools (Varied Types: District, Charter)
 * New Analysis Dataset: 38,709 Students, 15 Schools (Varied Types: District, Charter)
	* Percentage Change (Difference in Size) of 1.17692111% or 1.2%
*   Schools: 15 (Varied Types: District, Charter)
***
 ### District Summary, Result: _Minor Effect_

*   Given that difference between the intial and new dataset was just slighty over 1% (461 students) there was little change in overall results to the District Summary, as seen in the images below:
<p align="center">
  <i><b>District Summary A: Intial Anaylsis </b></i> 
 </p>

<p align="center">
  <img src="additional resources/district_summary_a.png"/>


<p align="center">
  <i><b>District Summary A: Intial Anaylsis_Unrounded/Formatted</b></i> 

<p align="center">
  <img src="additional resources/district_summary_a_unrounded.png"/>
<p align="center">
  <i><b>District Summary B: Second Anaylsis </b></i> 
 </p>

<p align="center">
  <img src="additional resources/district_summary_b.png"/>
</p>

***

### School Summary,  Result: _Greater Effect_

*   Unlike the results for the District Summary,where data was seen as whole, when we take a look at Thomas High School on a per school level, the absence of the ninth grade testing scores, were rather noticeable. We see significant jumps in _Math_, _Reading_ and _Overall_ passing percentages, respectively, seeing  about a **30%** boost as as result in calculating this new dataset, as seen in the images below. 

<p align="center">
  <i><b>School Summary: Thomas High School</b></i> 
 </p>

<p align="center">
  <img src="additional resources/intial_analysis_thomas_high_school_summary_a.png"/>
</p>

<p align="center">
  <i><b>School Summary: Thomas High School without Nine Grade Test Scores (Inclusive of 10th-12th Grades, only)</b></i> 
 </p>

<p align="center">
  <img src="additional resources/second_analysis_thomas_high_school_summary_b.png"/>
</p>

***

 ### Replacing Ninth-Grade Scores _Affects_

It would appear after several "runs" of the code, replacing the ninth-grade scores NANs presented no extreme bearing in the overall outcomes after an in-depth and exhaustive comparison by school size, type, math and reading scores by grade. 


Thomas High School appears to ***still*** remain amgonst the "Top 5 High Performing Schools".


## Summary
By replacing the scoring data with NaN, all "usable" data was kept in tact, such as school name, type, student name, etc. however, this method could sometimes net false positives as the results or effects are may or may not be as noticebale. 

Given that, it is possible because of the smaller sample size (haven been removed or replaced), ***only*** 1% of the inital student count, any difference would be primarily noticed on a per school breakdown. 

Any change in student population size would directly effect the overall passing outcomes of the group as whole. 

---
 #### Author
 _Whitney D. Gardner_
