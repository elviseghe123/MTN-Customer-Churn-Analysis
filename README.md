# 📊 MTN Nigeria Customer Churn Analysis


## 📚 Table of Contents

- [📘 Project Overview](#-project-overview)
- [🔗 Data Source](#-data-source)
- [🛠️ Tools Used](#️-tools-used)
- [📊 Types of Analysis](#-types-of-analysis)
- [📌 Key Performance Indicators](#-key-performance-indicators)
- [📈 Data Analysis Process](#-data-analysis-process)
- [🔍 Insights](#-insights)
- [💡 Recommendations](#-recommendations)
---

## 📘 Project Overview

This project analyzes customer churn data from **MTN Nigeria**, aiming to identify the key reasons customers leave the service, understand usage and revenue behavior, and recommend strategies to improve retention. The data was cleaned in **Excel** and visualized using **Power BI**, with KPIs and DAX measures used to drive business insights. The final dashboard allows stakeholders to interact with the data and explore patterns in churn, satisfaction, and plan performance.
Aims and Objectives
Aim:
To use data analysis and visualization to understand customer churn patterns and revenue performance in order to recommend actions that reduce churn and maximize customer value.
Objectives:
- To determine the churn rate and distribution across customer segments.
- To identify the main reasons customers are leaving.
- To segment revenue by plan, device type, region, and customer demographics.
- To assess satisfaction rates in relation to churn.
- To categorize subscription plans and evaluate performance per category.
- To provide data-driven recommendations to stakeholders.


---

## 📊 Dashboard Access

You can view the full interactive Power BI dashboard here:

🔗 [Click to open the MTN Churn Dashboard](https://uniportedung-my.sharepoint.com/:u:/g/personal/eeghe061_uniport_edu_ng/EfiuXR_3BlVOiZ3wVSz3zd8BFPHe6LMhHNGrb1F41jOCGA?e=TjgBNa)


![Page 1](https://github.com/user-attachments/assets/535f556b-3284-4448-8361-3d6baff4fe00)

---
## 🔗 Data Source

- [MTN Nigeria Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/oluwademiladeadeniyi/mtn-nigeria-customer-churn)

---
## 🛠️ Tools Used

- **Microsoft Excel** – For data cleaning and transformation
- **Power BI** – For building visual dashboards
- **DAX (Data Analysis Expressions)** – For creating dynamic KPIs and metrics

---

## 📊 Types of Analysis

- **Descriptive Analysis**: To summarize key metrics like churn rate, satisfaction, and revenue.
- **Diagnostic Analysis**: To understand why churn is happening and where.
- **Comparative Analysis**: Comparing churned vs active users by demographic and plan.
- **Segmentation Analysis**: Classifying customers into usage tiers and plan categories.

---

## 📌 Key Performance Indicators

| KPI                        | Description                                               |
|----------------------------|-----------------------------------------------------------|
| **Churn Rate (%)**         | % of customers who have left the service                 |
| **ARPU**                   | Average Revenue Per User                                  |
| **Customer Lifetime Value (CLTV)** | Total revenue expected from a customer over their tenure |
| **Satisfaction Index**     | Average customer satisfaction score                       |
| **Revenue by Plan/Device** | Revenue performance per product or device                |
| **Data Usage Tiers**       | Grouping customers based on data usage behavior           |

---

## 📈 Data Analysis Process

### 🔹 Excel (Data Cleaning)

- Removed duplicate customer entries
- Converted usage fields like "less than 50GB" to numeric values
- Extracted date and tenure columns
- Categorized subscription plans (Daily, Weekly, Monthly, Yearly, Unlimited)
- Created usage tiers: `<10GB`, `10–50GB`, `50–100GB`, `100+GB`

### 🔹 Power BI (Visualization & KPIs)

- Built dashboards with slicers for Gender, State, Age Group, Device, and Plan
- Created DAX measures:
  - `Churn Rate = (Churned Customers / Total Customers) * 100`
  - `ARPU = Total Revenue / Active Customers`
  - `CLTV = Tenure * (Revenue / Purchases)`
  - `Satisfaction Index = AVERAGE(Satisfaction Rate)`
- Visualized trends using:
  - Donut charts (Churn vs Active)
  - Matrix (Satisfaction by Gender and Plan)
  - Bar chart (Churn by State)
  - Bar and line charts (Revenue by Plan, Usage by Tier)

---

## 🔍 Insights

### 📉 Churn Behavior
- Middle aged customers (ages 30- 50) and users in **Adamawa** and **Imo** states showed the highest churn.
- Most churned customers were on **Daily** or **Weekly** plans with low satisfaction.

### 💵 Revenue Patterns
- **Others** and **Monthly** plans generated the highest revenue.
- Customers using **5G Routers** and **MiFi** had longer tenures and lower churn.

### 😐 Customer Satisfaction
- Users with satisfaction scores of 1 or 2 had a significantly higher chance of churning.
- Higher satisfaction was linked to higher CLTV and better plan retention.

### 📶 Usage Behavior
- Customers consuming **100GB+** of data had longer tenure and were more loyal.
- Customers with low usage (<20GB) churned more often, especially on low-cost plans.

---

## 💡 Recommendations

### 🎯 Marketing
- Offer **loyalty rewards** for long-tenured customers
- Target **Daily/Weekly users** with upsell campaigns to upgrade them to **Monthly/Unlimited** plans

### 🤝 Customer Service
- Actively **monitor and respond to low satisfaction scores**
- Trigger **early retention actions** when usage drops or bad reviews are received

### 🧠 Management
- Use Power BI dashboards for **monthly churn and revenue reviews**
- Consider **redesigning low-performing plans** for clarity and better value

---

## 📥 How to Use This Project

1. Download the cleaned dataset or use the original Kaggle link.
2. Load the data into Power BI.
3. Import the theme file (`MTN_Customer_Churn_Theme.json`) for brand colors.
4. Open the `.pbix` report file and explore KPIs using slicers.
5. Use insights to guide retention, marketing, and plan improvement decisions.

---

## 🙌 Author
**Elvis** – Data Analyst & Visual Storyteller  
*For more projects like this, connect with me on GitHub or LinkedIn.*
- [Linkedin](https://www.linkedin.com/in/eghe-elvis/)
- [Github]( https://elviseghe123.github.io/Elvis_Portfolio/)
---

