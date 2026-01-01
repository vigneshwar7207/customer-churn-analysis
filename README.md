📊 Customer Churn Analysis – Telco Dataset
📖 Project Overview

Customer churn occurs when customers stop using a company’s services.
This project analyzes **telecom customer data** to identify the key factors that influence customer churn and provides **data-driven business recommendations** to improve customer retention.

The analysis focuses on customer demographics, service subscriptions, contract details, and billing information.

 🎯 Project Objectives

* Understand customer behavior and churn patterns
* Identify services and contract types with high churn rates
* Analyze the impact of monthly charges and payment methods
* Provide actionable strategies to reduce churn and improve retention

 📂 Dataset Information

* Dataset Name: Telco Customer Churn
* File Type: CSV
* Total Records: ~7,000 customers
* Target Variable: `Churn` (Yes / No)

 📌 Key Features in Dataset

* Customer Demographics: gender, SeniorCitizen, Partner, Dependents
* Account Information: tenure, Contract, PaperlessBilling, PaymentMethod
* Services Used:
    * PhoneService, MultipleLines
    * InternetService
    * OnlineSecurity, OnlineBackup
    * DeviceProtection, TechSupport
    * StreamingTV, StreamingMovies

* Billing Details:
  * MonthlyCharges
  * TotalCharges

 🛠 Tools & Technologies Used

* Programming Language: Python
* Libraries:

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* IDE / Environment: Jupyter Notebook

 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed using count plots and distribution plots:

* Contract type vs Churn
* Payment method vs Churn
* Internet service vs Churn
* Add-on services (TechSupport, OnlineSecurity, DeviceProtection) vs Churn
* Monthly charges distribution by churn status

The tenure column was excluded from certain visual analyses to focus on categorical churn drivers.

 📊 Key Findings

* Customers on **month-to-month contracts** have the highest churn rate
* Customers using **Fiber optic internet** churn more compared to DSL users
* Lack of **Tech Support and Online Security** is strongly associated with churn
* Customers paying via **Electronic Check** churn more frequently
* Higher **Monthly Charges** increase the likelihood of churn

 💡 Business Recommendations

Based on the analysis, the following strategies are recommended:

* Promote **long-term contracts** through discounts and loyalty benefits
* Improve and actively market **Tech Support and Online Security services**
* Offer bundled service packages to increase service dependency
* Introduce targeted retention offers for customers with high monthly charges
* Incentivize customers to switch to **automatic payment methods**

 📈 Business Impact

Implementing these recommendations can help the company:

* Reduce customer churn
* Increase customer lifetime value (CLV)
* Improve customer satisfaction
* Stabilize long-term revenue growth

 📌 Conclusion

This project demonstrates how exploratory data analysis can uncover key churn drivers in the telecom industry.
By understanding customer behavior and acting on these insights, businesses can proactively reduce churn and improve customer retention.


      
