# Customer-Segmentation-Analysis
### Problem Statement
Customer Personality Analysis is a detailed examination of a company's ideal customers. It enables a business to better understand its customer base, facilitating the customization of products to meet the specific needs, behaviors, and concerns of different customer segments.
This analysis is instrumental in allowing a business to tailor its products effectively. For instance, rather than allocating resources to market a new product to every customer in the company's database, a more strategic approach is to identify which customer segment is most likely to purchase the product. The company can then focus its marketing efforts on this particular segment, optimizing both impact and efficiency.

### Aim
The aim of this project is to perform clustering to identify and summarize distinct customer segments. By doing so, we seek to enable targeted marketing strategies and product customization, aligning offerings with the preferences and needs of each segment.

### Objective
To segment customers, we plan to implement the K-means clustering algorithm, complemented by the elbow method to determine the optimal number of clusters. Additionally, to manage the complexity and enhance the interpretability of our dataset, we will employ Principal Component Analysis (PCA) for dimensionality reduction.

#### Attributes

*People:
1. ID: Customer's unique identifier
2. Year_Birth: Customer's birth year
3. Education: Customer's education level
4. Marital_Status: Customer's marital status
5. Income: Customer's yearly household income
6. Kidhome: Number of children in customer's household
7. Teenhome: Number of teenagers in customer's household
8. Dt_Customer: Date of customer's enrollment with the company
9. Recency: Number of days since customer's last purchase
10. Complain: 1 if the customer complained in the last 2 years, 0 otherwise

*Products:
11. MntWines: Amount spent on wine in last 2 years
12. MntFruits: Amount spent on fruits in last 2 years
13. MntMeatProducts: Amount spent on meat in last 2 years
14. MntFishProducts: Amount spent on fish in last 2 years
15. MntSweetProducts: Amount spent on sweets in last 2 years
16. MntGoldProds: Amount spent on gold in last 2 years

*Promotion:
17. NumDealsPurchases: Number of purchases made with a discount
18. AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
19. AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
20. AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
21. AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
22. AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
23. Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

*Place:
24. NumWebPurchases: Number of purchases made through the company’s website
25. NumCatalogPurchases: Number of purchases made using a catalogue
26. NumStorePurchases: Number of purchases made directly in stores
27. NumWebVisitsMonth: Number of visits to company’s website in the last month
