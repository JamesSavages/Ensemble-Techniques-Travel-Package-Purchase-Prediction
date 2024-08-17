# Ensemble-Techniques-Travel-Package-Purchase-Prediction

### Background and Context

You are a Data Scientist for a tourism company named "Visit with us". The Policy Maker of the company wants to enable and establish a viable business model to expand the customer base.

A viable business model is a central concept that helps you to understand the existing ways of doing the business and how to change the ways for the benefit of the tourism sector. One of the ways to expand the customer base is to introduce a new offering of packages.

Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages.

However, the marketing cost was quite high because customers were contacted at random without looking at the available information.

The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being.

However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

You as a Data Scientist at "Visit with us" travel company have to analyze the customers' data and information to provide recommendations to the Policy Maker and Marketing Team and also build a model to predict the potential customer who is going to purchase the newly introduced travel package.

### Objective:
To build a model to predict which customer is potentially going to purchase the newly introduced travel package.

### Data Description:

**CustomerID**: Unique customer ID

**ProdTaken**: Whether the customer has purchased a package or not (0: No, 1: Yes)

**Age**: Age of customer

**TypeofContact**: How customer was contacted (Company Invited or Self Inquiry)

**CityTier**: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3

**DurationOfPitch**: Duration of the pitch by a salesperson to the customer

**Occupation**: Occupation of customer

**Gender**: Gender of customer

**NumberOfPersonVisiting**: Total number of persons planning to take the trip with the customer

**NumberOfFollowups**: Total number of follow-ups has been done by the salesperson after the sales pitch

**ProductPitched**: Product pitched by the salesperson

**PreferredPropertyStar**: Preferred hotel property rating by customer

**MaritalStatus**: Marital status of customer

**NumberOfTrips**: Average number of trips in a year by customer

**Passport**: The customer has a passport or not (0: No, 1: Yes)

**PitchSatisfactionScore**: Sales pitch satisfaction score

**OwnCar**: Whether the customers own a car or not (0: No, 1: Yes)

**NumberOfChildrenVisiting**: Total number of children with age less than 5 planning to take the trip with the customer

**Designation**: Designation of the customer in the current organization

**MonthlyIncome**: Gross monthly income of the customer

## Business Recommendations
The model of best performance could be used to help identify certain customers who may purcase a package. Given that the main features within this model were passport, married couples and the basic package, this contributes to identifying a target market.

For example, discounts for the Wellness Tourism Package could be offered to married couples. Also, if they could offer discounts on some of their international offers which may attract people with a passpost to travel abroad. While the Wellness Tourism Package is the new package they are offering, the basic package is quite a popular package. Therefore, additional offerings for the basic package should be considered. Alternatively, correlating this package with the Wellness package could be considered. For example, they could have a basic package for the Wellness package which is cheaper and more affordable for customers.

While those were some of the main features for the model of best performance, its worth discussing some of the other features that we evaluated throughout the EDA and some of the models build:

Pitch Satisfactory Score: As expected a score of 5 led to the most sales from the EDA. Assessing the sales people/team with the highest scores could be taken into account to target the right customers. Some of the employees with poor scores could shadow the higher scored employees. This may help improve their performance. Also, the marketing team should target the customers that did return a score of 5 as they would be more likely to repuchase.

Type of Contact - a self enquiry was the highest form of contact, but from the EDA there was little difference in terms of sales. While a lot of enquires in todays market are more than likely over the phone or online, in person performance needs to also be evaulated. For example, is someoen does "Self Enquire" in person, the sales people in office need to be able to pitch the new product confidently.

Age & Income - from both the EDA and the model building Age and Income are important features to consider. Wellness Tourism Package is defined as "Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being.". In terms of age this could be a broad category of individuals from young people looking to improve their health, all the way to people in their 50s/60s looking to improve their health and well being. Given this wide gap and that age is highly correlated with income, how this package is priced is very imprtant. As recommended having different forms of the package could be considered e.g. have a basic form of the package as well as a delux type package for older customers.

