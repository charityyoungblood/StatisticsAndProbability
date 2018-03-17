<!-- Learning Objectives: Relate measures of center AND spread to the shape of the distribution, and choose the appropriate measures in different contexts --> 

1. Range:
  - The "Range" is EXACTLY the distance between the smallest data point (Min) and the largest one (Max)
      Formula: Range = Max - Min 
  - It is the most intuitive measure of variability 
  
2. Inter-Quartile Range (IQR): 
  - Measures the variability of a distribution by giving us the range covered by the MIDDLE 50% of the data
  - Steps to Finding the IQR (from Stanford Statistics Course)
    - Arrange the data in increasing order > calculate the "median" 
    - Since the median separates the data down the middle, you now have a TOP 50% and a BOTTOM 50%
    - Calculate the median in the BOTTOM 50% of the data 
      - This is called Q1, the first quartile of the data 
    - Calculate the median in th TOP 50% of the data
      - This is Q3, the third quartile of the data 
    - The middle 50% of the data falls between Q1 and Q3
        IQR = Q3 - Q1  
        
3. How do we classify "extreme" observations as "Outliers"?
  - The IQR is used as a basic rule of thumb for identifying "outliers"
  - An observation is considered a "suspected outlier" if: 
    - The observation is below Q1 - 1.5(IQR) or 
    - The observation is above Q3 + 1.5(IQR)
  
  Example: 
  
  min = 85, Q1 = 130, Median = 145, Q3 = 150, Max = 250
    
   IQR = Q3 - Q1 
   Q1 - 1.5(IQR)
   Q3 + 1.5(IQR)
   
   IQR = 150 - 130 = 20 
   Below 130 - (1.5 * 20) = Below 100
   Above 150 + (1.5 * 20) = Above 180