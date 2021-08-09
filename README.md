# Travel Package Purchase Prediction


Following task were carried out

- Perform an Exploratory Data Analysis on the data.
- Missing value & outlier detection
- Illustrate the insights based on EDA
- Data Pre-processing
- Model building - Decision Trees, Random Forest, Bagging, Adaboost, Gradient Boost,XGBoost
- Hyperparamter tuning  for  Random Forest, Bagging, Adaboost, Gradient Boost,XGBoost
- Model comparision
- Actionable Insights & Recommendations.

For detailed notebook click here

# Context
"Visit with us". company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information.The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being.However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

We need to analyze the customers' data and information to provide recommendations to the Policy Maker and Marketing Team and also build a model to predict the potential customer who is going to purchase the newly introduced travel package.


# Business Recommendations & Insights
I have been able to build a predictive model:

a) that the company can deploy to identify customers who will be interested in purchasing the Travel package.

b) that the company can use to find the key factors that will have an impact on a customer taking a product or not.

- Most important features that have an impact on Product taken: `Desgination, Passport,TierCity,Martialstatus,occupation`
- Customers with Designation as Executive should be the target customers for the company .Customers who have passport and are from tier 3 city and are single or unmarried, have large business such customers have higher chances of taking new package.
- Customers monthly income in range of 15000- 25000, and age range 15-30, prefer 5 star properties also have higher chances of taking new package based on EDA.
- Based on EDA ,Factors from customer interaction data which can help in increasing the chances of the customer buying the travel package are:
- Having a higher duration of pitch by salesman to the customer.
- Getting a PitchSatisfactionScore of 3 or 5.
- Having multiple follow ups with the customers.
- Company should help and promote customers to get a passport , as we see having a passport increases the chances of customer accepting a package.
- Mostly Single customers are accpeting a package , reason may be married couples might has kids , provding a property , with child care services can get married couples to accept the product.
