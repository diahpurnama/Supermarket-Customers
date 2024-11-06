Supermarket Customer Behavior and Campaign Effectiveness Analysis
Background
In the competitive retail market, supermarkets continuously strive to enhance their understanding of customer behavior to improve product offerings, personalize marketing efforts, and increase overall sales. As consumer preferences evolve with demographic shifts and lifestyle changes, it becomes crucial to leverage data-driven insights to tailor experiences to specific customer groups.

This analysis explores key factors affecting shopping behavior, spending patterns, campaign engagement, and promotional effectiveness in a supermarket setting. By analyzing customer demographics alongside their purchasing habits, shopping channel preferences, and responses to marketing campaigns, we aim to offer actionable recommendations that can help supermarkets optimize both their in-store and online services. Insights from this study support targeted marketing and improved customer satisfaction, contributing to long-term customer loyalty and increased revenue.

Problem Statement
The primary questions guiding this analysis are:

1. How do consumer demographics influence the choice of shopping channels in supermarkets?
Understanding which customer groups prefer online versus in-store shopping is essential for supermarkets looking to allocate resources effectively. By identifying patterns in shopping channel preferences across different demographics (age, family size, marital status, and education level), supermarkets can create targeted marketing strategies, enhancing both the in-store and online shopping experiences.

2. How does customer demographics affect spending patterns across different product categories in supermarkets?
Customer demographics often influence purchasing choices across product categories. Recognizing the spending tendencies of various groups, such as age and income, enables supermarkets to optimize product placement, adjust inventory, and design specialized promotions that resonate with each demographic segment, ultimately driving sales.

3. How effective are the marketing campaigns in reaching and engaging customers?
The effectiveness of marketing campaigns varies widely across customer segments, impacting both reach and repeat engagement. By analyzing campaign participation and identifying characteristics of responsive customers, supermarkets can refine their strategies to increase customer engagement, improve campaign ROI, and foster loyalty.

4. Which customers are more likely to make purchases through deals or discounts?
Promotional offers and discounts are essential tools for driving short-term sales, yet their appeal can differ based on customer income and purchasing behavior. This analysis seeks to determine which customers are most responsive to deals, providing insights into how supermarkets can structure offers to maximize engagement across all income levels and demographic groups.

Approach
This analysis leverages data visualization tools and statistical analysis to examine customer purchasing behavior and campaign responses. Key findings and tailored recommendations are provided to guide supermarkets in improving their product offerings, promotional tactics, and customer experience strategies.


Data Dictionary:

People
● ID: Customer's unique identifier
● Year_Birth: Customer's birth year
● Education: Customer's education level
● Marital_Status: Customer's marital status
● Income: Customer's yearly household income
● Kidhome: Number of children in customer's household
● Teenhome: Number of teenagers in customer's household
● Dt_Customer: Date of customer's enrollment with the company
● Recency: Number of days since customer's last purchase
● Complain: 1 if the customer complained in the last 2 years, 0 otherwise
Products
● MntWines: Amount spent on wine in last 2 years
● MntFruits: Amount spent on fruits in last 2 years
● MntMeatProducts: Amount spent on meat in last 2 years
● MntFishProducts: Amount spent on fish in last 2 years
● MntSweetProducts: Amount spent on sweets in last 2 years
● MntGoldProds: Amount spent on gold in last 2 years
Promotion
● NumDealsPurchases: Number of purchases made with a discount
● AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
● AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
● AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
● AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
● AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
● Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise
Place
● NumWebPurchases: Number of purchases made through the company’s website
● NumCatalogPurchases: Number of purchases made using a catalog
● NumStorePurchases: Number of purchases made directly in stores
● NumWebVisitsMonth: Number of visits to the company’s website in the last month
