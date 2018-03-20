<!-- Measures Of Spread: Standard Deviation --> 

1. Standard Deviation: 
  - A measure of spread that quantifies the spread of a distribution by measuring how FAR the observations are from their MEAN 
  - The Standard Deviation gives the average, or typical distance, between a data point and the mean
  - There are a few notations for the Standard Deviation including: SD, s, Sd, StDev

## Example: Here are the dress sizes tried on by customers in an 8 hour period: 
      
  Size 8, Size 10, Size 12, Size 14, Size 6, Size 4, Size 16, Size 10, Size 8, Size 14, Size 12 
  
    Step 1: Find the Mean of your data
    
      (8 + 10 + 12 + 14 + 6 + 4 + 16 + 10 + 8 + 14 + 12) / 11 = 10.36
        
        Mean = 10.36
        
    Step 2: Find the deviations from the mean: the difference between each observation and the mean
      (8 - 11), (10 - 11), (12 - 11), (14 - 11), (6 - 11), (4 - 11), (16 - 11), (10 - 11), (8 - 11), (14 - 11), (12 - 11)
           -3, -1, 1, 3, -5, -7, 5, -1, -3, 3, 1
           
    Step 3: Square each of the deviations 
      (-3 * -3), (-1 * -1), (1 * 1), (3 * 3), (-5 * -5), (-7 * -7), (5 * 5), (-1 * -1), (-3 * -3), (3 * 3), (1 * 1) 
          
        9, 1, 1, 9, 25, 49, 25, 1, 9, 9, 1
        
    Step 4: Average the square deviations and divide by n - 1 (one less than the sample size)
        (9 + 1 + 1 + 9 + 25 + 49 + 25 + 1 + 9 + 9 + 1) / (11 - 1) = 13.9 
        ** This average of the squared deviations is called the "VARIANCE" of the data **
        
    Step 5: The SD of the data is the square root of the variance 
          SD = sqrt(13.9) = 3.73
          