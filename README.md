# School_District_Analysis

##Overview of the school district analysis: 
  The purpose of this analysis was to analyze 15 different high schools based on multiple different metrics. These metrics included number of schools, number of students, reading scores for the students, math scores for the students, and budget of the high schools. Calculation was undertaken to determine the average math score for the district, the average reading score for the district, and the percentage of students in the district who passed math, passed reading, or passed both. The total budget for the district and the total number of students in this district was calculated, as well. 
  
  Additionally, analyses of these metrics were also done for all the individual schools. After this was done, the data was refactored to only look at the data for he 10th through 12th grades of Thomas High School, leaving out their ninth graders. In addition, after conducting the analyses of the individual schools, calculations occured to determine which were the top 5 performing schools in the district and which were the lowest five performing schools in the district. Following this, analysis of the reading and math scores by individual grades was done, comparing the 4 grades' scores against each other. Afterwards, the spending for each school was looked at to determine if the amount of spending played a role in students' scores in math and reading. Finally, the size of each school was analyzed to determine if that played a role in student test scores. 

##Results: Using bulleted lists and images of DataFrames as support, address the following questions.
  Replacement of the ninth-grade schools led to the following responses in the dataset:
    * Despite other changes in the data, Thomas High School's performance compared to other schools stayed the same in regards to ranking. It remained the second-best          performing school in the district. See chart below:
    ----chart
    * The district summary was affected, seeing a decrease in percent overall passing from 65.2 to 64.9. Also, the percent passing reading decreased by 0.1%. The percent         passing math decreased from 74.98 to 74.8. See chart below for changes in DataFrame after the 9th grade score removal for Thomas High School.
      -----chart
    * When examining the school summary, the average math score for Thomas High School had decreased from 83.42 to 83.35. The average reading score for Thomas High School         had increased from 83.73 to 83.896. The percent passing math decreased from 93.27 to 66.91. The percent passing reading decreased from 97.31 to 69.66 The percent           overall passing for Thomas High school went from 90.95 to 60.08. See chart below for changes in DataFrame after the 9th grade score removal for Thomas High School.
    ----chart
    * Math and reading scores by grade only changed for Thomas High school in the ninth grade column since the grades were nto present in the analysis. All other gardes         remained the same in regards to scores.
    * When examining, scores by school spending, the average math score for Thomas High School decreased from 83.41 to 83.35. The average reading score for Thomas High           school increased from 83.85 to 83.896. The percent passing math decreased from 93.27 to 93.19. The percent passing math decreased from 97.31 to 97.02. The overall         passing percentage for Thomas High School decreased from 90.95 to 90.63. See chart below for updates
    --------chart
    * When examining the analysis of scores by school size, the average math score for schools of medium size, of which Thomas High school is a member, decreased from           83.42 to 83.35. The average reading scores decreased from 83.85 to 83.896. The percentage passing math decreased from 93.27 to 93.19. The percentage passing reading       decreased from 97.31 to 97.02. The overall passing percentage decreased from 90.95 to 90.63. See chart below for changes in data.
    ------chart
    * The data for scores by school type were unaffected by the removal of the ninth grade scores.
## Summary: 
  In summary, removing the ninth grade scores from Thomas High School led to a decrease in average math score, an increase in average reading score, a decrease in passing math percentage, a decrease in passing reading percentage, and a decrease in overall passing. 
