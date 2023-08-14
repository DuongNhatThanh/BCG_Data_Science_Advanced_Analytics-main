# BCG_Data_Science_Advanced_Analytics

<img width="700" alt="image" src="https://github.com/DDDDNNNNNThanh/BCG_Data_Science_Advanced_Analytics/assets/110702728/8e99a8f6-c6aa-4ce6-8f9c-f12fe3f4d4c1">

## Task 1 - Business Understanding & Hypothesis Framing

### Business Understanding & Hypothesis Framing

#### Problem
PowerCo is a prominent provider of gas and electricity services catering to corporate, SME (Small & Medium Enterprise), and residential customers. The liberalization of the energy market in Europe has resulted in substantial customer turnover, particularly within the SME segment. To address this issue, PowerCo has partnered with BCG to identify the underlying reasons behind the churn among SME customers.

One plausible hypothesis is that changes in pricing significantly influence customer churn. Therefore, it would be beneficial to determine which customers are more or less likely to switch to a competitor given their current pricing. Developing an effective predictive model would assist in this endeavor.

Additionally, for customers who are at risk of churning, offering them a discount could serve as an incentive to remain with our client. The head of the SME division is contemplating implementing a 20% discount, a substantial reduction aimed at dissuading almost any customer from switching, particularly those who prioritize price as a deciding factor.

Following an initial team meeting led by the Associate Director (AD), various hypotheses were discussed, including the potential impact of price sensitivity on churn. Based on these discussions, you have been tasked with further investigating the hypothesis that customer churn is driven by their sensitivity to pricing.

Your AD has requested an email outlining your thoughts on how the team should proceed with testing this hypothesis.

The client intends to utilize the predictive model on the first working day of each month to identify the customers to whom the 20% discount should be offered.

#### Tasks
Formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis. Communicate your thoughts and findings in an email to your AD, focusing on the data that you would need from the client and the analytical models you would use to test such a hypothesis.

## Task 2 

### Exploratory Data Analysis
The BCG project team recognizes the potential of constructing a churn model to determine if price sensitivity is the primary factor driving customer churn. The client has provided a dataset, and the Assistant Director (AD) requests that you conduct exploratory data analysis.

The dataset consists of the following information:
* Historical customer data: This includes details such as customer usage, sign-up date, forecasted usage, and more.
* Historical pricing data: It encompasses both variable and fixed pricing information, among other relevant data points.
* Churn indicator: This indicates whether each customer has churned or remains active.
  
#### Sub-Task 1:

Perform some exploratory data analysis. Look into the data types, data statistics, specific parameters, and variable distributions. This first subtask is for you to gain a holistic understanding of the dataset.

#### Sub-Task 2:

Verify the hypothesis of price sensitivity being to some extent correlated with churn. It is up to you to define price sensitivity and calculate it.

#### Sub-Task 3:

Prepare a half-page summary or slide of key findings and add some suggestions for data augmentation – which other sources of data should the client provide you with and which open source datasets might be useful?

## Task 3 

### Feature Engineering & Modelling

The team now has a good understanding of the data and feels confident to use the data to further understand the business problem. The team now needs to brainstorm and build out features to uncover signals in the data that could inform the churn model.

Feature engineering is one of the keys to unlocking predictive insight through mathematical modeling. Based on the data that is available and was cleaned, identify what you think could be drivers of churn for our client and build those features to later use in your model.

First focus on building on top of the feature that your colleague has already investigated: “the difference between off-peak prices in December and January the preceding year”. After this, if you have time, feel free to get creative with making any other features that you feel are worthwhile.

Once you have a set of features, you must train a Random Forest classifier to predict customer churn and evaluate the performance of the model with suitable evaluation metrics. Be rigorous with your approach and give full justification for any decisions made by yourself as the intern data scientist.

Recall that the hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it would be possible to predict customers likely to churn using a predictive model.

If you’re eager to go the extra mile for the client, when you have a trained predictive model, remember to investigate the client’s proposed discounting strategy, with the head of the SME division suggesting that offering customers at high propensity to churn a 20% discount might be effective.

Build your models and test them while keeping in mind you would need data to prove/disprove the hypotheses, as well as to test the effect of a 20% discount on customers at high propensity to churn.

#### Sub-Task 1

This feature is “the difference between off-peak prices in December and January the preceding year”.

#### Sub-Task 2

Train a Random Forest classifier and to evaluate the results in an appropriate manner. We would also like you to document the advantages and disadvantages of using a Random Forest for this use case.

Ensure you’re able to explain the performance of your model, where did the model underperform? Why did you choose the evaluation metrics that you used? Please elaborate on your choices. Document the advantages and disadvantages of using the Random Forest for this use case. Do you think that the model performance is satisfactory? Give justification for your answer.

## Task 4 

### Findings & Recommendations

Develop an abstract slide synthesizing all the findings from the project so far, keeping in mind that this will be for the key stakeholders meeting which the Head of the SME division, as well as other various stakeholders, will be attending, including:

* What is the most important number or metric to share with the client?
* What impact would the model have on the client’s bottom line?


