<!-- Ordinary Least Squares Method --> 

How does the Simple Linear Regression FIND the "Trend" line? By Using the Ordinary Least Squares Method 

1. Refer to example from video (@0:24) 

2. The red crosses - represent the actual observations we have in our data 

3. The "Trend Line" - represents the "best fitting" line; this "trend line" is also referred to as the "Simple Linear Regression Model" 

4. If we were to draw vertical lines to FROM the observations TO the "trend" line (or "Model")
  - The red cross (our ACTUAL observation data) - for our salary example, this is the ACTUAL salary amount the person is receiving 
      - The red cross is called yi (y subscript i)
      - This represents the ACTUAL VALUE
  - The green cross - or accompanying point on the model, by following our vertical line down to where the it "hits" the trend line, represents what salary the person SHOULD be making, according to the model 
      - The green cross is called yi^ (y i "hat")
      - This represents the value the model PREDICTS that person should be earning
  - The vertical line we drew to the model, represents the DIFFERENCE between the ACTUAL VALUE and the PREDICTED VALUE 
  - Think of this vertical line to the model/trend line as the DIFFERENCE between the OBSERVED and the MODELED for that level of independent variable
  
5. To Find the "Trend Line" or Linear Regression Model 
  - We take each one of our vertical lines > Calculate the distance between the OBSERVED and MODELED > Square the values 
  - Then take the sum of the squared value
  - Sum of Squares of Residuals Formula: 
        SSres = SUM((yi - yi^)^2)
  - Once you have the sum of the squared values, you have to find the minimum 
  - A Simple Linear Regression, draws numerous amounts of vertical lines from the OBSERVED VALUE to the PREDICTED VALUE on the model, and counts the sum of those squares every time and records it > then it FINDS the MINIMUM sum of squares
  - This line that has the minimum sum of squares possible, will be the BEST FITTING LINE 
  - This process is called the Ordinary Least Squares Method 
  
## R Squared Parameter ## 

1. Sum of Squares of Residuals
    SSres = SUM((yi - yi^)^2)

2.  = SUM((yi - yavg)^2) - where "i" and "avg" are subscripts not regular multilple

3. Instead of the regression line we drew in the previous example, we now draw an AVERAGE line 