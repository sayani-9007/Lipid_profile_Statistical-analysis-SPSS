# Lipid Profile Statistical Analysis using SPSS

## Overview

This project presents statistical analysis of lipid profile data using IBM SPSS Statistics.

## Statistical Methods

The following statistical methods were performed:

- Normality tests
- ANOVA
- Mann–Whitney U test
- Kruskal–Wallis test
- Correlation analysis
- Regression analysis

## Description
The dataset included the lipid profile of a total 149 patients where there were 65 males and 84 females. The following tests were performed on the dataset.

1.	 The variation in the level of cholesterol across the two genders were tested.
   
i.	The null hypothesis is "The Cholesterol level is same across the genders". 

ii.	The normality test was run and the Shapiro-wilk values were 0.023 for males and 0.074 for females, and the mean values for male was 149.09 and female it was 158.48, thus the non-parametric test for one dependent and other independent variables which is Mann-Whitney U test was performed.

iii.	The p-value was 0.177, which is >0.05, thus it retains the null hypothesis, the test statistics was found to be 3082.5. 

iv.	This shows there's no significant difference in the level of cholesterol between the two genders. 

2.	The variation in LDL level among three age groups.

i.	The ages were first recoded into three groups- "Below 40", "40-50" and "Above 50".

ii.	The null hypothesis is "The LDL level across the three age groups remain same". The normality test was performed showing the Shapiro-wilk values as 0.91 for below 40, 0.17 for 40-50 and <0.001 for above 50 age groups. Thus, the non-parametric test for one dependent and other grouping variable was performed called Kruskal-Wallis test.

iii.	The test statistics was 17.27 and the p-value was<0.001, which is <0.05, thus it rejects the null hypothesis. For further analysis, pairwise comparisons were done, the significant values were adjusted using Bonferroni corrections. The adjusted significant values are- For "Above 50 to 40-50" is 0.02 [<0.05], for "Above 50 to Below 40" it is 0.001 [<0.05] and for "40-50 to Below 40" it is 1 [>0.05]. From this data we can conclude that the difference in the level of LDL varies more significantly between the Above 50 and Below 40 age groups and varies lesser significantly between 40-50 and above 50 age groups, whereas it doesn't vary significantly between Below 40 and 40-50 age groups. 

iv.	Further, the mean values observed are- 108.86 [Below 40], 100.05 [40-50] and 79.83 [Above 50], this concludes that the level of LDL in the patients of above 50 age group is the least, and it is the highest for Below 40 age groups, whereas 40-50 age group lies in a moderate stage. 

v.	In the population of India, it is seen that the LDL level is below 40 age group is lower to that of the other two age groups according to ICMR-INDIAB studies. But in the data set, the scenario is quite opposite. The reasons might be as follows- 

a)	The patients of Below 40 age groups lead an unhealthy lifestyle. The reasons can be poor dietary habits, tobacco consumptions, genetic diseases, certain medications can spike LDL level at a younger age.

b)	The patients above 50 yrs have lower LDL levels. This might be due to proper sleep schedule, healthy dietary habits and more significantly consumption of medicines to lower LDL level. 



3.	Correlation between Triglycerides and patient age groups

i.	The ages were first recoded into three groups- "Below 40", "40-50" and "Above 50". And the missing values were cleaned before running the tests.

ii.	The null hypothesis is "The Triglycerides level and patients’’ age groups are highly correlated”.  The normality test was performed showing the Shapiro-wilk values as 0.092 for below 40, 0.832 for 40-50 and <0.001 for above 50 age groups. Thus, the non-parametric test for correlation was performed called Spearman’s correlation test.

iii.	The total no. of patients in the dataset is 147. The analysis shows the correlation coefficient as ‘-0.147’ which signifies a weak correlation. Also, the negative value shows that the correlation is negative i.e. if one value increases, the other will decrease.

iv.	The p-value is 0.076; thus, it is statistically non-significant. Therefore, it rejects the null hypothesis.

## Tools Used

- IBM SPSS Statistics
- Microsoft Excel

## Objective

The objective of this analysis is to investigate relationships and differences within lipid profile data using appropriate statistical methods.

## Project Status

Completed statistical analysis and interpretation.
