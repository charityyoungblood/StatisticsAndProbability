<!-- Five Number Summary --> 

1. The Five Number Summary 
  - The Five Number Summary provides a COMPLETE numerical description of a distribution 
  - The combination of Min, Q1, M (median), Q3, and Max is called the "Five Number Summary" 
  - It provides a quick numerical description of both the center and spread of a distribution 
  
2. R Command for Five Number Summary: 
    summary(dataFrameName$ColumnTitle)
    
3. Example
 
    min = 85, Q1 = 130, Median = 145, Q3 = 150, Max = 250
    
    IQR = Q3 - Q1 
    Q1 - 1.5(IQR)
    Q3 + 1.5(IQR)
   
    IQR = 150 - 130 = 20 
    Below 130 - (1.5 * 20) = Below 100
    Above 150 + (1.5 * 20) = Above 180
