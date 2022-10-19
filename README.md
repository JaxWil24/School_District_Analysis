# School District Analysis

## Overview
* An analysis and correction was completed on the data for highschoolers. Evidence of academic dishonesty led to a reworking of data for performance of multiple high schools, specifically Thomas High School. Code removed the faulty scores and reworked the data to show a more accurate measurement of the schools success. 


## Results
* The district summary improves slightly in all grading categories. The total schools, total students, and total budget remain the same. 
![image](https://user-images.githubusercontent.com/106329824/196699160-8225c207-0db6-4522-bb6d-890c8051134d.png)

* The school summary is generally the same except for Thomas High School. As a whole, Thomas High School becomes a good school with high passing rates when before Thomas High School was barely passing math or reading.
![image](https://user-images.githubusercontent.com/106329824/196700215-646320b6-d4c9-4207-8e7c-e53e55f9b819.png)

* Replacing the ninth graders' math and reading scores puts Thomas High School's performance equal to the performance of other schools.

![image](https://user-images.githubusercontent.com/106329824/196699800-924a1faa-e286-49d1-9abb-3f576b8762c9.png)

* Replacing the ninth-grade scores does not affect other grades for math and reading.

* Replacing the ninth-grade scores does not affect school spending.  

* Replacing the ninth-grade scores affects school size by decreasing Thomas High School. This decrease is the number of students without the 9th grade, making it 461 less.
![image](https://user-images.githubusercontent.com/106329824/196700494-8a3dd73e-c9c5-4e68-8bd0-2cc2f9b87674.png)

* Replacing the ninth-grade scores does not affect school type.

## Summary

* A change in the school district after reading and math scores for the ninth grade at Thomas High after being replaced with NaNs is the overall scores of Thomas High School. The overall passing rate went up, and the percentage of passing reading and math drastically changed.

* Another change in the school district would be a more accurate reading of how effective Thomas High School truly is. By taking away the dishonest test scores, we are left with an honest look at the performance.

* Instead of changing the scores or student ID to 0, using NaN for the ninth grade Thomas High School allows for a less convoluted look at the data. Understanding NaN helps to clarify when data is incorrect or incompatible.

* Replacing the reading and math scores for the ninth graders at Thomas High School with NaN puts Thomas High School more in line with the other schools from the district.
