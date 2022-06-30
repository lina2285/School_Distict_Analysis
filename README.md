# School_Distict_Analysis
## Overview of the School District Analysis
### Deliverable 1

The school board notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders appear to have been altered. Consequently, the board has asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. This analysis required using the Pandas loc method with conditional statements to successfully exclude Thomas High School's ninth-graders. 

Deliverable 1 shows how using the loc method allowed us to retrieve the specific school name and grade for math and reading, and replacing them the grades with NaNs.  
![deliverable 1](https://github.com/lina2285/School_Distict_Analysis/blob/main/Deliverable%201.png)

###Deliverable 2

On Deliverable two, we were able to recalculate all the key metrics excluding the Thomas High School ninth graders and we found that the average decreased upon removing the Thomas High School ninth grade students.  

Differences:

* The original overall passing greade average percentage was 65%, on the revised analysis, the overall passing grade average was 64.9%. 
* 
* Passing math percentage went from 75% to 74.8%
* Passing reading percentage went from 86% to 85.7%

based on the finding of deliverable 2, there is not enough infomation to conclude or confirm that there was academic dishonesty.  The differences in percentage are very close. 

![PyCitySchools_without_tsh_ninth](https://github.com/lina2285/School_Distict_Analysis/blob/main/PyCitySchools_without_tsh_ninth.png)
![PyCitySchools_inclusive_of_all](https://github.com/lina2285/School_Distict_Analysis/blob/main/PyCitySchools_inclusive_of_all.png)

The top five and bottom five

* The top five schools had an overall passing percentage between 90% and 91% 
* Per student budget between $578 and $638. 
* Student count: 
    * Highest: 2283
    * Lowest: 962

* The bottom five schools had an overall passing percentage between 52% and 53%
* Per student budget between $637 and $655
* Student Count:
    * Highest: 4761
    * Lowest: 2949

Based on the above findings, there is a possible correlations between student count and student grades. 

![Top_bottom_five](https://github.com/lina2285/School_Distict_Analysis/blob/main/top_bottom_five.png)

Average scores by grade level
* Based on the average score comparisons, it seems that Cabreara High School and Griffin High School have the highest grade averages. 

