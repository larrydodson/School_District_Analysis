# School_District_Analysis
UTMCC DataViz Module 4

## Contents
   * Background and Purpose
   * Results
   * Summary 


---

## Background and Purpose
In this report we present the results and summary for an analysis on local city high schools, as was requested by Maria. Maria is the data scientist for the city school district, and she has provided data on fifteen schools within the district, having a combined total of 39,170 students. The data is within two separate csv files, and includes student test scores for math and reading, student grade levels, the type of school with the number of students, and each school's budget in US dollars. 
    
**Purpose:** Maria is looking to provide summary information to the school board and administration for decision making for the coming school sessions, and to know the performance of each school using various metrics. The results as shown below, and in the GitHub file PyCitySchools_Challenge.ipynb, will aid in decision-making insights and intelligence on budgets and priorities for the best targeted outcomes by the board and administrators.
    
Note-1: During the work on the analysis, Maria communicated that the board notified her of evidence of academic dishonesty specific to the math and reading scores of the Thomas High School ninth-grade. She asked that these scores be removed from the analysis, replaced with NaNs, and to keep the rest of the data and analysis in place. In the Summary below, the changes to the results as was a result of this action is described. 

 **Deliverables**
  1. Replace ninth-grade reading and math scores
  2. School District Analysis
  3. Written Summary 


---

## Results 
   ### Replacing Thomas High School (THS), 9th-Grade Data
The math and reading scores were replaced with NaN using the .loc method. Please see Figture-1 to see a confirmation of this replacement, with a the head/tail view of the table. Also used to confirm the full replacements with NaNs were methods using .count() and insull().sum(). 
   
   **Figure-1** ![PyCitySch_NaN.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_NaN.png)
   
   
Also requested was to confirm the combination of the two csv files data, by creating a new data frame and using the Pandas library. Please see Figure-2 for a partial-view of the combined DataFrame: school_data_complete_df. 
   
   **Figure-2**   ![PyCitySch_CombinedData.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_CombinedData.png)


.

   ### Schools and Students analysis metrics:
        
The following information and tables are a description of the requested results of the analysis. 


  **Figure-3 School District Summary** ![PyCitySch_SchDistrictSum.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_SchDistrictSum.png)



   **Figure-4 Schools Summary**    .     ![PyCitySch_SchoolSum.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_SchoolSum.png)


**Note-2**: The overall school district was effected by the change of the removal THS-9th Grade scores. THS's scores itself were generally improved by removing while using only scores from the 10th, 11th and 12th Grades, and as a result the scores of the other schools were slightly reduced. 


In Figure-5, the Top Five and the Bottom Five Schools are shown, as a measure based on overall passing percentage of each school's students. 

**Figure-5 Schools Performance**  ![PyCitySch_PerformanceFives.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_PerformanceFives.png)


**Note-3**: As a result of removing the THS 9th Grade scores, THS moved up to second in performance overall with a 90.6% rating, from a much lower position at 65.5%.  


In Figure-6, the average scores for Math and Reading per school are shown, with the schools in alphabetical order. 

**Figure-6 Scores per Grade per School**  ![PyCitySch_ScoresGradeLvl.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_ScoresGradeLvl.png)

In Figure-6, the average scores for Math and Reading per school are shown, with the schools in alphabetical order. 


In Figure-7, the spending by each school, based on the school's budget, is compared with student scores for math, reading and overall. This is shown by spending per student, by school size, and by school type. 

**Figure-7 Student Scores compared with School Spending**  ![Resources/PyCitySch_Spending.png](https://github.com/larrydodson/School_District_Analysis/blob/master/Resources/PyCitySch_Spending.png)



.

---

## Summary 

Four major changes in the updated school district analysis (after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs).

   1. Math and reading scores by grade.  
   2. Scores by school spending.  
   3. Scores by school size.  
   4. Scores by school type.  
      


.

.end 
