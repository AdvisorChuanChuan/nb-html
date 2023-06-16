# Marketing Campaign

**Data Set Information:**

The dataset includes various types of information about customers who have been in contact with a company. The features of the dataset include demographic information (year of birth, education level, marital status, income), household composition (number of small children and teenagers), customer relationship with the company (date of enrollment, number of days since the last purchase, number of visits to the company's website in the last month, whether or not they complained in the last two years), spending habits (amount spent on various product categories in the last two years, number of purchases made with discount, through the company's website, using a catalogue, directly in stores), participation in marketing campaigns (whether they accepted the offer in the previous five campaigns), and financial measures related to the customer contact (cost of the contact, revenue of the contact). The dependent variable, or target, is whether or not the customer accepted the offer in the last campaign (a boolean value).

**Business Problem:**

 The primary business problem is developing a predictive model to determine whether a customer will accept an offer in a marketing campaign. The model type specified is Classification. The goal would likely be to use this model to target customers who are more likely to accept offers in future campaigns, thus optimizing marketing resources and potentially increasing revenue. The features provided could offer insights into which factors most influence a customer's decision to accept an offer, potentially guiding future marketing strategies.

**Model Type:**

Classification

**Feature Category:**

catrgorical, continuous, datetime


**Indenpendent Feature X:**
1. ID(identical key id) - identical ids of the sampling 2240 entries from 11191 total dataset
2. Year_Birth(ordinal) - year of birth
3. Education(categorical) - customer’s level of education
4. Marital_Status(categorical) - customer’s marital status
5. Income(numerical) - customer’s yearly household income(USD)
6. Kidhome(ordinal) - number of small children in customer’s household
7. Teenhome(ordinal) - number of teenagers in customer’s household
8. Dt_Customer(Date/time) - date of customer’s enrolment with the company
9. Recency(numerical) - number of days since the last purchase
10. MntWines(numerical) - amount spent on wine products in the last 2 years
11. MntFruits(numerical) - amount spent on fruits products in the last 2 years
12. MntMeatProducts(numerical) - amount spent on meat products in the last 2 years
13. MntFishProducts(numerical) - amount spent on fish products in the last 2 years
14. MntSweetProducts(numerical) - amount spent on sweet products in the last 2 years
15. MntGoldProds(numerical) - amount spent on gold products in the last 2 years
16. NumDealsPurchases(numerical) - number of purchases made with discount
17. NumWebPurchases(numerical) - number of purchases made through company’s web site
18. NumCatalogPurchases(numerical) - number of purchases made using catalogue  
19. NumStorePurchases(numerical) - number of purchases made directly in stores
20. NumWebVisitsMonth(numerical) - number of visits to company’s web site in the last month
21. ~ 25. AcceptedCmp1-5(Boolean) - 1 if customer accepted the offer in the x_th campaign, 0 otherwise
26. Complain(Boolean) - 1 if customer complained in the last 2 years
27. Z_CostContact(numerical) - cost of the contact
28. Z_Revenue(numerical) - revenue of the contact
