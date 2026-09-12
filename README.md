# Insurance Claims & Policy Analytics Dashboard

## 📌 Project Overview

An interactive **Power BI dashboard** designed to analyze insurance policies, customers, claims, and customer feedback.

The dashboard provides a consolidated view of key insurance metrics such as **Premium Amount, Coverage Amount, Claim Amount, Claim Status, Policy Performance, Customer Demographics, and Customer Feedback Sentiment**.

The project uses **MySQL** as the database, **Power Query** for data transformation, and **DAX** for analytical calculations and KPI development.

---

## 🎯 Business Problem

Insurance companies generate large amounts of data related to customers, policies, claims, and customer feedback.

Analyzing this data manually can make it difficult to identify important trends, monitor claim performance, and understand customer experience.

This project provides an interactive dashboard to help users:

- Monitor premium, coverage, and claim amounts
- Understand claim distribution by status
- Compare different insurance policy types
- Analyze active and inactive policies
- Understand customer demographics
- Analyze claim amounts across different age groups
- Explore detailed policy and claim records
- Analyze customer feedback and sentiment
- Identify areas where customer experience can be improved

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze insurance policy performance
- Track key financial metrics
- Analyze claims by claim status
- Compare premium amounts across policy types
- Analyze active and inactive policies
- Understand customer demographics
- Analyze claim amounts by age group
- Explore detailed policy and claim information
- Analyze customer feedback
- Perform sentiment analysis on customer feedback
- Build an interactive Power BI dashboard
- Implement Drill-through functionality
- Configure Scheduled Refresh in Power BI Service
- Implement Row-Level Security (RLS)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **MySQL** | Database management and data querying |
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures, KPIs, and analytical calculations |
| **Power BI Service** | Report publishing, refresh, and security |
| **Excel** | Supporting data handling |

---

## 📊 Dataset

The dataset contains insurance-related information covering **customers, policies, claims, and customer feedback**.

### Key Data Fields

| Field | Description |
|---|---|
| Policy Number | Unique policy identifier |
| Customer ID | Unique customer identifier |
| Claim Number | Unique claim identifier |
| Age | Customer age |
| Gender | Customer gender |
| Coverage Amount | Insurance coverage amount |
| Policy Start Date | Policy start date |
| Policy End Date | Policy end date |
| Policy Type | Type of insurance policy |
| Claim Status | Current status of the claim |
| Claim Date | Date of claim |
| Claim Amount | Claim amount |
| Age Group | Customer age category |
| Active/Inactive | Policy activity status |
| Customer Name | Customer name |
| Feedback | Customer feedback |
| Sentiment Score | Sentiment score of customer feedback |

### Policy Types

- Travel
- Health
- Auto
- Life
- Home

### Claim Status

- Pending
- Settled
- Rejected

---

## 🔄 Data Preparation

The insurance data was connected to Power BI and prepared for analysis using **MySQL and Power Query**.

### Data preparation included:

- Connecting the database with Power BI
- Reviewing data structure and data types
- Cleaning and transforming data
- Formatting date fields
- Preparing categorical fields
- Creating age group categories
- Preparing policy status information
- Transforming customer feedback data
- Preparing data for sentiment analysis
- Creating required fields for analysis and visualization

**Power Query** was primarily used for data transformation and preparation, while **DAX** was used to create analytical measures and KPIs.

---

## 📈 Dashboard Features

The Power BI report contains multiple interactive pages for analyzing insurance data.

### 1. Overview Dashboard

The Overview page provides a high-level summary of insurance performance.

### Key KPIs

- **Premium Amount:** 5.98M
- **Coverage Amount:** 600.55M
- **Claim Amount:** 16.91M

### Visualizations

- Premium Amount by Policy Type
- Active vs Inactive Policies
- Claims by Claim Status
- Claim Amount by Age Group
- Policy Type vs Claim Status
- Gender-wise Customer Count
- Interactive Policy Number Slicer

---

### 2. Detail Table

The Detail page provides a detailed view of individual policy and claim records.

It includes information such as:

- Policy Number
- Customer ID
- Claim Number
- Age
- Gender
- Coverage Amount
- Policy Start Date
- Policy End Date
- Policy Type
- Claim Status
- Claim Date
- Claim Amount
- Age Group
- Active/Inactive Status

This page allows users to move from summarized dashboard information to detailed records.

---

### 3. Interactive Power BI Features

The project implements several Power BI features:

- Slicers
- KPI Cards
- Bar Charts
- Line Charts
- Donut Charts
- Ribbon Chart
- Funnel Chart
- Matrix
- Multi-row Card
- Drill-through
- Scheduled Refresh
- Row-Level Security (RLS)
- Power BI Service Publishing

---

## 😊 Sentiment Analysis

A dedicated **Sentiment Analysis** page was created to analyze customer feedback.

The page includes:

- Customer feedback table
- Sentiment scores
- Feedback categories
- Word Cloud
- Customer count by feedback category

### Feedback Summary

| Feedback Category | Customer Count |
|---|---:|
| Excellent | 50 |
| Needs Improvements | 33 |
| Good | 14 |

The sentiment analysis helps understand customer experience and identify common themes in feedback.

The analysis covers feedback related to areas such as:

- Customer service
- Claims
- Policies
- Website experience
- Support
- Premiums
- Coverage

---

## 🔑 Key Insights

Based on the dashboard analysis:

- **Travel policies** contribute the highest premium amount among the displayed policy types.
- **Active policies** represent a larger proportion compared to inactive policies.
- **Rejected claims** have the highest count among the displayed claim statuses.
- **Adult customers** contribute the highest claim amount among the displayed age groups.
- **Excellent** is the largest customer feedback category among the displayed categories.
- Customer feedback also highlights areas where improvements are required.
- Feedback analysis provides useful information about customer experiences related to claims, policies, services, and support.

---

## 📷 Dashboard Preview

### Overview Dashboard

![Overview Dashboard](images/overview-dashboard.png)

---

### Detail Table

![Detail Table](images/detail-table.png)

---

### Sentiment Analysis

![Sentiment Analysis](images/sentiment-analysis.png)

---

## 🚀 Project Workflow

```text
Insurance Data
      ↓
    MySQL
      ↓
Data Retrieval / SQL
      ↓
   Power BI
      ↓
 Power Query
      ↓
Data Cleaning & Transformation
      ↓
     DAX
      ↓
KPI & Analytical Measures
      ↓
Interactive Dashboard
      ↓
 Power BI Service
      ↓
Scheduled Refresh + RLS

## 👨‍💻 Author

**Karan Kumar Chauhan**

B.Tech – CSE(Data Science)

**Skills:** SQL · MySQL · Python · Power BI · DAX · Power Query · Excel · Data Analytics
