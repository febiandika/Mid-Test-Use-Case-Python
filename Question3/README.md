# Titanic Dataset
## by Febi Andika Dani Fajar Suryawan

### Background  
<br>
The dataset contains data for 887 of the real Titanic passengers. Each row represents one person. The columns describe different attributes about the person including whether they survived (S), their age (A), their passenger-class (C), their sex (G) and the fare they paid (X). The table below shows the Data Dictionary.

### Objective
<br>
Create a python script to explore the titanic passenger data. The script must answer the questions below.
<br>
I. What is the dimension (col, row) of the data frame?
<br>
II. How to know data type of each variable?
<br>
III. How many passengers survived (Survived=1) and not-survived (Survived=0)?
<br>
IV. How to drop column ‘Name’ from the data frame?
<br>
V. Add one new column called ‘family’ to represent number of family-member aboard (hint:
family = sibsp + parch)
<br>
VI. As shown, columns ‘Age’ contains missing values. Please add new column named
‘Age_miss’ to indicate whether Age is missing or not (Age_miss = ‘YES’ for missing value and
‘NO’ for non-missing value).
<br>
VII. Please fill Age missing value with means of existing Age values
<br>
VIII. What is the maximum passenger Age who survived from the tragedy?
<br>
IX. How many passengers survived from each ‘PClass’?
<br>
X. How to randomly split the data frame into 2 parts (titanic1 and titanic2) with proportion of
0.7 for tttanic1 and 0.3 for titanic2 ?
