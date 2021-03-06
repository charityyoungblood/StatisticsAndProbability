<!-- Correlation Coefficient --> 

## When creating a Scatterplot in R - Complete Steps in R_LinearRegression.md FIRST ##

1. CORRELATION COEFFICIENT: denoted by "r", this is a numerical measure that measures the STRENGTH and DIRECTION of a Linear Relationship between two QUANTITATIVE VARIABLES
    - The value of "r" ranges from -1 to 1, "r" CANNOT take values outside of this range 
    - The sign of "r" either positive or negative, indicates the DIRECTION of the Relationship 
    - Negative values of "r" indicate a "Negative Relationship" 
    - Positive values of "r" indicate a "Positive Relationship" 
    - "r" indicates the "Strength" of the Linear Relationship 
    - Values of "r" that are CLOSER TO ZERO, positive or negative, indicate a WEAK LINEAR RELATIONSHIP 
      - The closer "r" is to zero, the WEAKER the relationship 
      - If "r" is EQUAL TO zero, which is extremely rare, this indicates NO LINEAR RELATIONSHIP 
    - Values of "r" close to -1 indicate a Strong NEGATIVE LINEAR RELATIONSHIP; the CLOSER "r" is to -1, the STRONGER the Linear Relationship
    - Values of "r" close to 1 indicate a Strong POSITIVE LINEAR RELATIONSHIP; the CLOSER "r" is to 1, the STRONGER the Linear Relationship
    - The CORRELATION COEFFICIENT can ONLY be interpreted as the measure of Strength of a Linear Relationship - we need the Scatterplot to VERIFY that the relationship indeed looks Linear
    
2. Properties of The Correlation Coefficient 
    - If we change the units of measurement (i.e. changing "feet" to "meters") of the explanatory variable and/or the response variable, the change has NO EFFECT on the correlation (r) 
    - The CORRELATION COEFFICIENT is USELESS for assessing the Strength of any type of NON-LINEAR relationships - this INCLUDES "Curvilinear" relationships 
  ## IMPORTANT ### >>> ALWAYS LOOK AT THE DATA IN THE SCATTERPLOT - As there may be a STRONG, NON-LINEAR Relationship that "r" does NOT indicate #####
    - The Correlation ("r") is HEAVILY INFLUENCED by Outliers; the way in which the outlier influences the correlation depends upon whether or not the outlier is consistent with the pattern of the linear relationship 
    - If the Outlier IS consistent with the pattern of the Linear Relationship, i.e. the Scatterplot displays a "Positive" Linear relationship with 2 Outliers at the very top, REMOVING the Outlier will cause the CORRELATION COEFFICIENT to DECREASE 
    - If the Outlier is NOT consistent with the pattern of the Linear Relationship, REMOVING the Outlier will cause the CORRELATION COEFFICIENT to INCREASE 
    
3. Example of Interpretating Correlation Coefficient 
  - Description: Report the correlation between gestation and longevity and comment on the strength and direction of the relationship. Interpret your findings in context.
 ## Response: The correlation is r = 0.663. The relationship is moderately strong and positive. The positive direction of the relationship means that, in general, animals that have a longer lifespan also have longer pregnancies. The moderate strength of the relationship tells us that there is some considerable variation around the relationship's linear form.
 
 4. Drawbacks to Correlation Coefficient
  - The Correlation Coefficient is useful for telling us whether two variables are correlated HOWEVER, it does NOT describe the nature of the relationship between the two variables 
  - "Lines" are VERY USEFUL for describing relationships between two variables 
  - The Correlation Coefficient ALONE is NOT sufficient to determine whether a relationship is Linear or not; The Correlation Coefficient serves as a SUPPLEMENT to the Scatterplot
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  