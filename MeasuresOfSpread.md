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