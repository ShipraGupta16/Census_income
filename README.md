# Census Income Dataset

#### Data source: https://www.kaggle.com/datasets/tawfikelmetwally/census-income-dataset

### Questions:
Census Income data from various countries. <br>
Q1. How is education distributed among different racial groups? <br>
Q2. How does income correlate with different variables like education, work class, occupation, race, marital status, and sex? <br>
Q3. Explore the relationship between Age and the number of hours worked per week. <br>
Q4. Draw a correlation between income, age, hours per week, and education number. <br>
Q5. Is there any correlation between number of hours worked and income worked? <br>
Q6. What is the median age of people with >50k income? <br>
Q7. Is there any difference in the pattern of analysis US and other countries? <br>


Income distribution by education <br>

Based on education, this plot tells us that people who earned high school graduate, some college and bachelor’s degrees (top 3) earned <=50k income. Higher education does show higher income.
However, people who earned a Doctorate and Prof-school earned >50k income.
There are less number of people who earned with 5-6th, 10th, 1st-4th, preschool, and 12th class earned <=50k. <br>

Income distribution by Workclass <br>

People who worked in the private sector have the highest regardless of earning <=50k or >50k.
Other high categories are self-employed-not inc, Unknown sector, State-gov, local-gov, self-emp-inc and federal-gov sectors.
There is no data available in the Without-pay and Never-worked categories. <br>

Income distribution by Occupation <br>

A majority of people have <50k income based on sector.
The most commonly occurring occupations in both income categories are executive-managerial and professional-specialty. Except for the armed forces and private-house-serve sector <= 50k are high in all occupation sectors. <br>

Income distribution by Race <br>

White represents a higher income slab than the rest.

Income distribution by Marital status <br>

The people who are never married represent the highest and have <=50k income
The people who are married-civilian-spouse represent the second highest have <=50k income. They also have a high income with >50k which may conclude the combined salary of the spouse. <br>

Income distribution by Sex <br>

Males have more earnings than females.
Male earns <=50k than >50k.
Female earns <=50k than >50k.


#### Limitations in this dataset <br>
* Little data on capital gains and loss to be analysed with income.
* Couldn't perform median or average and replace in any column as they represent the country dataset. It is possible when data is at state level. <br>


### Conclusion <br>
* Similar trends of high private jobs, occupation and income range in US population and other countries.
* Male population having more income than females.
* The median age of >50k income is 45 years.
* White population has high frequency of some college, HS-grad and Bachelors degree.
* Not much difference in pattern of analysis between US and other countries. It is noticeable to say that 80% of world census data is coming from the US.