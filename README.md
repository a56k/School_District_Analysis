#School_District_Analysis

    This challenge requires to analyze the data for different schools based on their district, budget, size, etc. 
    More specifically, the exercise asks us to focus on "Thomas High School" and provide results related to academic dishonesty for students in ninth grade. As part of the research, we're taken through multiple steps to ensure the data is clean by verifying any missing values and altered scores for THS. Further, as a short-term solution to quickly ascertain the missing information, we replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 
    Additionally, we repeated the school district analysis done during the course walkthrough to observe trends and existing discrepancies between the math, reading, and overall passing scores. This comparison provides an overview of the changes - if any. - has occurred based on suspicion of Maria. 

#How is the summary district affected?
    No significant changes are observed after analyzing both the class module and the challenge.
    
#How is the school summary affected?

    We do notice a change with THS grades as we extract the 9th graders from the list. The average scores for all students passing both Math and Reading dropped by a small percentage (.3% ) specifically. The analysis done in class contains the grade for the total students, including the 9th graders.
    
#How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

    With no significant changes observed for both Math & reading scores, it's important to note that the suspicion of academic dishonesty may be proven right if we include the  9th graders' overall grades in the report. 
    
    Doing so would drag THS average scores below the current number and ultimately affect the district's school ranking. 
    
#How does replacing the ninth-grade scores affect the following: #Math and reading scores by grades

    We can observe which values are missing and from which school - this allows us to pin-point the problem quickly as we assess the data for outliers and discrepancies. We've used the function "np. NAN" to replace missing values.
    
#Scores by school Spending

    There is no changes in the numbers as the 9th Graders are absent from the analysis.
    
#Scores by school size

    No significant changes observed for the "overall Passing Percentage" grades.
    
#Scores by school types

    No changes in this part of the analysis.
    
# Clonclusion:

    As we conclude the analysis, no significant changes are occurring with the rest of the challenge. By subtracting 9th graders, we ensure that values that could have affected our analysis remained out of the data frames. Thus, we had a better overview and scope of the necessary data to conduct our research and provide the required results. 

