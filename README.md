# _What **do** the scores say?_ || PyCity School District Analysis 

## Overview of Project

On task with assisting the Chief Data Scientist of the PyCity School District. Analysis consisted of review "clean-up" of standardized test score data from local high schools, by which findings would later give insights as to strategic planning of future budgets 
and priorities by the school board and superintendent.

Upon completion of initial analysis, it was brought to attention that file: students_complete.csv, a source for said analysis, containing Math and Reading testing results from Thomas High School ninth graders, respectively, had been altered.

 While, the extent of the alteration is unknown, to uphold the state-testing standards the _ "remedy"_ was to re-do the analysis excluding the former Thomas High School ninth grade test results data (subsequently using the _only_ data from tenth to twelfth grade). 

### Resources
•	Data Source (s): students_complete.csv, schools_complete.csv

•	Software: Python 3.7.6 64-bit, Pandas, Jupyter Notebook, Anaconda *

•	Data Access: Workaround, [Project Jupyter: jupyter nbviewer](nbviewer.jupyter.org), a Jupytner Notebook renderer **

<p align="center">
  <i><b>Some DataFrames on _PyCitySchools_Challenge file may not present intact. Specifically, data is not aligned or showcased under its appropriate column in GitHub appearing “jumbled up”. *
  </b></i> 
 </p>


<p align="center">
  <i><b>GitHub: "Jumbled" Data
  </b></i> 
 </p>


<p align="center">
  <img src="additional resources/data_combined_in_github.png" />
</p>

<p align="center">
  <i><b> Please use site: Project Jupyter: jupyter nbviewer](nbviewer.jupyter.org) as work around. Proceed to add source link to in search field.**
  </b></i> 
 </p>
   

<p align="center">
  <i><b>Project Jupyter: nbnbviewer jupyter Homepage</b></i> 
 </p>


<p align="center">
  <img src="additional resources/nbviewer_ jupyter .png"/>
</p>


## Results
### What has been impacted? 

Aforementioned, the basis of re-analysis was due to inaccuracies in reported ninth grade Math and Reading standardized scores from Thomas High School. Though replacing this data with NaNs (Not a Number), the analysis consisted of the same general calculations, methodology, and overall objectives with additions or edits in code to address the data set change.

<p align="center">
  <i><b> ---- District Snapshot ----</b></i> 
 </p>

 * Initial Analysis Dataset: 39,170 students, 15 Schools (Varied Types: Districts, Charter)
 * New Analysis Dataset: 38,709 Students, 15 Schools (Varied Types: Districts, Charter)
	* Percentage Change (Difference in Size) of 1.17692111% or 1.2%
*   Schools: 15 (Varied Types: Districts, Charter)
***
 ### District Summary, Result: _Minor Effect_

*   Given that difference between the intial and new dataset was just slighty over 1% (461 students) there was little to no change overall results to the District Summary, as seen in the images below:
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

### School Summary,  Result: _Big Effect_

*   Unlike the results for the District Summary,where data was seen as whole,  when we take a look at Thomas High School on a per school level, the absence of the ninth grade testing scores, were rather noticeable. We see significant jumps in _Math_, _Reading_ and _Overall_ passing percentages, respectively, seeing  about a **30%** boost as as result in calculating this new dataset, as seen in the images below. 

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

 ### Replacing Ninth-Grade Scores

The below showcases the 
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary
By Replacing the scoring data settiith NAN, al "usable" data was kept in tact. More specfically and sucintently nan  in pandas if a float variable  Also this replacement was only done the grades and not s student count, this would had a bigger impact, as the population size would have impacted the percentage averages.  

Not having this information could present two outcomes. Data maynot be properly allocated as we do not how well ninth graders did well on their exam, but given
population plays a part in the overall outcome

scores for both math and reading went up significantly
shouldn't effect funding
Overall outcome was not selected

changed the outcomes of the top and low perfoming school

average of would have put Thomas High School in the lowest peformance category
##### Author
Whitney Gardner
