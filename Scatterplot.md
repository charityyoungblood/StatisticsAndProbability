<!-- Scatterplot --> 
## When creating a Scatterplot in R - Complete Steps in R_LinearRegression.md FIRST ##

1. Scatterplot
  - To examine the relationship between two QUANTITATIVE VARIABLES we use a Scatterplot
  - To create a Scatterplot:
    -> Each PAIR of values is plotted > The EXPLANATORY VARIABLE (X) is plotted on the X-Axis (Horizontal)
    -> The value of the RESPONSE VARIABLE (Y) is plotted on the Y-Axis 
  - When creating a Scatterplot the EXPLANATORY VARIABLE should ALWAYS be plotted on the HORIZONTAL AXIS
  - The RESPONSE VARIABLE should ALWAYS be plotted on the VERTICAL AXIS (Y-AXIS)
  
2. How To Interpret A Scatterplot 
  - When describing the relationship between two quantitative variables using a Scatterplot we look at: 
    - Overall Pattern:
      - Direction: this can be "Positive", "Negative" or "Neither" 
        - Positive Relationship: means that an increase in one of the variables is associated with an increase in the other 
        - Negative Relationship: means that an increase in one of the variables is associated with a decrease in the other 
      - Not ALL relationships can be classified as either "Positive" or "Negative" 
      - Form: this is the Scatterplot's general shape 
        - When identifying the "form", try to find the simplest way to describe the shape of the Scatterplot 
        - Linear: Relationships with Linear form are described as points scattered about a line 
        - Curvilinear: Relationships with Curvilinear 
        - Clusters 
      - Strength: The "Strength" of the relationship is determined by how closely the data follow the "form" of the relationship 
    - Deviations From The Pattern: Data points that deviate from the pattern are called "Outliers" 
    
3. Labeled Scatterplot
  - Adding labels to a Scatterplot that indicate different groups or categories within the data might help us get more insight about the relationship we are exploring 
  - Labeled Scatterplots can provide further insight about the relationship we are exploring 
  
4. Regression Line in R - enter the following: 
  - modelVariableName=lm(dataFrameName$Y-AxisHeader ~ dataFrameName$X-AxisHeader)
  - abline(modelVariableName)
  - cf=coefficients(modelVariableName); 
  - lt=paste("GPA = ",round(cf[1],2),"+",round(cf[2],2),"HS_GPA")
  - legend(1.7,4.3,lt)