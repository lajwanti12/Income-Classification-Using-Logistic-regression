# Income-Classification-Using-Logistic-regression
Multi-class Logistic Regression
Similar principles to those of binary classification are used in multiclass classification implementation. As you are aware, binary categorization involves resolving a yes-or-no dilemma. A person has heart disease if the output is 1 and does not have heart disease if the output is 0.
We have more than two classes when we use multi-class classification. Only one class can be assigned to each sample. As an illustration, consider classifying data using attributes taken from a set of income, which can either be of a 150, 50, or 100.
Dataset 
Dataset which is used here is named as Income dataset which is consist of 250 rows and 15 columns. There are 14 features and 1 target value
Features are given below
•	Age: Describes the age of individuals. Continuous.
•	Workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
•	Final weight: Continuous.
•	Education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
•	Education-num: Number of years spent in education. Continuous.
•	Marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
•	Occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
•	Relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
•	Race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
•	Sex: Female, Male.
•	Capital-gain: Continuous.
•	Capital-loss: Continuous.
•	Hours-per-week: Continuous.
•	Native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc.), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
And Target is 
•	Income: >50K, <=50K, >100.
Defining the Problem Statement
The information in the data is anonymous and includes things like age, profession, education, working class, etc. The objective is to train a binary classifier to predict an individual's income, which can take one of three forms: ">50K," "50K," or ">100." The dataset consists of 250 instances and 14 characteristics. A decent mix of categories, numerical, and missing values may be found in the data.
Implementation of Multiclass Logistic Regression
•	Importing important libraries 
•	Loading dataset from drive
•	Exploratory Data Analysis
•	Dividing the model into train, validation, and test sets.
•	Model Implementation
•	Training the model
•	Regularized the model if needed
•	Fine tuning the model
•	plot the model results with normalization and without normalization.
