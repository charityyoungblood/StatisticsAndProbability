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