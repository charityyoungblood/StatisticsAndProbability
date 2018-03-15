<!-- Linear Regression in R --> 

Information from Youtube Series: 24/7 ProLearn - Data Science with R 

## Step 1: Create Data Frame ##
  - If data is in any other file extenstion, other than .rdata, load data first 
  - To create data frame in R, use the following command: 
    variableName = read.table("fileName.fileExtension", header=TRUE, sep=",", skip=0)
      - variableName: this can be any name you like, in lower case letters 
      - fileName.fileExtension: Example - "Salary.csv" 
      - sep: what the file is separated by (i.e. comma in csv)
      - skip: this is if you want to enter any data to "skip", if no skip needed, enter 0 

## Step 2: Create a Scatterplot ## 
  - We will create a Scatterplot using our two variables of interest (in the example from class, these are "Salary" and "Years of Experience")
  - We create a Scatterplot in order to provide a VISUAL explanation for our Linear Regression Model as we construct it 
  - We'll use the "Base Plotting System", which is one of the three plotting systems in R 
  - To create the Scatterplot, enter the following command: 
    plot(x = dataFrameName$ColumnTitleForXAxis, y = dataFrameName$ColumnTitleForYAxis, main = "ScatterPlotTitle", xlab = "XAxisTitle", ylab = "YAxisTitle")
      - main: refers to TITLE of your Scatterplot
      - xlab: TITLE for X-AXIS
      - ylab: TITLE for Y-AXIS
      
## Step 3: Create Linear Regression ## 
  - To create the Linear Regression (not the trend line, but the information we need to create the trend line, enter the following command: 
    model = lm(formula = ColumnTitleForYAxis ~ ColumnTitleForXAxis, data = dataFrameName)
      formula: set your YAxis value "as a function" of XAxis value - formula's in R are defined as our OUTCOME VARIABLE as a FUNCTION of our EXPLANATORY VARIABLE 
  - Next, we have to use the SUMMARIZE function and pass in our model as an argument (the above formula will not automatically create the model and open another window like the Scatterplot does), enter in the following: 
    summary(modelVariableName)
  - Now our summary will be displayed in our console

## Step 4: Create Linear Regression Trend Line (Model) ## 
  - To create the Linear Regression Trend Line (Model), enter the following: 
    lines(x = dataFrameName$ColumnTitleForYAxis, y = modelVariableName$fitted, col = "red", lwd = 3)
      - fitted: refers to the fitted value of our linear regression model - i.e. the predicted salary given years of experience
      - col: color of the line 
      - lwd: line width (in pixels)
      
## Step 5: Prediction of New Values From our Linear Regression Model ## 
  - Before we predict new values based on our linear regression model, we first need to look at the correlation coefficients of the two variables we are studying: "salary" and "years of experience" 
  - Enter in the following command: 
    cor(x = dataFrameName$ColumnTitleForXAxis, y = dataFrameName$ColumnTitleForYAxis)
  - In our example, the correlation coefficient of our two variables is 0.9782416
    - Since this value is CLOSE to 1, this means there is a RELATIVELY HIGH correlation between salary and years of experience 
    - This HIGH CORRELATION, combined with the GOOD FIT of our Linear Regression Model (Trend Line) tells us that "Years of Experience" (X-Axis Value - Interval Value) will likely be a GOOD PREDICTOR VARIABLE for "Salary" (Y-Axis Value - Count)
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  