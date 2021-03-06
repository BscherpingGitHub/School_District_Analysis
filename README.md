# School_District_Analysis
# Overview of the school district analysis
We were tasked to condense, calculate and sort the reading and math grades of a school district. 
# Results
How is the district summary affected?
-	The district summary went down by a small percentage. <br/>
Original district summary: <br/>
![districtsummary](Resources/districtsummary.png)<br/>
New district summary: <br/>
![newdistrictsummary](Resources/newdistrictsummary.png)<br/>

How is the school summary affected?
-	The school summary went down overall very small. <br/>
Original school summary: <br/>
![summaryorig](Resources/summaryorig.png)<br/>
New school summary: <br/>
![summarytentwe](Resources/summarytentwe.png)<br/>

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
-	Thomas High School stayed where it was. <br/>
Original top 5: <br/>
![origtop5](Resources/origtop5.png)<br/>
New top 5: <br/>
![newtop5](Resources/newtop5.png)<br/>

How does replacing the ninth-grade scores affect the following:
- Math and Reading scores by grade
   - It only brought down the 9th grade average.<br/>
   
Original math scores by grade: <br/>
![mathgradeavg](Resources/mathgradeavg.png)<br/>
New math scores by grade: <br/>
![mathgradeavgna](Resources/mathgradeavgna.png)<br/>
Original reading scores by grade: <br/>
![readinggradeavg](Resources/readinggradeavg.png)<br/>
New reading scores by grade: <br/>
![readinggradeavgna](Resources/readinggradeavgna.png)

- Scores by school spending
   -	The school spending with Thomas High School went down a small percentage <br/>
   
Original scores by school spending: <br/>
![schoolspending](Resources/schoolspending.png)<br/>
New scores by school spending: <br/>
![schoolspendingna](Resources/schoolspendingna.png)

- Scores by school size
  -	The scores went down for the school size with Thomas High School <br/>
  
Original scores by school size: <br/>
![schoolsize](Resources/schoolsize.png)<br/>
New scores by school size: <br/>
![schoolsizena](Resources/schoolsizena.png)<br/>
- Scores by school type
  -	The scores went down for the school type with Thomas High School <br/>
  
Original scores by school type: <br/>
![schooltype](Resources/schooltype.png)<br/>
New scores by school type: <br/>
![schooltypena](Resources/schooltypena.png)<br/>


# Summary
There were small changes in the 4 criteria’s:
1.	Scores by grade: grades went down .2% for passing math and .1% for passing reading.
2.	Scores by school spending: spending went down .1% for passing reading and .1% for overall percentage.
3.	Scores by school size: the medium school size went down .1% for passing reading. 
4.	Scores by school type: the school type charter went down .01% for passing math, .04% for passing reading, and .04% for overall percentage. <br/>
Each of these changes were very small. I had to format the code for extra decimal places to find differences. The reason for small changes is due to the amount of data being impacted. We are only impacting around 450 of 39,000 students. This small number will only change the data a small amount which is why I had to change the format. The only big change was when we included the NaN students in the total students while including the NaN status on passing reading and math.

Orgininal school summary: <br/>
![summaryorig](Resources/summaryorig.png)<br/>
School summary with NaN students included in total student count: <br/>
![summarywithna](Resources/summarywithna.png)<br/>

The NaN value is bascially 0 causing the percentages to drop which is represented in the data above. 
