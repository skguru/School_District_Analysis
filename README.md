# School_District_Analysis


Challenge Description:  Maria and her supervisor discovered the score averages for ninth graders from one high school are incorrect.    Present the analysis by removing the ninth grade math and reading scores for that high school.

Background:

It was found that Thomas High School was the school in question and the following steps are necessary to present the cohesive summary to Maria and her supervisor.  

-Remove the ninth-grade math and reading scores from Thomas High School
-Keep all other data associated with the ninth-grade students and Thomas High School intact

In order to do that, following actions were completed:

-Replaced the reading and math scores for ninth graders at Thomas High School with NaN.

Analysis Summary: 

-District summary is not impacted by this removal of the data.  The data remains the same after the removal of the ninth grade math and reading scores for Thomas High School. 
-School Summary is impacted significantly.  
  -prior to the removal, Thomas High School was on the Top 2 schools based on %Overall Passing
  -After the removal, Thomas High School came to the bottom most school based on %Overall Passing
-Thomas High School performance impacts significantly
  -%Passing Math pre vs post = 93.27 vs 66.91
  -%Passing reading pre vs post = 97.31 vs 69.66
  -%Overall passing pre vs post = 95.29 vs 68.29

The code provides detailed analysis per grade, per spending, per school size and type. 

Conclusion: 

Thomas High School's performance came down significantly by the removal of ninth grade math and reading.  
