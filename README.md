# CPSC4800-Titanic-Analysis

## Which directory contains what
src: I uploaded source code of jupyter notebook in ipynb format
result: I put results of the titanic analysis with plots
doc: This directory is reserve for additional documents
data: There is original csv file I worked with

## How users can get started with the project
  #### Hypothesis 1: the survival rate is associated to the class of passenger
  I categorized all dadta by Pclass and cointed both the number of survivlas in each class and the total number of passengers in each         class. Then, I calculated the survival rate. Since the Pclass is a categorical variable and survival rate is a numerical variable, Bar     graph with Pcalss on x axis is the most proper plot to show data.
  
  #### Hypothesis 2: the survival rate is associated to the gender
  Similarly to hypothesis 1, I divided data into two categories which are 'female' and 'male' and derived the survival rate for each sub     categories. To compare and show difference between sub categories clearly, I used bar graph.

  #### Hypothesis 3: the survival rate is associated to the age
  'Age' and 'survival rate' are numerical variables. However, since 'age' data is spread widely, I made age class by 10 years and             transformed 'Age' into a categorical variable. With age class on X axis and the survival rate for each age class on Y axis, bar graph       indicates 'Age' and 'the survival rate' don't have strong association. Hence, I uncategoriezed 'Age' columns tried correlation             coefficient analysis with all age data and the survival rate to read if there is linear relation.
