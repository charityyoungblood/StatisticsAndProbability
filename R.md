<!-- R: Programming Language for Statistics -->

1. R has an interface similar to Terminal 

2. To add your Data file to R 
  - Download and save to directory
  - Open file in R, by either clicking the file directly, or going to "File" > Open Document 
  - Once in R, to view Data file contents > enter file name (without file extension)
  
3. To Extract (View) a Specific Variable Data Frame 
  ## A Data Frame is the title of your data file in lower case ##
  - Insert $ to identify the desired variable (column title) within the data frame
  - We use the name of our file with the $ followed by the Column Name
  - nameOfDataFile$ColumnName
  
4. R Commands - To Create a Frequency Distribution Table 
  - After loading file and opening in R > enter data frame name (lower case)
  - Enter the following: t = table(DataFrameName$ColumnTitle)
  - To see the PROPORTION of the total in EACH category, enter the following:
    prop = prop.table(t);prop
  - To see the PERCENTAGE of the total in each category, enter the following:
    percent = prop.table(t);percent