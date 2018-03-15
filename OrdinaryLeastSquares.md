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
      - yi is the OBSERVED or ACTUAL VALUE
      - yi hat is the PREDICTED or MODELED VALUE 

2. Total Sum of Squares
    SStot = SUM((yi - yavg)^2) - where "i" and "avg" are subscripts not regular multilple
    - yavg is your AVERAGE salary across ALL of your observations 
    
3. Instead of the regression line we drew in the previous example, we now draw an AVERAGE line 

4. Next, we add vertical lines from the OBSERVED data to the AVERAGE (points on the line)

5. Calculate the distance/difference between the OBSERVED data and AVERAGE, then square the values 
    SUM((yi - yavg)^2)
    
6. R Squared
  - R Squared is equal to 1 minus the Sum of Squares of Residuals divided by the Total Sum of Squares 
    R^2 = 1 - (SSres / SStot)
  - R Squared is telling us "how GOOD our Simple Linear Regression Model (Trend Line) is COMPARED to the AVERAGE line" 
  - The closer R Squared is to 1, the better - R Squared should NEVER be more than 1 
  - Interpretation: Since there will always be a total sum of squares, i.e. the sum of squares will always be "some value" 
    - What you are trying to do with your regression, is fit a line to minimize the Sum of Squares of Residuals 
    - The average line is also a type of "Trend Line" - think of this as a "model" that is fit to your data set, NOT the slope, but still a type of "Trend Line" 

## Adjusted R Squared ## 

1. REMEMBER: the closer your R Squared value is to "1" the better 
  - Your value will be between 0 and 1 
  - We want to use R squared as a "best fit" parameter

2. Potential problem with R Squared 
  - The problem starts to occur when you add more variables to your model  
  - You would/could potentially add independent variables that you think are impacting the dependent variable (the outcome) and you want to fit the model to see if it's better or not (after adding additional independent variables) 
  - In this case, you would be answering the question: "Did R Squared INCREASE (meaning this would be the BETTER model) or did R Squared stay the same?"
  - R Squared will NEVER DECREASE when you ADD independent variables
  - The problem with R Squared is that you can add variables to your model, but you will NOT know if those variables are "helping" your model or "not helping"
  - Ex: In simple linear regression formula 
      y = b0 + b1 * x1 >> where "y" is the dependent variable, "b0" is a constant, "b1" is the coefficient to the independent variable, and "x1" is the independent variable 
  - In the case of multiple linear regression, the formula changes to:
      y = b0 + b1 * x1 + b2 * x2 + b3 * x3 + ... bn * xn  
  
  
3. Adjusted R Sqaured Formula 
    Adj R^2 = 1 - (1 - R^2)n - 1 / n - p - 1 
      - p is the number of regressors (independent variables)
      - n is the sample size  
  - Adjusted R Squared has a penalization factor: it penalizes you for ADDING indpendent variables that DON'T help your model 
  - Analyzing the formula 
    - Since p is in the denominator, when p INCREASES, the DENOMINATOR VALUE DECREASES 
    - When the denominatory DECREASES the ratio INCREASES (inversely proportional)
    - When the ratio INCREASES the (1 - R^2) portion of the formula ALSO INCREASES 
    - When the (1 - R^2) portion of the formula INCREASES and is subtracted from 1 (first part of formula), DECREASES 
    - The above all means that the Adjusted R Squared value is DECREASING, going further away from 1


































