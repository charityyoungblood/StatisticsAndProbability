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

## Histograms in R ## 
  - The default X-Axis label is the VARIABLE NAME (i.e. Age)
  - The default Y-Axis label is the COUNT 
  - A good graphic (i.e. pie chart, histogram, etc) is a "well-labeled graphic"
  - You can modify the settings of your graphic with the below R commands
    
6. R Commands - To Create a Histogram 
  - After loading file and opening in R > enter data frame name (lower case), enter the following: 
      hist(DataFrameName$ColumnTitle)
  - To add an X-axis label (label for Interval values) and remove the title of the histogram, use the following code:
      hist(DataFrameName$ColumnTitle, xlab="IntervalValuesTitle", main="")
  - To modify the X-axis and Y-axis label and the title use the following code:
      hist(DataFrameName$ColumnTitle, xlab="IntervalValuesTitle", ylab="CountTitle", main="HistogramTitle")

7. R Commands - Modifying the Number of Bins 
  - REMEMBER "bins" are created by dividing the entire range of values into a series of intervals, meaning EACH INTERVAL SET is a "bin" (21-30 bin, 31-40 bin, etc)
  - R uses an algorithm to determine the optimal number of bins based on the data you pass in - but in some cases you may want to modify the number of bins yourself 
  - We do this by adding "parameter breaks" in the hist() command; the example below shows 8 breaks 
    hist(actor_age$Age, breaks=8, xlab="Age of Best Actor Oscar Winners (1970-2013)", main="")












































