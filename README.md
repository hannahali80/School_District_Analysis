# School_District_Analysis

**Deliverable 3: A Written Report for the School District Analysis:**


1.	Overview of the school district analysis: Explain the purpose of this analysis.

The purpose of this analysis is to summarize data by using loc function and other logical formulation to summarize data in a quick readable format for high level overview. 
    The key metrics were present in table format:
        -	Top 5 top and bottom performing schools based on the pass rate
        -	The score average reading and math score received by students in each grade level
        -	The performance of school based on budget, school size and type of school

2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions.

    A.	How is the district summary affected?
        The district summary showed no change after replacing the 9th grade Thomas High School students math and reading scores with NaN values.  
        
        Below are the results:
      
      ** Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
          0	15	          39,170	     $24,649,428.00       	78.9	              81.9	            74.8	             85.7	            6**

    B.	How is the school summary affected?
    
        The school summary showed a bit of decrease in results:
        
                           
        School Type	 Total Students	  Budget	       Per Student Budget	Average Math Score	Average Reading Score % Passing Math	% Passing Reading	% Overall Passing
        Thomas                    
        Before           1635	       $1,043,130.00   $638.00	           83.350937	        83.896082	              66.911315	      69.663609	      65.076453
        After:           1635	       $1,043,130.00	 $638.00	           83.350937	        83.896082	              93.185690	      97.018739	      90.630324
        
    C.	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    
        The replcacing of 9th grader math and reading score did affect the passing math by 26.27% (66.91 to 93.18), passing reading by 27.02% (69.6 to 97.02) and overall passing         by 25.56% (65.07 to 90.63).
    D.	How does replacing the ninth-grade scores affect the following:
    
         1. Math and reading scores by grade
            Only the Thomas High School scores were affected due to 9th grade with overall 25.56% while other schools remained the same. 
    
         2.	Scores by school spending
            No change founds, results remain the same.  
    
         3.	Scores by school size
            No change founds, results remain the same.  
    
         4.	Scores by school type
            No change founds, results remain the same.  

3.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 
         The four changed found after updating reading and math scores for ninth grade at Thomas High School are the following:
          A. The overall performance of school increased by 25.56.
          B. The passing math score were increased by 26.27%
          C. The passing reading score were incerased by 27.02%
          D. Overall changing the 9th grader data did affect the overall scores
