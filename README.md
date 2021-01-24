# School_District_Analysis

## Overview of the Analysis

The purpose of this analysis is to verify the authenticity of the reading and math grades obtained for Thomas High School ninth graders. In order to continue to uphold and maintain state-testing standards, the math and reading scores for Thomas High School will be replaced by NaNs, while the rest of the data will remain intact.

## Results of the School District Analysis

- As highlighted, the only changes to the analysis will occur in the Thomas High school ninth graders section, while the rest of the data remains intact. 

 ![image](https://user-images.githubusercontent.com/75655852/105624822-a06e8b00-5df2-11eb-9e16-df6dfec4ac5b.png)
 *As shown above, only the reading scores of ninth graders from Thomas High School are displayed as NaNs (Not a Number – and interpreted as an undefinable value).*

- There is a total of 461 students who are ninth graders at Thomas High School. This number is excluded from the total student count to see how the results changed. 

## Differences between the previous and current analyses

- An analysis performed with the total count of students and grades (PySchoolPractice) indicated that Thomas High School was the second best amongst the top five schools. However, after the exclusion of Thomas High School grade 9, it no longer appeared in the top five performing schools. 

![image](https://user-images.githubusercontent.com/75655852/105624923-6ce03080-5df3-11eb-96aa-14b38405bb3f.png)
*Before the exclusion of Thomas High School Grade 9 math and reading scores*

![image](https://user-images.githubusercontent.com/75655852/105624847-c8f68500-5df2-11eb-81ab-6e1cec9d1821.png)
*After the exclusion of Thomas High School Grade 9 math and reading scores*

- This could indicate that the addition of grade 9 scores had a significant impact in increasing the overall grades and therefore the ranking of the school. 

- Once the reading and math scores of Thomas High School are replaced:
        - The district_summary decreased to 64.9%
        - The overall passing scores of THS decreased from 90.948012 % to 65.076453 %
    
- There is no significant change in the math and reading scores by grade of THS, as grades 10, 11, and 12 did not experience a significant change despite the drop of grade 9 scores.

Despite having an impact on overal passing scores, there appears to be no changes to the score by school spending, school size and school type, as Thomas High School maintains a spending range (per student) of $630-644, a medium (1000-2000) school size, and remains a Charter school.

# Conclusion

After the reading and math scores for the ninth grade at Thomas High School were replaced with NaNs, there were major changes that occurred:
 - Thomas High School was no longer in the list of top performing schools.
 - The overall passing scores of Thomas High School decreased from 91 % to 65 %.
 - The passing mass scores at Thomas High School dropped from 93 % to 70 %.
 - The passing reading scores at Thomas High School dropped from 97 % to 70 %.
 - It was discovered that Thomas high School does not have any students enrolled in grade 8, 461 students enrolled in grade 9, 421 students in grade 10, 415 in grade 11, and 338 in grade 12, with a total of 1635 enrolled at Thomas High School.
 
 Overall, it is highly probable that the grades of ninth graders at Thomas High School were altered to reflect different and higher grades than the original ones obtained by the students.  

