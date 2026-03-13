# 🏠 Bluestone Real Estate Market Intelligence Analysis

### End-to-End Data Analytics Project | Snowflake • Power query • Power BI

## Overview

Real estate organisations often struggle to understand market demand, lead conversion performance, and transaction trends due to fragmented data systems.

This project builds a **centralised analytics solution** that integrates property listings, customer inquiries, and completed transactions into a unified analytical framework.

Using **Snowflake, Power BI, and dimensional modelling**, the project transforms raw real estate data into interactive dashboards that reveal demand patterns, operational bottlenecks, and conversion opportunities.

The goal is to enable **data-driven decision making for real estate agencies and PropTech platforms**.



---

# Business Problem

Real estate operations generate large volumes of data across different systems, including listing platforms, CRM systems, and transaction databases.

However, these datasets are often **disconnected**, preventing organisations from gaining a holistic view of their market performance.

### Key Challenges

• Property listings, inquiries, and transactions exist in **separate data sources**

• Stakeholders lack **real-time visibility into market demand**

• Sales teams cannot easily track **customer progression from inquiry to deal**

• Slow inquiry response times lead to **lost customers**

Without a consolidated analytical system, businesses struggle to optimise pricing strategies, marketing campaigns, and operational efficiency.



---

# Project Objectives

This project was designed to solve these challenges by building a **modern real estate analytics platform**.

### Core Objectives

• Integrate fragmented real estate datasets into a **single analytical model**

• Track **customer journey from inquiry → lead → transaction**

• Identify **high-demand property segments**

• Detect **sales funnel bottlenecks**

• Provide **real-time dashboards for market monitoring**



---

# Tech Stack

| Layer               | Tools       |
| ------------------- | ----------- |
| Data Warehouse      | Snowflake   |
| Data Transformation | Power Query |
| Data Modeling       | Star Schema |
| Data Visualisation  | Power BI    |
| Analytics           | SQL         |

---

# Data Architecture
<img width="715" height="491" alt="MODEL" src="https://github.com/user-attachments/assets/53b435a4-dc60-4c79-b776-5611ef0fb93d" />
The analytics workflow follows a **modern ELT pipeline**.

```
Raw Data Sources
      │
      ▼
Snowflake Data Warehouse
      │
      ▼
Data Cleaning (Power Query)
      │
      ▼
Dimensional Data Model
      │
      ▼
Power BI Analytics Dashboard
```

This pipeline enables scalable reporting and ensures that data is cleaned, structured, and optimised for analytics.



---

# Data Model

The project uses a **Star Schema** to optimise analytical performance.

### Fact Tables

• `fact_listings`
• `fact_inquiries`
• `fact_transactions`
`fact_listings_history

### Dimension Tables

• `dim_property`
• `dim_city`
• `dim_date`

This structure allows efficient querying of large datasets and supports complex business metrics.

---

# Key Business Questions

The analysis addresses several strategic questions relevant to real estate operations.

### Market Demand

Which property types attract the highest demand?

### Sales Funnel Performance

How effectively do inquiries convert into completed deals?

### Seasonal Trends

When does transaction activity peak during the year?

### Operational Efficiency

How does response time impact deal conversion?



---

# Key Insights

### 1. Apartments Dominate Rental Demand
<img width="946" height="462" alt="image" src="https://github.com/user-attachments/assets/d340242f-0b59-4a93-88e6-0518806b8fa7" />

Apartments generate significantly higher rental activity compared to property sales.

This highlights strong tenant demand for apartment housing and indicates that rental marketing strategies should prioritise apartment listings.

---

### 2. Real Estate Transactions Peak in Q4
<img width="954" height="400" alt="image" src="https://github.com/user-attachments/assets/ec1ad7ca-cdb8-4662-9bb3-c37d8723a7e4" />

Transaction activity increases sharply during the fourth quarter.

This seasonal pattern suggests agencies should scale marketing and listing availability ahead of year-end demand.

---

### 3. Slow Inquiry Responses Reduce Conversions

<img width="165" height="110" alt="image" src="https://github.com/user-attachments/assets/a1788d97-e610-4bfb-a975-f7b14122733e" />

Customers often contact multiple agents simultaneously.

Delays in responding to inquiries increase the likelihood of losing potential buyers or renters to competitors.

Faster response times improve the probability of closing deals.


---

# Business Recommendations

### Implement CRM Automation

Automate notifications and lead alerts to ensure agents respond quickly to new inquiries.

### Improve Lead Nurturing

Introduce structured follow-up workflows to increase lead-to-offer conversion.

### Focus Marketing on High-Demand Properties

Prioritise marketing for:

• Apartments (rental demand)
• Single-family homes and condos (sales demand)

### Prepare for Seasonal Demand

Increase listing supply and marketing activity ahead of the Q4 transaction surge.



---

# Dashboard Features

The Power BI dashboards provide stakeholders with real-time analytics including:
<img width="675" height="405" alt="image" src="https://github.com/user-attachments/assets/4b7f2167-a4a3-464f-8813-77cb0a6b4130" />
<img width="667" height="403" alt="image" src="https://github.com/user-attachments/assets/d27345b3-4735-4acd-ae28-ba193f47b7f3" />

### Market Performance

• Listings by city
• Property demand analysis

### Sales Funnel Analysis

• Total inquiries
• Qualified leads
• Offers submitted
• Closed transactions

### Operational Metrics

• Inquiry response time
• Lead conversion rates

### Market Trends

• Monthly transaction volume
• Rental vs sales performance

---

# Example KPIs

| KPI                    | Description                                 |
| ---------------------- | ------------------------------------------- |
| Total Listings         | Number of active property listings          |
| Total Inquiries        | Customer inquiries received                 |
| Lead Conversion Rate   | % of inquiries that convert to deals        |
| Average Days on Market | Time required to close a property           |
| Inquiry Response Time  | Average response time to customer inquiries |
| Transaction Volume     | Completed sales or rentals                  |

---

# Business Impact

The solution enables real estate organisations to:

• Identify **high-performing markets and property types**

• Improve **lead conversion performance**

• Detect **sales funnel inefficiencies**

• Monitor **market trends in real time**

• Support **data-driven strategic decision making**

---

# Project Structure

```
Real-Estate-Analytics-Project
│
├── Data
│   └── Sample datasets
│
├── SQL
│   └── Data transformation queries
│
├── PowerBI
│   └── Dashboard files (.pbix)
│
├── Documentation
│   └── Data model & KPI dictionary
│
└── README.md
```

---
# link to interactive dashboard: 
https://app.powerbi.com/view?r=eyJrIjoiYjAyYzQ0NWQtNjA5Ni00NzIwLWExOTMtZWYyMjZhN2Q5OGRmIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9

# Key Skills Demonstrated

• Data Warehousing
• SQL Analytics
• Data Modelling (Star Schema)
• Power BI Dashboard Development
• Business Intelligence
• KPI Development
• Data-Driven Decision Making

---

# Author

**Elijah Okpako**

Data Analyst | Business Intelligence | Data-Driven Decision Making
