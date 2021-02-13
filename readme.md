# Pisa 2012 Data Exploration

## Dataset

The data consists of information regarding 485,490 data entries. Each row represents a student performance entry. 
The student performances are splitted into 3 main categories: mathematics (PV1MATH to PV5MATH), Reading (PV1READ to PV5READ) 
and Science (PV1SCIE to PV5SCIE).
Besides the performance variables, the dataset consists of various other variables such as living country, 
parent qualifications, possessions, subjective norms, experiences and many more.
The dataset contains 636 columns.
Explanations and details to the different features of the dataset can be found in the PISA TECHNICAL REPORT 
(https://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf). 
Additional information can be found in the PISA Data Analysis Manual (https://www.oecd-ilibrary.org/docserver/9789264056275-7-en.pdf?expires=1593104863&id=id&accname=guest&checksum=7823743D615762D34BB2F868F3193900)

## Summary of Findings

My main target was to gain some insights into the mathematics scores. Is there a feature 
with a positive relationship to mathematics scores? 
During the exploration, I analysed 11 features and their relationships with the mathematics scores.
I found that there is a strong negative relationship between mathematics scores and mathematics
anxiety. Further analysis of both features with the 10 remaining features revealed that
the educational level of the parents and the number of books at home have a positive 
relationship to the mathematics scores and mathematics anxiety.
The premise for a better mathematics score is that both variables (higher parental 
educational level and number of books at home) are given. If separated, the positive
relationship to the mathematics scores might not be given.


## Key Insights for Presentation

For the presentation, I present the relationships between the 4 features:
mathematics scores, mathematics anxiety, parental educational level and the number of books at home.
I start by introducing the mathematics scores variable, which is normaly distributed.
Afterwards, I introduce the numeric variable mathematics anxiety, which can be 
broken down into 5 categorical variables. For that, I use violinplots to compare the 
mathematics scores to the five different statements belonging to mathematics anxiety.
Next, I present a comparison of the parental educational level to the average mathematics scores by
using a pointplot.
The last variable, the number of books at home, is compared to the mathematics scores using a boxplot.
Finally, I present two pointplots visualizations, presenting the relationsship between respectively 3 
variables: 
- mathematics scores, parental educational level and number of books at home
- mathematics anxiety, parental educational level and number of books at home
