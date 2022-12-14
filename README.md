# Linear Regression

**Linear regression** is a statistical way of measuring the relationship between a response variable and one or more exploratory variables by fitting a line through observed data. 

The best way to understand linear regression is through an example. Let's pretend that you're the CEO of an exciting new company, and like all CEO's, you're interested in seeing if you can improve the product sales. 

You have access to marketing spend by channels and corresponding sales. [Dataset](https://github.com/balu12don/Linear-Regression/blob/0352276304a3107c15ca275bfa082a7666c15045/marketing_data.csv).

#### Objective: 
Predict impact of spenditure across various marketing channels on product sales using a linear regression model.

#### Building the model: 
To build a [linear regression model](https://github.com/balu12don/Linear-Regression/blob/f7d12d3a06ef20cafd72f5419862084c578dc64d/Linear_Regression.ipynb) in python, we’ll follow the following steps:

* Understand and visualize the data
* Fit the regression model
* Analyze test results using statistical methods
* Evaluate linear regression assumptions

#### How to use the notebook: 
* Download the ipynb file
* Download "marketing_data" dataset in the same folder
* Run the notebook to fit the multi-linear regression model

#### Conclusion:

[Regression model](https://github.com/balu12don/Linear-Regression/blob/f7d12d3a06ef20cafd72f5419862084c578dc64d/Linear_Regression.ipynb) suggests the following best fit line

$$ Sales = 4.6 + 0.05*(TV) + 0.1*(Radio) $$

With this model, we can
* Predict sales given the marketing spenditure by channel
* Estimate impact of each marketing channel on product sales
