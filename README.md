# School_District_Analysis
Using python to analyse Math exam results for a school district

##Challenge

Recreate the district and school summary DataFrames.
- How is the district summary affected?
- How is the school summary affected?

For the new district summary, we don’t see many large-scale changes. Average math score and average reading score are practically unchanged, but the percent of students that passed math and reading dropped by about 1% and as a result the percent that passed overall also dropped by 1%.

For the new school summary we see the average math score fog down negligibly, and the average reading score go up negligibly for Thomas High School, but we see a big drop in the % passing scores given that all the 9th graders now contribute to the non-passing scores in these statistics.

Recalculate the high- and low-performing schools.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

Replacing the ninth grader’s math and reading scores affects Thomas High School’s performance relative to other school quite dramatically. Thomas goes fom the 2nd highest performing school by % overall passing, to the 8th highest (7th lowest) performing school by % overall passing.

Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
- How does replacing the ninth-grade scores affect the following?
    -Math and Reading Scores by Grade
    -Scores by School Spending
    -Scores by School Size
    -Scores by School Type
    
Replacing ninth grader’s math and reading scores create an NaN for Thomas High School scores by grade in the 9th grade. In the scores by school spending, the averages are unchanged, but in the $630-644 bucket where Thomas High School is located, the % passing math and reading drop by 6 and 7 percent respectively and the % overall passing drops by 7 percent. For scores by school size, Thomas High School is categorized as a medium school, and as a result we see the % passing math, reading and overall passing drop by 6 percent each. Lastly, as Thomas High School is a charter school, we see the % passing math and reading drop by 4 percent respectively and the % overall passing drop by 3 percent.
