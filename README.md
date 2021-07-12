# Insurance-cost-prediction

https://www.kaggle.com/mirichoi0218/insurance link of the dataset

Life is full of uncertainty. People, households, companies, properties, and property are exposed to 
different risks. The world of finance has developed numerous products to shield individuals and 
organizations from these risks by using financial capital to reimburse them. insurance is, therefore, a 
policy that decreases or removes loss costs incurred by various risks.
Therefore, it becomes important for the companies of insurance to be sufficiently precise to 
measure or quantify the amount covered by this policy and the insurance charges which must be 
paid for it. various variables estimate these charges. each factor of these is important. if any factor is 
omitted when the amounts are computed, the policy changes overall. it is therefore critical that 
these tasks are performed with high accuracy to calculate the insurance premium

<b> Hence the Idea is to build an algorithm that can predict the charges as accurately as possible that 
an insurance company may have to pay in case of a mishappening. </b>


(prediction.ipynb contains)

• In this analysis, I want to analyse the relationship between insurance cost (target variable) and 
six independent variables based on (age, BMI, child number, individual living area, or sex and 
whether the customer is a smoking person). on the basis of a regression.
• To build the regression model that predicts the charges paid by insurance companies. I will
 analyse the performance of the regression model by the following three metrics:
− Mean Squared Error (MSE).
− Root Mean Squared Error (RMSE).
− Mean Absolute Error (MAE)

Web Framework:

Flask is used to provide the web framework to the model 

Deploying the model:

Heroku is used to deploy the project

<b>Steps to deploy on heroku:-</b>

Install the heroku CLI

Use Git to clone source code to your local machine

     $ heroku git:clone -a name_of_the_model

Deploy your changes
 
    $ git add .

    $ git commit -am "make it better"
  
    $ git push heroku master

Note: you will also need a Procfile and requirements text

