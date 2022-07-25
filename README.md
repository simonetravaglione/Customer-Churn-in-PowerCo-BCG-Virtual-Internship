# Customer-Churn-in-PowerCo-BCG-Virtual-Internship

## My Submission

### 1. Situation
My client - PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers.

### 2. Complication
Significant churn problem

Driven by power-liberalization of the energy market in Europe Problem is largest in the SME segment

### 3. Hypothesis
One of the hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it is possible to predict customers likely to churn using a predictive model. The client also wants to try a discounting strategy, with the head of the SME division suggesting that offering customers at high propensity to churn a 20% discount might be effective.

### 4.Results
#### 4.1 Model Development
I  built a Logistic Regression, Random Forest,  Gradient Boosting and XGBC Classifier model.
#### 4.2 Take aways
Churn is not due to price sensitivity alone. In fact, price does not work alone, it is affected by other variables. Similar to other variables that influences churn, they don't work alone, they are influenced by other variables.
Churn is driven mostly by:

• Forecasted power price for 1st period
• Electricity consumption of the past 12 months
• Price of energy for the 2nd period
• Subscribed power
• Electricity campaign the customer first subscribed to
• Forecasted bill of meter rental for the next 12 months.

The optimal cutoff for price discount is 0.26%.We might think that the cutoff is costly and that it might be more advantageous to focus on the most profitable consumers. However, in this case, it doesn't make sense to prioritize large-revenue customers, since the overall revenue delta is much lower than when targeting everyone. A strategic business possibility could be to intensify the customer relationship, add key account managers or other interventions that incur costs depending on the number of targeted customers. In this case, it may be advantageous to target only a subset of customers to save on these costs.

### 5.My Recommendation to the client
• Track user behaviour to understand just before who are the users are about to churn
• Build Personalisation. Not only about recommendations for new products, but also referred to the pricing front and the user experience
• Re-define Customer Journey. Create a user journey which has discounts or gifts when a customer enters the churn probable bucket
• Resolving customers' problems quickly and effectively is the most effective way to make them loyalty. He can trust you in his time of need and this pays more than a discount

