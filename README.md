# School_District_Analysis

## Overview

I have been working with Maria in the PyCities School District to summarize district-wide school and student performance data using Pandas and Jupyter Notebook. After submitting our final reports to the district school board, the board informed us that there was evidence of academic dishonesty in our student data, and that the Thomas High School's 9th Grade Math and Reading grades appear to be altered. We have been tasked with replacing the THS 9th Grade's scores with NaN values and repeating our analysis. 

### Results

Now that our analysis is complete, we will address a number of outstanding questions. 

- **District Summary:**
  Our district-wide summary (seen below) wasn't affected much by the removal of the THS 9th Grade grades. 
  ![](Resources/1_Summary_District.png)
   We only see around two tenths of a reduction in the percentage of students passing math and one tenth of a reduction in the percentage of students passing reading. Our overall passing percentage was reduced by 3 tenths of a percentage point. 
  
- **School Summary:**
  Our school summary (seen below) also showed very little change from the previous summary run with the THS 9th Grade data included. THS saw a slight decrease in its percentage passing math and percentage passing reading, and therefore in its overall passing percentage. 
 ![](Resources/2_Summary_School.png)
 
- **THS Relative to Other Schools:**
  THS saw no change to its position in school rankings as a result of replacing its 9th Grade math and reading scores. Prior to the change, it was placed in the 2nd position overall with an overall passing percentage rate of 90.95%, and even with a reduction to 90.63% after the change, still placed above the 3rd placing school's rate of 90.60%. 
  ![](Resources/3_Summary_TopSchools.png)

- **Additional Affects:**

  - *Math and Reading Scores by Grade*
  
    Unfortunately here there is now simply an absence of data for THS' 9th Grade, whereas before there were averages of math and reading scores, respectively. 
    
  - *Scores by School Spending*
  
    Removing the THS 9th Grade scores changed no viewable data in the Scores by School Spending summary due to the percentages being rounded by tenths, instead of hundredths or not at all, as we saw in images above.  
    ![](Resources/4_School_Spending.png)
    
  - *Scores by School Size*
  
    As we saw with Scores by School Spending, I think because we are looking at percentages rounded by tenths, we are not viewing any discernable changes in this summary due to removing the THS 9th Grade scores. 
     ![](Resources/5_School_Size.png)
     
  - *Scores by School Type*

    I also wasn't surprised to see no changes here, as with the previous two summaries, we are looking at percentages rounded by tenths. 
    ![](Resources/6_School_Type.png)
    
    
### Summary

After replacing the THS 9th Grade student math and reading scores with NaN values, we can observe four changes in our summary data:
- a reduction of district-wide students passing math by 0.2%
- a reduction of district-wide students passing reading by 0.1%
- a reduction of district-wide students passing *both* math and reading by nearly 0.3%
- a reduction in THS' math (by 0.1%), reading (by 0.3%), and overall passing percentages (by 0.3%)
