In this notebook , I'll be experimenting with Nepal Population Data by sex and age group(2011-12).
This dataset is  taken  from opennepal [here](https://github.com/opennepal/odp-census/blob/master/Population%20by%20sex%20and%20age-group/data.csv)

### Data Cleaning
1. If we observe the csv files provided at opennepal, the values were comma separated but between two columns (Year (AD) and Sex) there was trailing space. The trailing space was removed using single regular expression substitution with regex pattern <b>*(,)\s+(\w)*</b>
and replace string <b>*\1\2*</b> <br>
 I used notepad++ for this purpose.
 
 
