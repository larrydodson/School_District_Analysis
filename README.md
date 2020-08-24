# School_District_Analysis
UTMCC DataViz Module 4

## Contents
     * Background and Purpose
     * Results
     * Summary 

---

## Background and Purpose
    In this report we describe and present the results and summary for an analysis on local city high schools, as was requested by Maria. Maria is the data scientist for the city school district, and she has provided data on fifteen schools within the district, having a combined total of 39,170 students, that is within two separate csv files. The data includes test scores for math and reading, student grade levels, the type of school with number of students and budget in US dollars. 
    
    Purpose: Maria is looking to provide summary information to the school board and administration for decision making for the coming school sessions, and to know the performance of each school using various metrics. The results as shown below and in attached files will aid in decision-making insights and intelligence for the best targeted outcomes by the board and administrators. Budgets and priorities.
    
    Note: During the work on the analysis, Maria communicated that the board notified her of evidence of academic dishonest specific to the math and reading scores of the Thomas High School ninth-grade. She asked that these scores be removed from the analysis, replaced with NaNs, and to keep the rest of the data and analysis in place. In the Summary below, the changes to the results as was a result of this action is described. 

    * Deliverables
          1. Replace ninth-grade reading and math scores
          2. School District Analysis
          3. Written Summary 


## Results 
   ### Replacing Thomas High School (THS), 9th-Grade Data
    The math and reading scores were replaced with NaN using the .loc method. Please see Figture-1 to show a confirmation of this replacement. Also used to confirm the full replacemlent with Nans were methods using .count() and insull().sum(). 
   
   Figure-1 ![PyCitySch_NaN.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_NaN.png)
   
   
   Also requested was to confirm the combination of the two csv files data, by creating a new Data Frame and using the Pandas library. Please see Figure-2 for the head/tail of the combined DataFrame school_data_complete_df. 
   
   Figure-2   ![PyCitySch_CombinedData.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_CombinedData.png)



   ### Schools and Students analysis metrics:
        - The district summary. How is the overall summary affected?
        - The school summary. How is the school summary affected?
        - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
        - The top 5 and bottom 5 performing schools, based on the overall passing rate
        - The average math score for each grade level from each school
        - The average reading score for each grade level from each school
        - The scores by school spending per student, by school size, and by school type

             - How does replacing the ninth-grade scores affect the following:
             - Math and reading scores by grade
             - Scores by school spending
             - Scores by school size
             - Scores by school type



Figure-3 School District Summary ![PyCitySch_SchDistrictSum.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_SchDistrictSum.png)



Figure-4 Schools Summary ![PyCitySch_SchoolSum.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_SchoolSum.png)






Figure-5  ![PyCitySch_PerformanceFives.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_PerformanceFives.png)



Figure-6  ![PyCitySch_ScoresGradeLvl.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_ScoresGradeLvl.png)




Figure-7  ![Resources/PyCitySch_Spending.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_Spending.png)



.

---

## Summary 

   Four major changes in the updated school district analysis (after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs).
   1. a
   2. b
   3. c
   4. d
      


.

.end 
