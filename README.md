# School-District-Analysis
 Purpose 
The purpose of this analysis is to summurize data from 15 different schools in order to identify top performing schools in reading and math scores. Then to see if metrics such as school type ( district / charter ) , school size , funding or grade had any correlations. After discovering that Thomas High schools 9th grade reading and math scores we deleted the wrong information and we will point out the differences after removing the inflated score from the dataset.


How is the district summary affected?

before 
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/pyber%20summary%20df.png)

after  
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/challenge%20summary%20df.png)

How is the school summary affected?
The overalll passing readign and match scores decreased 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Before 
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/pyber%20thomas%20data%20.png)
AFter 
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/challenge%20thomas%20data%20.png)
In relation to the other schools, after replacing Thomas highschools grades it takes Thomas from a top performing school down to a bottom performing school.
Overall passing (including all grades at Thomas ) decreased From 90%  to 65%, reading 21% decreased from 90% to 69%. Even steeper declines in Math, from 93% to 66%



Math  and reading Doesnt affect by grade, 9th grade was just deleted 

Scores by school spending

Before  
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/pyber%20spending.png)
After
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/challenge%20spending%20.png)

631- 645 range score % passing reading and math score decreased ( category that Thomas was in )

Scores by school size

before
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/pyber%20school%20size.png)
after
![alt text](https://github.com/MellyCodes808/School-District-Analysis/blob/main/resources/Challenge%20school%20size.png)

Clear to see that Medium school scores decreased

Scores by school type
Thomas is a Charter school, droping thiese grades influenced the  % passing math to decrease by 4% , % passing reading decreased by 5% and Avg overall passing decreased by 3%
For district no changes were seen

After replacing the 9th grade scores from thomas with NaN scores its clear to see that this unaccurate information greatly inflated the data set and made Thomas Highschool apper as a top perfoming school, when that is not the case. Some key obervations to support this aare that  Medium school sizes % passing math and reading decreased, Avg spending per student (631-645)- % passing reading , math and overall decreased , Charter school % passing scores decreased and Median scores for 9th graders deceased.
