<!-- Types of Regressions --> 

1. Linear Regression 
  - Simple Linear Regression
    Formula: y = b0 + b1 * x1 (where the 0 and 1's are below the variable - not multiplied by the variable)
      
      y: the "dependent variable" - a dependent variable is the object/subject etc. you are trying to "explain" that is "dependent" on another  
        - an example of a dependent variable could be "how does a person's salary change with experience"
        where "salary" is the dependent variable 
        
      x: the "independent variable" is the one that you are hypothesizing is the one "causing" the change or implied association between the independent and dependent variable 
        - in using the "salary" example, "experience" would be the independent variable 
        
      b1: the "coefficient" (a coefficient is a number used to multiply a variable) of the independent variable 
        - it determines the "unit change" in x1 and how that affects the "unit change" in y 
      
      b0: the constant  
      
  - Multiple Linear Regression
    Formula: y = b0 + b1* x1 + b2 * x2 + ... + bn * xn (where 0,1,2 and n are below the variable - not multiplied)
    
    b0: constant - followed by many "pairs" of b and x  
    y: dependent variable 
    x: independent variables - you use this if you think there may be additional "reasons" for the dependent variable 
    
## Breakdown of Linear Regression Graph ## 
  - Salary will be our Y-Axis (Count)
  - Experience is our X-Axis (Variable)
  - The problem: We want to understand how people's salary depends on their experience 
  - The data is represented by "points" on the graph (Video @5:12) 
  - Once we implement the linear regression formula, a "slope" line is drawn that intersects with the points on the graph, that BEST FITS your data
  - The constant, b0, refers to the POINT where the "slope" or line crosses the vertical axis (Y-Axis)
    - In our exmaple, this is 30k
    - This can be interpreted as "When Experience is at 0, Salary will be $30k" 
  - b1, in our example, is the "slope" of the line
    - The "steeper" the line, the more money you get per year of experience 
    - For example, if someone went from four to five years of experience 
      - To see how the salary would "increase" you have to project the coefficient onto the line, using the points along the line, and project that onto the salary (Y-Axis) 
  
   
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
    
    
2. Logistic Regression 
  - Simple Logistic Regress
  - Multiple Linear Regression