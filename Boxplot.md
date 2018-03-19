<!-- Boxplot: Used for graphical display of a quantitative variable --> 

1. Boxplot: 
  - The boxplot graphically represents the distribution of a quantitative variable by visually displaying the "five-number summary" and any observation that was classified as a suspected outlier using the 1.5(IQR) criterion
  - see "MeasuresOfSpread.md" > point 3. 
  
2. Boxplot Values:
  - To create a boxplot, plot the whiskers (thin lines) down to the minimum and up to the maximum value 
    - First, calculate the IQR
    - Second, multiply IQR by 1.5 
    - Third, add the value from Step 2, to Q3
    - Fourth, analyze below: 
        - If the value from Step 3 is GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker to the maximum value 
        - If the value from Step 3 is NOT GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker at the LARGEST VALUE that is LESS THAN Q3 + 1.5 * IQR (review "MeasuresOfSpread.md point 3.) - (this point represents the largest observation in the dataset that is NOT an outlier)
  

