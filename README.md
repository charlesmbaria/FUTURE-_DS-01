**1. Problem Definition**

The Titanic disaster is one of history's most infamous shipwrecks. Approximately 1502 out of 2224 passengers and crew lost their lives.

**2. Project Purpose**

**The purpose of this project is to:**

1.	Gain insights into the Titanic dataset.
2.	Identify key features influencing survival rates.
3.	Prepare data for predictive modeling.
4.	Communicate findings effectively to stakeholders.

**3. Dataset Description**

The Titanic dataset contains demographic and travel information of passengers. It is typically provided by Kaggle or other public repositories and contains the following columns:

•	PassengerId: Unique ID for each passenger.

•	Survived: Survival indicator (0 = No, 1 = Yes).

•	Pclass: Passenger class (1st, 2nd, 3rd).

•	Name: Passenger's name.

•	Sex: Gender of the passenger.

•	Age: Age of the passenger.

•	SibSp: Number of siblings/spouses aboard.

•	Parch: Number of parents/children aboard.


•	Ticket: Ticket number.

•	Fare: Ticket price.

•	Cabin: Cabin number.

•	Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
________________________________________

**4. Methods Used**

The analysis was divided into the following steps:

**1.	Data Cleaning:**

o	Handled missing values in the Age and Cabin.

o	Imputed Age using the median.

o	Dropped Cabin due to a high percentage of missing data.


**2.	Exploratory Data Analysis (EDA):**

o	Univariate Analysis: Examined individual features using histograms and bar charts.

o	Bivariate Analysis: Explored relationships between survival and other variables using heatmaps and boxplots.

o	Multivariate Analysis: Analyzed the relationship between survival and other multiple variables using bar graphs 


**3.	Visualization Tools:**

o	Used libraries like matplotlib, seaborn, and pandas for data visualization to identify patterns and trends.

________________________________________

**5. Findings**


**•	Survival Rates:**

There is a relationship between PClass, Sex and Survival

**Key Features Influencing Survival:**

o	Gender: Females were more likely to survive.

o	Class: First-class passengers had higher survival rates.

o	Age: Children (age < 16) had a better chance of survival.

o	Fare: Higher fares were associated with increased survival probabilities.
________________________________________

**6. Key Takeaways**


•	Survival was heavily influenced by socio-economic factors (e.g., class, fare) and demographics (e.g., age, gender).

•	Class and fare indicate a possible prioritization of wealthy passengers during evacuation.

•	Data cleaning and visualization significantly improved the dataset's usability for further analysis.
________________________________________

**7. Tools and Libraries**

•	Python: pandas, numpy, matplotlib, seaborn.

