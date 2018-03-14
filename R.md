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
  - To create a TABLE, enter the following:
    t = table(DataFrameName$ColumnTitle)
  - To see the PROPORTION of the total in EACH category, enter the following:
    prop = prop.table(t);prop
  - To see the PERCENTAGE of the total in each category, enter the following:
    percent = prop.table(t);percent
    
5. R Commands - To Create a Pie Chart 
  - After you've entered the above commands to create the Frequency Distribution Table
    Enter the following: pie(t)
  - Here you can modify Pie Chart Labels, with the following commands:
    - pf = round(percent,1);pf >> this rounds our values to 1 decimal place
    - lbl = paste(c("No difference","Opposite sex","Same sex"),pf,"%",sep=" ");lbl >> the ensures our labels will include category names and percent for each section of the pie chart 
    - pie(t,label=lbl) >> this creates the updated pie chart 
    
6. R Commands - To Create a Histogram 
  - After loading file and opening in R > enter data frame name (lower case), enter the following: 
      hist(DataFrameName$ColumnTitle)
  - To add an X-axis label (label for Interval values) and remove the title of the histogram, use the following code:
      hist(DataFrameName$ColumnTitle, xlab="HistogramTitle", main="")
  - To modify the X-axis and Y-axis label and the title use the following code:
      hist(DataFrameName$ColumnTitle, xlab="Age of Best Actor Oscar Winners (1970-2013)", ylab="Number of Actors", main="Best Actor Oscar Winners Ages")




