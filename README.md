# Analyzing Factors Influencing Income and Developing a Predictive Model for Social Policy Planning
## Context
DeltaSquare is an NGO that works with the Government on matters of social policy to bring about a change in the lives of underprivileged sections of society. 
They are tasked with coming up with a policy framework by looking at the data government got from WHO. 
You as a data scientist at DeltaSquare are tasked with solving this problem and sharing a proposal for the government

## Objective
The dataset aims to answer the following key questions:
What are the different factors that influence the income of an individual?
Is there a good predictive model for income that exists? What does the performance assessment look like for such a model?

## Data Dictionary
age: continuous - age of a Person
workclass: Where do a person works - categorical -Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
fnlwgt: This weight is assigned by the Current Population Survey (CPS). People with similar demographic characteristics should have similar weights since it is a feature aimed to allocate similar weights to people with similar demographic characteristics - continuous
education: Degree the person has - Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
education-num: no. of years a person studied - continuous.
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
sex: Female, Male.
capital-gain: Investment gain of the person other than salary - continuous
capital-loss: Loss from investments - continuous
hours-per-week: No. of hours a person works - continuous.
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, - - Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
salary: >50K, <=50K (dependent variable, the salary is in Dollars per year)

## Representation of the steps taken
``` mermaid
graph TD
    A[Data Analysis Initiated]
    A -->|1. Define research objectives| B(Gather WHO dataset)
    B -->|2. Gather WHO dataset| C(Preprocess data)
    C -->|3. Preprocess data| D(Exploratory Data Analysis)
    D -->|4. Analyze income factors| E(Identify influential factors)
    E -->|5. Identify influential factors| F(Build predictive model)
    F -->|6. Train and evaluate model| G(Performance assessment)
    G -->|7. Assess model performance| H(Generate insights)
    H -->|8. Generate insights| I(Create policy framework)
    
    
   ```
