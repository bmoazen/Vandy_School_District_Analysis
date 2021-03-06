# School District Analysis
## Overview
In this project, we used the pandas library in python to analyze standardized math and reading test scores for a city school district in order to identify trends in performance by school, school type, grade, spending per student, as well as other categories.  Our input file listed the standardized test scores of each student, as well as other useful information (school, grade level, gender, and others).

# Data Concerns
One concern with the data is that the ninth grade reading and math grades for one high school, Thomas High School, appeared to have been altered.  For this reason, two separate analyses were performed: one with all of the student scores and one in which the scores for Thomas High School ninth graders were removed.

# Contents
PyCitySchoolClean.ipynb - Python Code looking at the full student data <br />
PyCitySchool_Challenge.ipynb - Python Code looking which removes the Thomas 9th grade scores and runs the same anlysis as the full styudents data set <br />
PyCitySchoolCompare.ipynb - Python Code which compares the two analysis <br />
Resources Folder - contains the school and student data in csv <br />
Results Folder - contains results from the comparison sanalysis in csv form as well as png images of result dataframes <br />


# Results
All results can be found in CSV form in the Results folder of this repository
* District Summary <br />
  The district summary for all students and with the 9th graders of Thomas High School removed schools and all students is shown below:<br />
  ![alt text](https://github.com/bmoazen/Vandy_School_District_Analysis/blob/main/Results/districtBoth.PNG?raw=true)
  https://github.com/bmoazen/Vandy_School_District_Analysis/blob/main/Results/districtBoth.PNG?raw=true <br />
  Since there are only 461 Thomas High School 9th graders out of a total of over 39,000 students in the district, the removal of these scores has very little impact on the scores of the district as a whole.

* School Summary <br />
  Since only 9th grade students were removed from the data, only scores relating to Thomas High School would be affected (i.e. there would be no affect on scores from other schools)
  ![alt text](https://github.com/bmoazen/Vandy_School_District_Analysis/blob/main/Results/thomasBoth.PNG?raw=true)
  https://github.com/bmoazen/Vandy_School_District_Analysis/blob/main/Results/thomasBoth.PNG?raw=true <br />
  Removal of the Thomas High School 9th grade scores did little to affect the overall scores of the school.  This is most likely due to the fact that the 9th grade scores were very similar to the scores for that of the rest of the school.
  
* Thomas High School compared to other schools <br />
  Since the overall Thomas High School scores were not affected much ny the removal of the 9th grade scores, a comparison of the school with that other the other district schools would not be affected either
  
 * Scores by grade, school spending, size, and school type <br />
  Again, since the overall numbers were not affected by the removal of the Thomas High School 9th grade scores, analysis of other factors, such as grade, school spending, size, and school type, would not be affected.

  
