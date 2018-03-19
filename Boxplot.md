<!-- Boxplot: Used for graphical display of a quantitative variable --> 

1. Boxplot: 
  - The boxplot graphically represents the distribution of a quantitative variable by visually displaying the "five-number summary" and any observation that was classified as a suspected outlier using the 1.5(IQR) criterion
  - see "MeasuresOfSpread.md" > point 3. 
  
2. Boxplot Values:
  - To create a boxplot, plot the whiskers (thin lines) down to the minimum and up to the maximum value 
    - STEP 1: Calculate the IQR
    - STEP 2: Multiply IQR by 1.5 
    - STEP 3: Add the value from Step 2, to Q3
    - STEP 4: Subtract the value from STEP 2 from Q1 >> Q1 - (1.5 * IQR)
    - STEP 5: Plot points based on the following: 
        - If the value from Step 3 is GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker to the maximum value 
        - If the value from Step 3 is NOT GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker at the LARGEST VALUE that is LESS THAN Q3 + 1.5 * IQR (review "MeasuresOfSpread.md point 3.) - (this point represents the largest observation in the dataset that is NOT an outlier)
    - Fifth, ANY VALUES that are GREATER THAN the upper whisker point, as INDIVIDUAL POINTS (OUTLIERS)
  

