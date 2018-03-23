<!-- Examining Distributions - Exploratory Data Analysis (EDA) --> 

1. Since the data for each variable is a long list of values (whether qualitative or quantitative), is not very informative in "raw data" form 

2. To convert our "raw data" into useful information, we need to summarize and then examine the distribution of the categorical (qualitative) variable
  ## Distribution of a value refers to:
   ## WHAT values does the variable take 
   ## HOW often the variable takes those values 
  - The DISTRIBUTION of a categorical variable is summarized using:
    - Graphical display: pie chart, bar chart
    - Numerical summaries: the Graphical displays are supplemented by Numerical summaries, which are category counts and percentages 
    
3. Frequency Distributions 
  - In a "frequency distribution" we are looking at the "frequency" of certain categories 
  - For this example study, we asked 1200 women: Where do you carry the majority of your weight? Upper body, lower body, or balanced
  - The CATEGORICAL VARIABLE we are examining is "Body Type" 
  - These are our categories: upper body, lower body, balanced
  - From this data, we can create a "Frequency Distribution" table 
    - The table will consist of: 
      ## The different values (categories) the variable takes 
      ## How many times each value occurs (count)
      ## How often each value occurs (by converting count to percentage)
      
        Category	       Count	      Percent
        Balanced	        855	          855/1200 = 71.3%
        Upper Body	        235	          235/1200 = 19.6%
        Lower Body	        110	          110/1200 = 9.2%
        Total	           n=1200	       100%
        
## Pie Charts, Bar Charts and Pictograms are used to display QUALITATIVE/CATEGORICAL DATA ##        

4. Pie and Bar Charts 
  - There are two simple graphical displays for visualizing the distribution of categorical data 
    - The Pie Chart: emphasizes how the different categories relate to the whole
    - The Bar Chart (displayed with a "count" or "percentage" axis): emphasizes how the different categories compare with each other 
    
5. Pictogram: a variation on pie charts and bar charts 
  - Pictograms CAN be misleading - make sure to use a critical approach when interpreting the information the Pictogram is trying to convey 
  
6. Describing Your Results: 
  - Once you have created your table, describe your results in "human speak" as follows for our "friends" dataset 
    - Describe the distribution of the variable "friends" in context:
      The students are NOT divided equally among the three categories. About 50% of the students find it as easy to make friends with the opposite sex as with the same sex. Among the remaining 50% of the students, the majority (36.2%) find it easier to make friends with people of the opposite sex, and the remainder (13.7%) find it easier to make friends with people of their own sex.
      
## Histogram, Stemplot and Boxplot are used to display QUANTITATIVE DATA ## 

7. To convert our "raw data" for our QUANTITATIVE variables into useful information, we need to summarize and then examine the distribution of the QUANTITATIVE variable 

8. Histogram: 
  - similar to a bar chart - a histogram is a way to display counts of data
  - Displays categorical variables in "bins" 
  - Histograms are used to display QUANTITATIVE variables 
  - When using a Histogram, some information is LOST - we have INTERVALS not EXACT numbers (scores)
  - To CONSTRUCT a Histogram - plot the INTERVAL VALUES on the X-AXIS, and show the NUMBER OF OBSERVATIONS/COUNT in each interval (frequency of the interval) on the Y-AXIS
  - To create a relative frequency table from Histogram data (Full Description in Stanford Stats Course - in One Quantitative Variable - Graps > Histogram: Intervals)
    - Calculate the total number of observations (total count) 
    - Calculate the relative frequency for each interval, by dividing the number of observations in each row by the total number of observations
  
9. Interpreting Relative Frequency Table Data
  - A relative frequency table can be used to determine the frequency of scores occuring at or across intervals
  - Example: 
  
      Exam Grades
      
       Score	     Count      Relative Frequency (this is calculated by dividing "count" by the "total")
      [40-50]	       1             0.07
      [50-60]	       2             0.13
      [60-70]	       4             0.27
      [70-80]	       5             0.33
      [80-90]	       2             0.13
      [90-100]	       1             0.07
       Total           15
  
 ## Calculating Missing Data ##  
  - It is possible to determine the number of scores (observation count) for an interval, if you have the total number of observations and the relative frequency for that interval 
  - For instance, if we know that we have 15 scores (or observations) and the relative frequency is 0.13, we can determine the number of scores by multiplying the total number of observations by the relative frequency and rounding up to the next whole number: 15 * 0.13 = 1.95, which rounds up to 2 observations.
  
- A relative frequency table, like the one above, can be used to determine the frequency of scores occurring at or across intervals. Here are some examples, using the above frequency table:

  ## What is the percentage of exam scores that were 70 and up to, but not including, 80?
    - To determine the answer, we look at the relative frequency associated with the [70-80) interval. The relative frequency is 0.33; to convert to percentage, multiply by 100 (0.33 * 100 = 33) or 33%.

  ## What is the percentage of exam scores that are at least 70? To determine the answer, we need to:
    - Add together the relative frequencies for the intervals that have scores of at least 70 or above. Thus, would need to add together the relative frequencies from [70-80), [80-90), and [90-100] = 0.33 + 0.13 + 0.07 = 0.53.
    - To get the percentage, need to multiple the calculated relative frequency by 100. In this case, it would be 0.53 * 100 = 53 or 53%.
    
10. When Setting Up Intervals
  - It is IMPORTANT that EACH OBSERVATION (score in the above example) be counted in only ONE interval
  - The syntax [40-50), [50-60), where there is a SQUARE BRACKET at the beginning, and a PARENTHESIS at the end, means "the interval from 40 to 50, including 40 NOT including 50, etc
  - You can set up your intervals however you want, but you have to be CONSISTENT 




















  
  
  
  
  
  
  
  
  