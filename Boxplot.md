<!-- Boxplot: Used for graphical display of a quantitative variable --> 

1. Boxplot: 
  - The boxplot graphically represents the distribution of a quantitative variable by visually displaying the "five-number summary" and any observation that was classified as a suspected outlier using the 1.5(IQR) criterion
  - see "MeasuresOfSpread.md" > point 3. 
  - Boxplots are MOST USEFUL when presented side-by-side for comparing and constrasting distributions from two or more groups 
  
2. Boxplot Components/Features:
  - Central Box: 
    - the actual "Box" portion of the display
    - the Central Box spans from Q1 to Q3 
  - Horizontal Line in the Middle of the box: this is the Median across all observations
  - Two Lines that extend ABOVE and BELOW the Box: these lines go to the SMALLEST and LARGEST observations that are NOT classified as OUTLIERS  
  - Any Outliers that might be present in the data set: These are displayed as "dots" 
  
3. Boxplot Values:
  - To create a boxplot, plot the whiskers (thin lines) down to the minimum and up to the maximum value 
    - STEP 1: Calculate the IQR
    - STEP 2: Multiply IQR by 1.5 
    - STEP 3: Add the value from Step 2, to Q3
    - STEP 4: Subtract the value from STEP 2 from Q1 >> Q1 - (1.5 * IQR)
    - STEP 5: Plot whisker points based on the following: 
        - If the value from Step 3 is GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker to the maximum value 
        - If the value from Step 3 is NOT GREATER THAN or EQUAL TO the MAXIMUM VALUE in the dataset, draw the upper whisker at the LARGEST VALUE that is LESS THAN Q3 + (1.5 * IQR) (review "MeasuresOfSpread.md point 3.) - (this point represents the largest observation in the dataset that is NOT an outlier)
        - If the value from Step 4 is LESS THAN the MINIMUM VALUE in the dataset, draw the LOWER whisker to the MINIMUM value 
        - If the value from Step 4 is GREATER THAN or EQUAL TO the MINIMUM VALUE in the dataset, draw the LOWER WHISKER at the LOWEST VALUE that is GREATER THAN Q1 - (1.5 * IQR) (review "MeasuresOfSpread.md point 3.) - (this point represents the smallest observation in the dataset that is NOT an outlier)
    - STEP 6:
      - ANY VALUES that are GREATER THAN the UPPER WHISKER whisker point, as INDIVIDUAL POINTS (OUTLIERS)
      - ANY VALUES that are LESS THAN the LOWER WHISKER point, as INDIVIDUAL POINTS (OUTLIERS)

4. Interpreting Box Plots (Review Boxplot - Side-by-Side Boxplots)
  - When there is LITTLE VARIABILITY, the values are more "CONSISTENT"
  - When there is LARGE VARIABILITY, the values "LACK CONSISTENCY"
  - The CENTER of the distribution is MORE MEANINGFUL as a "typical" value for the distribution when there is LITTLE VARIABILITY 
    
## BELOW ARE EXAMPLES OF HOW TO "TALK" OR "DESCRIBE" THE DATA ##
    
  Examples: Interpretation of Box Plot for Colleges (from Statistics Package Exercise: Creating Side-by-Side Boxplots) 
     
## Assignment: Compare and contrast the distributions of the graduation rates at the different colleges. Be sure to address center, spread and outliers. ## 
     
  - Center: Of the six colleges, college D has the highest median graduation rate (M = 79), followed by colleges F (M = 72), B (M = 70.15), C (M = 67.65), A (M = 63.75) and college E (M = 59.15).

  - Spread: College B has the smallest variation in graduation rates over the years (range = 9.4%, IQR = 3.5%). College D's graduation rates are also pretty consistent over the years (range = 10.5%, IQR = 4.45%). A larger variation in graduation rates is found in colleges E and C, and the least consistency in graduation rates (i.e., largest variation) is found in college A (range = 30.6%, IQR = 19.55%) and college F (range = 29.7%, IQR = 16.23%).

  - None of the graduation rates distributions have outliers.
       
## Assignment: If you had to choose one college among the six colleges based on this data, which college would it be? Explain your reasoning. ## 

  - If I had to choose one college based on the graduation rates, I would choose college D. Not only does this college have the largest median graduation rates, but it also has the smallest variation in graduation rates over the years. This means that even in years when college D has a relatively small graduation rate, it is not MUCH smaller than the median (min = 74.1%, Median = 79%), and is still higher than most graduation rates at the other colleges. In particular, the smallest graduation rate that occurred in college D (74.1%), is still higher than:

      • the highest graduation rate at colleges A and E,

      • the third quartile of the distribution of graduation rates at colleges B and C, and

      • the median graduation rate at college F.

























