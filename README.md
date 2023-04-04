## Backgrounds
As businesses strive to stay competitive in today's marketplace, data-driven decision-making is becoming increasingly important. To achieve this, companies utilize various data analysis techniques to gain insights about customers. By gaining this insight, companies can adjust their products and strategies to better meet customer needs and increase revenue.

## Problem Statement
1. What kind of customer background is the company's priority in an effort to maintain and increase revenue?
1. Is there a significant correlation influencing customers in shopping?
1. What are the recommendations for companies based on efforts to maintain and increase revenue?


## Data Field
### People : 

| Variable Name | Description |
| --- | --- |
| `ID` | Customer's unique identifier |
| `Year_Birth` | Customer's birth year | 
| `Education` | Customer's education level |
| `Marital_Status` | Customer's marital status |
| `Income` | Customer's yearly household income | 
| `Kidhome` | Number of children in customer's household |
| `Teenhome` | Number of teenagers in customer's household |
| `Dt_Customer` | Date of customer's enrollment with the company |
| `Recency` | Number of days since customer's last purchase |
| `Complain` | 1 if customer complained in the last 2 years, 0 otherwise |

### Products :

| Variable Name | Description | 
| --- | --- |
| `MntWines` | Amount spent on wine in last 2 years |
| `MntFruits` | Amount spent on fruits in last 2 years |
| `MntMeatProducts` | Amount spent on meat in last 2 years |
| `MntFishProducts` | Amount spent on fish in last 2 years |
| `MntSweetProducts` | Amount spent on sweets in last 2 years |
| `MntGoldProds` | Amount spent on gold in last 2 years |

### Promotion :

| Variable Name | Description |
| --- | --- |
| `NumDealsPurchases` | Number of purchases made with a discount |
| `AcceptedCmp1` | 1 if customer accepted the offer in the 1st campaign, 0 otherwise |
| `AcceptedCmp2` | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise |
| `AcceptedCmp3` | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise |
| `AcceptedCmp4` | 1 if customer accepted the offer in the 4th campaign, 0 otherwise |
| `AcceptedCmp5` | 1 if customer accepted the offer in the 5th campaign, 0 otherwise |
| `Response` | 1 if customer accepted the offer in the last campaign, 0 otherwise |

### Place :

| Variable Name | Description |
| --- | --- |
| `NumWebPurchases` | Number of purchases made through the company’s web site |
| `NumCatalogPurchases` | Number of purchases made using a catalogue |
| `NumStorePurchases` | Number of purchases made directly in stores |
| `NumWebVisitsMonth` | Number of visits to company’s web site in the last month |

## Conclusion
**1. What kind of customer background is the company's priority in an effort to maintain and increase revenue?**
Age Category, Education Level, Marriage Level, Number of Children have an association on Total Expenses. By looking at comparisons between groups of variables, insights can be obtained in the form of:
<br>
- It is expected that the company can create a strategy to **maintain** the performance of customers who at least meet one of the following categories because the proportion level of Total_Expense (as revenue) is very high:
    1. Customers who already have a partner (couple)
    2. Customers who do not have children
    3. Customers with a Bachelor's level of education
    4. Customers whose ages are in the range of 36-50
<br><br>
- Other things can be seen as improvement opportunities because they have a small Total Expenses as a source of revenue. It is expected that the company can create a strategy to **increase** the performance of customers who at least meet one of the following categories:
    1. Customers whose education level is Basic
    2. Customers who have 3 children
    3. Customers whose age is in the range of 24 years or less

**2. Does any the correlation significantly affect customers in shopping?**
There is a strong relationship for Total_Expenses & Total_Purchases, Income & Total_Expenses, and Income & Total_Purchases where it is also known that there is a moderate relationship between Number_of_Child & NumDealsPurchases.

1. Total_Expenses & Total_Purchases have a strong positive correlation (0.910080). This means that when customers spend more on a company's products, they also tend to make more purchases. This information is useful for companies to focus on techniques to increase the total purchase value of each customer.
<br><br>
2. Income & Total_Expenses have a strong positive correlation (0.853119). This suggests that as customer income increases, they tend to spend more on the company's products. Companies can target higher income demographics with more expensive products or marketing campaigns to maximize their sales.
<br><br>
3. Income & Total_Expenses have a fairly strong positive correlation (0.779843). This implies that customers with higher income tend to make more purchases from the company. Companies can use this information to adapt their marketing strategy towards higher earning customers to drive more sales.
<br><br>
4. Number_of_Child & NumDealsPurchases have a moderate positive correlation (0.542874). This shows that customers with more children tend to take advantage of the discount offers offered by the company. Companies can use this information to target families with more children with exclusive discounts and promotions.

**3. What are the recommendations for companies based on efforts to maintain and increase revenue?**
1. Maintaining Loyal Customer Performance
     - Customize the preferences of loyal customers (already have a partner or don't have children or Bachelor's education level or aged 36-50 or have a high total expenses).
     - Provide special discounts or incentives for loyal customers to increase their loyalty and encourage them to keep shopping with the company.
2. Improve Potential Customer Performance
     - The company develops new products and marketing strategies according to the needs and preferences of potential customers (basic education level or having 3 children or aged 24 and under or having less total expenses)
3. Increasing the Total Purchase Value of Each Customer
     - Companies can encourage customers to make more purchases by providing discounts or special promotions on purchases:
         - Upselling refers to the practice of encouraging customers to buy a more expensive or more sophisticated version of a product or service that they are already interested in.
         - Cross-selling refers to the practice of offering customers complementary or related products or services that they may be interested in buying in addition to the products they are already considering.
4. Target High-Earning Customers
     - Companies can develop more exclusive products for customers with higher incomes to increase their interest and purchase frequency
5. Targeting Families with Multiple Children
     - Companies can develop special products or services for families with many children, such as more advantageous product or service packages or product bundling offers to suit their needs.
