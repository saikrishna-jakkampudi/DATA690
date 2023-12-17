## DATA_606_CAPSTONE PROJECT

#### Professor: Dr. Chaojie Wang

#### Project Title:E-Commerce Customer Churn Prediction

Prepared for UMBC Data Science Master Degree Capstone under Guidance of Prof Dr Chaojie (Jay) Wang

#### Student Name: Sai Krishna Jakkampudi

#### Semester: FALL 2023


**PowerPoint presentation file:**

**Link to your YouTube video:**

**GitHub:** https://github.com/saikrishna-jakkampudi

#### Background

**Customer churn analysis involves studying customer behavior to identify patterns and factors that contribute to customers discontinuing their relationship with a business. It aims to predict which customers are likely to churn in the future so that businesses can take preventive actions to retain them. This analysis is crucial across industries such as telecommunications, subscription services, e-commerce, and more. This topic matters in several ways. For instance, it impacts the revenue of a company. Customer churn has a significant impact on a company's revenue. When customers stop doing business with a company, it directly results in a loss of revenue.**

**These lost sales and transactions can accumulate quickly, especially for businesses with a large customer base. Furthermore, reducing churn can provide a competitive advantage in crowded and saturated markets. In competitive industries, customers have numerous options, making it easier for them to switch to a competitor if they are dissatisfied. By effectively managing churn, a business can differentiate itself from competitors and enhance its reputation for customer satisfaction. Customers are more likely to stay loyal to a brand that consistently meets their needs and expectations. This loyalty can translate into increased market share and a stronger position in the industry.**

## DATA

**Data source**: [Kaggle - E-commerce Customer Churn Analysis and Prediction](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

- **Credibility of source**: The data is sourced from Kaggle, a reputable platform for datasets and data-related projects, known for its quality datasets contributed by the community.

- **Quality of data**: The dataset appears to be well-maintained and documented, providing a comprehensive set of features for analysis.

- **Size of data**: The dataset contains 5630 records, which is a reasonably sized dataset suitable for analysis.

**Attributes of data**:

- **CustomerID**

  - Data type: Continous
  - Description: Unique customer ID.
  - Possible data entries: "50001" to  "55630"
  
- **Churn**

  - Data type: Categorical ( Binary)
  - Description: Chrun Flag.
  - Possible data entries: "0" and  "1"
  
- **Tenure**

  - Data type: Continous ( Numerical)
  - Description: Tenure of customer in the organization.
  - Possible data entries Range: "0" to  "61"

- **PreferredLoginDevice**

  - Data type: Catergorical ( Nominal)
  - Description: Preferred Login Device of the Customer.
  - Possible data entries Range: "Phone", "Mobile Phone", "Computer"

- **CityTier**

  - Data type: Catergorical ( Ordinal)
  - Description: City Ter.
  - Possible data entries Range: "1", "2", "3"
  

- **WarehouseToHome**

  - Data type: Continous ( Numerical)
  - Description: Distance between customer house to warehouse
  - Possible data entries Range: "5" to  "127"
  
- **PreferredPaymentMode**

  - Data type: Catergorical ( Nominal)
  - Description: Preferred payment method of the customer.
  - Possible data entries Range: "CC", "CREDIT CARD", "DEBIT CARD", "UPI", "E-WALLET", "COD"," CASH ON DELIVERY"

- **Gender**

  - Data type: Categorical ( Binary)
  - Description: Gender of the Customer.
  - Possible data entries: "Male" and  "Female".
  
- **HourSpendOnApp**

  - Data type: Continous
  - Description: Number of hours customer spent on app or website.
  - Possible data entries: "0" to  "5".

- **NumberOfDeviceRegistered**

  - Data type: Continous
  - Description: Total number of devices registered per customer.
  - Possible data entries: "0" to  "6".
  
- **PreferedOrderCat**

  - Data type: Catergorical ( Nominal)
  - Description: Preferred order category in the last month.
  - Possible data entries Range: "Fashion", "Grocery", "Laptop & Accessories", "Mobile", "MObile-Phone", "Others".

- **SatisfactionScore**

  - Data type: Continous
  - Description: Customer Satisfaction Score.
  - Possible data entries: "1" to  "5".

- **MaritalStatus**

  - Data type: Catergorical ( Nominal)
  - Description: Marital status of the customer.
  - Possible data entries Range: "Single", "Married", "Divorce".

    
- **NumberOfAddress**

  - Data type: Continous ( Numerical)
  - Description: Total number of addresses added by customer
  - Possible data entries Range: "1" to  "22"

- **Complain**

  - Data type: Categorical ( Binary)
  - Description: Number of compliants received in the last month
  - Possible data entries Range: "0" to  "1"
  
  
- **OrderAmountHikeFromlastYear**

  - Data type: Continous ( Numerical)
  - Description: Percentage increase in order amount from last year
  - Possible data entries Range: "11" to  "26"


- **CouponUsed**

  - Data type: Continous ( Numerical)
  - Description: Total number of coupons used last month.
  - Possible data entries Range: "0" to  "16"

- **OrderCount**

  - Data type: Continous ( Numerical)
  - Description: Total number of orders place in last month.
  - Possible data entries Range: "0" to  "16"

- **DaySinceLastOrder**

  - Data type: Continous ( Numerical)
  - Description: Days since last order by the customer
  - Possible data entries Range: "0" to  "46"
  
- **CashbackAmount**

  - Data type: Continous ( Numerical)
  - Description: Average cashback in last month.
  - Possible data entries Range: "0" to  "325"


- **Dependent and independent variables**

Customer Churn is the most effective target variable for creating machine-learning models from the dataset. It is a binary variable that machine learning systems can classify with ease. Additionally, there is plenty of information and study on the subject because customer turnover is a regular and significant issue for organizations to address. On the other hand, for predictor variables, I used all the variables except customerID.

### EXPLORATORY DATA ANALYSIS (EDA)

![Alt Text]("C:\Users\saikr\Desktop\DATA-606\Version_4\Summary_Stastics.jpg")



```python

```
