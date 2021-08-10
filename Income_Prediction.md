# Income Prediction

The project focuses on predicting the income range based on some parameters
which are not based on skills rather than background and environment Even though 
the person is working the results can provide a lot of insights.

​
Whoever apply for a job or the new candidates or even any person who is 
curious to know the range of income possibilities regardless of the skills did not get the idea of the 
same. The provision revolves around the skills and education. Going through the data present 
globally its observed that there is some kind of pattern in the income. Using this pattern, a person 
can know the possible range of income one may expect. The income may or may not match the actual income but its interesting to provide insights over the possibilities using the patterns already 
observed.

## About the Dataset:

Using the dataset with around 33000 inputs from around the global with about 14 
parameters. Using these inputs, the model is trained to predict the possible income ranges. After 
some cleaning the model is trained. The insights are drawn and pulled up to understand how the 
pattern works.
​
The dataset is present in the [repository](https://github.com/Sara-cos/Income_Prediction).

### Attributes of the Dataset:

* Age: Describes the age of individuals. Continuous.

* Workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

* fnlwgt: Continuous.

* education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

* education-num: Number of years spent in education. Continuous.

* marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

* occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

* relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

* race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

* sex: Female, Male.

* capital-gain: Continuous.

* capital-loss: Continuous.

* hours-per-week: Continuous.

* native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

* salary: >50K,<=50K

### lets take a look at first 5 rows of our dataset:


```
data.head()
```
![](https://github.com/Sara-cos/Intern-Work/blob/main/int-ml-5/S/Images/Dataset.png)
