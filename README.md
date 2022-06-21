# Titanic-Survival
Using logistic regression to analyze what sorts of people were likely to survive the titanic 
# Task
The sinking of the Titanic on April 15th, 1912 is one of the most tragic tragedies in history. The Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers. The numbers of survivors were low due to the lack of lifeboats for all passengers and crew. Some passengers were more likely to survive than others, such as women, children, and upper-class. This case study analyzes what sorts of people were likely to survive this tragedy. The dataset includes the following:

•	Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

•	Sex: Sex

•	Age: Age in years

•	Sibsp: # of siblings / spouses aboard the Titanic

•	Parch: # of parents / children aboard the Titanic

•	Ticket: Ticket number

•	Fare: Passenger fare

•	Cabin: Cabin number

•	Embarked: Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton

•	Target class: Survived: Survival (0 = No, 1 = Yes)
# Methods

•	Get data from .csv

•	Visualization
   
   o	Visualization with seaborn ad matplotlib

•	Model training
   
   o	Logistic regression
# Result
Using Logistics Regression. The result is shown in the table below:

Survived: did not survive: 0, survived: 1

|	          |precision|recall|f1-score|support|
|-----------|---------|------|--------|-------|
|0	        |0.85     |0.85  |0.85    |117    |
|1	        |0.71     |0.73  |0.72    |62     |
|accuracy   |-	      |-	   |0.80	  |179    |
|macro avg  |0.78     |0.79  |0.78	  |179    |
|weighted avg|0.81    |0.80  |0.80	  |179    |
