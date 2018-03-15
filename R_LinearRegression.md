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

