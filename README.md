### Date created
06/11/20

### Project Title
Use of Multiple Imputation by Chained Equations (MICE) R package to impute missing data obtained from a Chicago bike share program

### Description
This project used three different methods to determine how the Multiple Imputation by Chained Equation (MICE) R package performed when imputing sex and age. The approaches were: 1) ignore the extremes in age and see how sex and age is imputed, 2) set the extreme ages to missing and impute age and sex all at once, even though setting age to missing makes the data non-monotone, and 3) Perform sequential multiple imputation to satisfy monotonicity. Impute sex first and then impute age using imputed sex dataset. A subset of anonymized data from the Motivateco bike share program in Chicago was used to perform the analyses, which contained ~20% missing data for age and sex. To reduce computation time, three imputations were performed for each approach and pooled, resulting in one complete dataset for each approach. Each complete dataset was graphed using ggplot2 and analyzed to compare between approaches.

### Files used
#original file 
chicago.csv

#complete dataset obtained for approach 1
chi_complete_1.csv  

#complete dataset obtained from approach 2 
chi_complete_2.csv 

#first part of dataset for approach 3 
chi_complete_3.csv 

#second part of approach 3 and complete dataset for approach 3
chi_complete_4.csv 

### Credits <:3)~
#MICE github repository 
https://github.com/stefvanbuuren/mice.git

#More information on the MICE R package 
https://stefvanbuuren.name/mice/

#A wonderful and very useful book on MICE 
https://stefvanbuuren.name/fimd/


