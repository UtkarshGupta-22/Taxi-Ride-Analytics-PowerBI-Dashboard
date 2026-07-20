<div align="center">

# Taxi Ride Analytics Dashboard

### End-to-End Business Intelligence Solution using Power BI

Transforming raw taxi booking data into actionable business insights through interactive dashboards, KPI tracking, and data-driven storytelling.

Built using **Power BI**, **Power Query**, **DAX**, and **Microsoft Excel**, this project demonstrates a complete Business Intelligence workflow—from data cleaning and modeling to interactive dashboard development and executive reporting.

---

![Power BI](https://img.shields.io/badge/Power_BI-Business_Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

![DAX](https://img.shields.io/badge/DAX-Analytics-blue?style=for-the-badge)

![Power Query](https://img.shields.io/badge/Power_Query-Data_Transformation-success?style=for-the-badge)

![Excel](https://img.shields.io/badge/Microsoft_Excel-Dataset-217346?style=for-the-badge&logo=microsoft-excel)

![Dashboard](https://img.shields.io/badge/Interactive_Dashboard-Power_BI-orange?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

# Table of Contents

- Project Overview
- Business Problem
- Objectives
- Dashboard Features
- Key Performance Indicators
- Technology Stack
- Dashboard Architecture
- Dataset
- Dashboard Pages
- Data Modeling
- DAX Measures
- Insights
- Business Recommendations
- Screenshots
- Skills Demonstrated
- Future Improvements
- License

---

# Project Overview

Taxi Ride Analytics Dashboard is a comprehensive Business Intelligence solution developed to analyze taxi booking operations, customer behavior, revenue trends, ride performance, cancellations, and service quality using interactive Power BI dashboards.

Rather than presenting raw operational data, this dashboard transforms complex booking records into meaningful business insights that help stakeholders monitor performance, identify operational bottlenecks, and make informed strategic decisions.

The project follows the complete analytics lifecycle:

- Data Collection
- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Dashboard Design
- Business Insight Generation

making it representative of real-world Business Intelligence projects.

---

# Business Problem

Taxi service providers generate thousands of booking records every day.

Without proper analytics, it becomes difficult to answer important business questions such as:

- Which vehicle category generates the highest revenue?
- Why are customers cancelling rides?
- Which payment methods are most popular?
- How efficiently are vehicles being utilized?
- Which customer segments contribute the most revenue?
- How does service quality vary across vehicle categories?

Analyzing these operational metrics manually is time-consuming and often fails to reveal actionable insights.

---

# Solution

This Power BI dashboard centralizes operational data into an interactive analytics platform that enables business users to:

- Monitor bookings in real time
- Analyze revenue trends
- Track customer and driver behavior
- Identify cancellation patterns
- Measure service quality
- Evaluate operational efficiency
- Support strategic decision-making

---

# Project Objectives

The dashboard was designed with the following objectives:

- Analyze overall taxi booking performance
- Monitor ride completion and cancellation rates
- Evaluate customer and driver behavior
- Identify high-performing vehicle categories
- Analyze revenue generation
- Measure service quality
- Study payment preferences
- Improve customer retention
- Enable data-driven business decisions

---

# Dashboard Features

| Feature | Description |
|----------|-------------|
| KPI Dashboard | Executive summary of business performance |
| Booking Analytics | Ride trends and booking distribution |
| Revenue Analytics | Revenue and payment insights |
| Vehicle Analysis | Performance across vehicle categories |
| Cancellation Dashboard | Customer & driver cancellation analysis |
| Ratings Dashboard | Service quality evaluation |
| Customer Analytics | Customer behavior insights |
| Interactive Filters | Dynamic slicing and drill-down |
| Time-Series Analysis | Monthly and weekly trend analysis |
| Executive Reporting | Actionable business insights |

---

# Key Performance Indicators

The dashboard tracks several operational and financial KPIs, including:

### Operational KPIs

- Total Bookings
- Completed Rides
- Cancelled Rides
- Completion Rate
- Cancellation Rate
- Average Ride Distance

---

### Financial KPIs

- Total Revenue
- Revenue per Ride
- Revenue per Kilometer
- Successful Booking Revenue

---

### Customer KPIs

- Customer Ratings
- Customer Retention
- Premium Customer Revenue
- Payment Method Distribution

---

### Driver KPIs

- Driver Ratings
- Driver Cancellation Rate
- Vehicle Utilization
- Ride Completion Performance

---

# Business Value

This dashboard enables business stakeholders to:

- Identify operational inefficiencies
- Improve customer satisfaction
- Optimize fleet allocation
- Increase revenue
- Reduce ride cancellations
- Enhance customer retention
- Support strategic planning through analytics

---

# Project Highlights

- End-to-end Business Intelligence solution
- Interactive executive dashboard
- Multiple analytics pages
- KPI-driven reporting
- Dynamic filtering and drill-down
- Power Query data transformation
- DAX-based business metrics
- Data modeling using relational concepts
- Business recommendations
- Professional dashboard design

---

# Repository Snapshot

| Category | Details |
|----------|---------|
| Domain | Transportation Analytics |
| Project Type | Business Intelligence Dashboard |
| Visualization Tool | Power BI |
| Data Source | Excel Dataset |
| Data Cleaning | Power Query |
| KPI Development | DAX |
| Dashboard Pages | 6 |
| Dataset Size | 148K+ Ride Bookings |

# Dashboard Architecture

The Taxi Ride Analytics Dashboard follows a structured Business Intelligence workflow, transforming raw operational data into interactive dashboards that support data-driven decision-making.

```text
                 Excel Dataset
                       │
                       ▼
              Power Query (ETL)
                       │
       Data Cleaning & Transformation
                       │
                       ▼
              Data Modeling
             (Relationships)
                       │
                       ▼
             DAX Calculations
                       │
                       ▼
         Interactive Power BI Dashboard
                       │
                       ▼
      Business Insights & Decision Support
```

---

# Analytics Workflow

The project follows the complete Business Intelligence lifecycle.

```text
Raw Taxi Booking Data

        │

        ▼

Data Cleaning

        │

        ▼

Data Transformation

        │

        ▼

Data Modeling

        │

        ▼

DAX Measure Creation

        │

        ▼

Dashboard Development

        │

        ▼

Business Insights

        │

        ▼

Executive Reporting
```

---

# Technology Stack

## Business Intelligence

- Power BI Desktop

---

## Data Preparation

- Power Query
- Microsoft Excel

---

## Data Modeling

- Relationships
- Star Schema Concepts
- Data Validation

---

## Data Analysis

- DAX
- Calculated Measures
- KPIs
- Aggregations

---

## Visualization

- KPI Cards
- Line Charts
- Pie Charts
- Bar Charts
- Slicers
- Interactive Filters
- Drill-through Analysis

---

# Technology Summary

| Layer | Technologies |
|--------|--------------|
| BI Tool | Power BI Desktop |
| Data Source | Microsoft Excel |
| ETL | Power Query |
| Data Modeling | Relationships, Star Schema |
| Business Logic | DAX |
| Visualization | Interactive Dashboards |
| Analytics | KPI Development |
| Reporting | Executive Dashboards |

---

# Dataset Overview

The project uses a structured taxi ride booking dataset containing operational, financial, and customer-related information.

### Core Attributes

- Booking ID
- Booking Date
- Ride Status
- Vehicle Type
- Booking Value
- Ride Distance
- Payment Method
- Customer Rating
- Driver Rating
- Cancellation Reason
- Customer Segment

The dataset represents more than **148,000 ride bookings**, enabling comprehensive operational and financial analysis.

---

# Data Preparation

Before building the dashboard, the dataset underwent extensive preprocessing using Power Query.

## Cleaning Operations

- Removed duplicate records
- Handled missing values
- Corrected inconsistent data
- Standardized categorical values
- Converted date columns
- Verified data quality

---

## Data Transformation

Several transformations were applied to improve reporting accuracy.

These included:

- Creating calculated columns
- Formatting date fields
- Categorizing ride distances
- Creating revenue groups
- Deriving business metrics
- Preparing dimensions for reporting

---

# Data Modeling

A well-structured data model is essential for efficient reporting and DAX calculations.

The dashboard follows relational modeling principles to ensure:

- Faster report performance
- Reduced redundancy
- Accurate aggregations
- Simplified measure creation

---

# DAX Implementation

Business KPIs were developed using Data Analysis Expressions (DAX).

Examples include:

- Total Bookings
- Completed Rides
- Cancelled Rides
- Cancellation Rate
- Total Revenue
- Revenue per Kilometer
- Customer Retention Rate
- Average Customer Rating
- Average Driver Rating
- Service Quality Score

These measures enable dynamic calculations that automatically respond to filters and slicers.

---

# Dashboard Pages

The report consists of six interactive dashboards, each focusing on a different aspect of business performance.

---

# 1. Executive Overview Dashboard

Provides a high-level summary of overall taxi operations.

### Includes

- Total Bookings
- Booking Status
- Monthly Trends
- Revenue Overview
- Ride Distribution

### Business Value

Offers executives a quick snapshot of operational performance and overall business health.

---

# 2. Vehicle Performance Dashboard

Analyzes operational performance across vehicle categories.

### Metrics

- Revenue by Vehicle
- Average Distance
- Total Distance
- Successful Bookings
- Booking Value

### Vehicle Categories

- Auto
- Bike
- eBike
- Go Mini
- Go Sedan
- Premier Sedan
- Uber XL

### Business Value

Supports fleet optimization and identifies high-performing vehicle segments.

---

# 3. Revenue & Payment Dashboard

Focuses on financial performance and payment behavior.

### KPIs

- Total Revenue
- Revenue per Ride
- Revenue per Kilometer
- Booking Value
- Payment Distribution

### Payment Methods

- UPI
- Cash
- Credit Card
- Debit Card
- Wallet

### Business Value

Helps monitor revenue streams and understand customer payment preferences.

---

# 4. Cancellation Dashboard

Examines ride cancellations from both customer and driver perspectives.

### Customer Reasons

- Change of Plans
- Driver Delay
- Wrong Address
- Driver Requested Cancellation
- AC Not Working

### Driver Reasons

- Vehicle Issues
- Distance Concerns
- Customer Issues
- Personal Reasons

### Business Value

Highlights operational bottlenecks and supports strategies to reduce cancellations.

---

# 5. Customer & Driver Ratings Dashboard

Evaluates service quality through customer feedback.

### Metrics

- Customer Rating
- Driver Rating
- Vehicle-wise Ratings
- Average Satisfaction

### Business Value

Measures service performance and identifies opportunities for quality improvement.

---

# 6. Service Quality Dashboard

Provides advanced operational insights.

### KPIs

- Customer Retention
- Service Quality Score
- Revenue per Kilometer
- Peak Hour Performance
- Weekly Trends
- Monthly Trends

### Business Value

Supports long-term strategic planning through comprehensive performance monitoring.

---

# Dashboard Navigation

```text
Executive Overview
        │
        ▼
Vehicle Performance
        │
        ▼
Revenue Analysis
        │
        ▼
Cancellation Analysis
        │
        ▼
Ratings Dashboard
        │
        ▼
Service Quality Dashboard
```

---

# Interactive Features

The dashboard includes several interactive capabilities that improve usability.

### Features

- Dynamic slicers
- Cross-filtering
- Drill-down analysis
- KPI cards
- Responsive charts
- Category filtering
- Time-based filtering
- Interactive navigation

---

# Project Structure

```text
Taxi-Ride-Analytics-PowerBI-Dashboard/
│
├── Taxi_Ride_Analytics.pbix
├── rideBookings.xlsx
├── README.md
│
├── screenshots/
│   ├── overview_dashboard.png
│   ├── vehicle_dashboard.png
│   ├── revenue_dashboard.png
│   ├── cancellation_dashboard.png
│   ├── ratings_dashboard.png
│   └── service_quality_dashboard.png
│
└── assets/
    └── architecture.png
```

---

# Dashboard Design Principles

The dashboard was developed following modern Business Intelligence best practices.

- Clean and consistent layout
- Executive-friendly KPI presentation
- Interactive filtering
- Business-oriented storytelling
- Minimal visual clutter
- Consistent color palette
- Easy navigation
- Actionable insights over raw data

---

# Getting Started

Follow the steps below to explore the Taxi Ride Analytics Dashboard locally.

---

# Prerequisites

Ensure the following software is installed on your system.

| Software | Version |
|-----------|---------|
| Power BI Desktop | Latest Version |
| Microsoft Excel | 2019 or Later (Optional) |
| Windows OS | Recommended |

---

# Repository Contents

```text
Taxi-Ride-Analytics-PowerBI-Dashboard/

│
├── Taxi_Ride_Analytics.pbix
│
├── rideBookings.xlsx
│
├── README.md
│
└── screenshots/
```

---

# Opening the Dashboard

### Step 1

Clone the repository.

```bash
git clone https://github.com/UtkarshGupta-22/Taxi-Ride-Analytics-PowerBI-Dashboard.git
```

---

### Step 2

Open

```text
Taxi_Ride_Analytics.pbix
```

using **Microsoft Power BI Desktop**.

---

### Step 3

If prompted, refresh the dataset.

```text
Home
    ↓
Refresh
```

Power BI will automatically update all visuals using the latest dataset.

---

# Dashboard Walkthrough

The report consists of six interactive dashboards, each addressing a different business objective.

---

## Executive Overview

Designed for senior management to quickly understand business performance.

### Monitor

- Overall bookings
- Revenue
- Ride completion
- Cancellation trends
- Monthly performance

---

## Vehicle Performance

Analyze operational efficiency across vehicle categories.

Questions answered:

- Which vehicle generates the highest revenue?
- Which vehicle travels the greatest distance?
- Which category receives the highest bookings?
- Which fleet segment should be expanded?

---

## Revenue Analysis

Focuses on financial performance.

Explore

- Revenue trends
- Revenue by vehicle
- Revenue by payment method
- Revenue per kilometer
- Premium customer contribution

---

## Cancellation Analysis

Provides insights into operational inefficiencies.

Analyze

- Customer cancellation reasons
- Driver cancellation reasons
- Cancellation percentage
- Vehicle-specific cancellation trends

---

## Customer & Driver Ratings

Understand service quality.

Track

- Customer satisfaction
- Driver performance
- Vehicle-wise ratings
- Overall service experience

---

## Service Quality Dashboard

Advanced dashboard for strategic analysis.

Includes

- Customer retention
- Revenue trends
- Peak hour analysis
- Service quality KPIs
- Weekly and monthly performance

---

# Dashboard Interaction

Users can interact with reports using built-in Power BI features.

### Supported Interactions

- Slicers
- Filters
- Cross-filtering
- Drill-down
- Drill-through
- Hover Tooltips
- Dynamic KPI Updates

These interactions allow users to explore the dataset from multiple business perspectives without modifying the underlying data.

---

# Business Questions Answered

The dashboard helps answer several important operational questions.

### Operations

- How many rides were completed?
- What percentage of rides were cancelled?
- Which vehicle performs best?

---

### Finance

- Which vehicle category generates maximum revenue?
- Which payment method is most popular?
- What is the revenue trend over time?

---

### Customer Analytics

- Are customers satisfied?
- Which services receive better ratings?
- Which customer segments generate higher revenue?

---

### Operational Efficiency

- Why are rides cancelled?
- Which cancellation reasons occur most frequently?
- Where can operational improvements be made?

---

# Key Business Insights

## Booking Performance

- More than **148,000 taxi bookings** were analyzed.
- The majority of rides were successfully completed.
- Booking demand remained relatively stable throughout the analysis period.

---

## Revenue Performance

- Premium vehicle categories contributed significantly to total revenue.
- Digital payment methods—especially **UPI**—were the preferred payment option.
- Evening booking periods generated the highest revenue.

---

## Customer Behavior

- Premium customers contributed a larger share of booking value.
- Customer ratings remained consistently positive across most vehicle categories.
- Repeat customers significantly improved overall revenue performance.

---

## Vehicle Utilization

- Certain vehicle categories consistently outperformed others in booking volume and revenue.
- Fleet utilization varied across vehicle types, highlighting opportunities for optimization.

---

## Cancellation Trends

- Customer and driver cancellations both contributed to operational losses.
- Several cancellation reasons occurred repeatedly, indicating process improvement opportunities.

---

# Business Recommendations

Based on the dashboard insights, several strategic recommendations can be made.

### Improve Fleet Allocation

Allocate more vehicles to high-demand categories during peak hours to maximize utilization and revenue.

---

### Reduce Ride Cancellations

Analyze recurring cancellation reasons and implement operational improvements such as:

- Better driver allocation
- Improved route optimization
- Enhanced customer communication

---

### Encourage Digital Payments

Promote UPI and digital payment incentives to reduce cash handling and improve transaction efficiency.

---

### Enhance Premium Services

Premium ride categories generate higher revenue and customer satisfaction.

Expanding premium offerings may improve profitability.

---

### Improve Customer Retention

Introduce loyalty programs and targeted promotions for repeat customers to increase lifetime customer value.

---

# Performance Summary

| Category | Outcome |
|----------|----------|
| Total Bookings | 148K+ |
| Dashboard Pages | 6 |
| KPIs Developed | 20+ |
| Interactive Visuals | Multiple |
| DAX Measures | Yes |
| Power Query Transformations | Yes |
| Dynamic Filters | Yes |

---

# Screenshots

Create a dedicated `screenshots/` folder inside the repository.

```text
screenshots/

├── overview_dashboard.png

├── vehicle_dashboard.png

├── revenue_dashboard.png

├── cancellation_dashboard.png

├── ratings_dashboard.png

└── service_quality_dashboard.png
```

Display them within the README.

```markdown
## Executive Dashboard

![Overview](screenshots/overview_dashboard.png)

---

## Vehicle Performance

![Vehicle Dashboard](screenshots/vehicle_dashboard.png)

---

## Revenue Dashboard

![Revenue Dashboard](screenshots/revenue_dashboard.png)

---

## Cancellation Dashboard

![Cancellation Dashboard](screenshots/cancellation_dashboard.png)

---

## Customer & Driver Ratings

![Ratings Dashboard](screenshots/ratings_dashboard.png)

---

## Service Quality Dashboard

![Service Quality Dashboard](screenshots/service_quality_dashboard.png)
```

---

# Dashboard Highlights

The project demonstrates practical Business Intelligence capabilities through:

- Interactive executive dashboards
- KPI-driven reporting
- Data storytelling
- Financial analysis
- Operational analytics
- Customer analytics
- Service quality monitoring
- Dynamic business reporting
- Decision support analytics

---

# Use Cases

This dashboard can support decision-making for:

- Taxi Aggregators
- Ride-Hailing Platforms
- Fleet Operators
- Business Analysts
- Operations Managers
- Revenue Analysts
- Customer Success Teams
- Executive Leadership

---

# Project Deliverables

The repository includes:

- Power BI Dashboard (.pbix)
- Source Dataset (.xlsx)
- Project Documentation
- Dashboard Screenshots
- Business Insights
- Strategic Recommendations

---

# Data Modeling

A robust data model is the foundation of any Business Intelligence solution.

This project follows relational modeling principles to ensure efficient query performance, accurate aggregations, and scalable dashboard development.

The data model was designed to:

- Minimize data redundancy
- Improve report performance
- Enable reusable DAX measures
- Support dynamic filtering
- Maintain data consistency

---

# ETL Workflow using Power Query

The dataset was processed using Power Query before visualization.

```text
Excel Dataset
        │
        ▼
Import Data
        │
        ▼
Remove Duplicates
        │
        ▼
Handle Missing Values
        │
        ▼
Standardize Categories
        │
        ▼
Format Date Columns
        │
        ▼
Create Derived Columns
        │
        ▼
Load into Power BI
```

---

# DAX Measures

Business KPIs were developed using **Data Analysis Expressions (DAX)** to provide dynamic calculations that automatically respond to report filters and slicers.

### Operational KPIs

- Total Bookings
- Completed Rides
- Cancelled Rides
- Cancellation Rate
- Completion Rate

---

### Revenue KPIs

- Total Revenue
- Successful Booking Revenue
- Revenue per Ride
- Revenue per Kilometer

---

### Customer KPIs

- Average Customer Rating
- Customer Retention Rate
- Premium Customer Revenue

---

### Driver KPIs

- Average Driver Rating
- Driver Cancellation Rate
- Vehicle Performance Score

---

### Service KPIs

- Service Quality Score
- Peak Hour Performance
- Monthly Growth
- Weekly Booking Trend

---

# Dashboard Design Philosophy

The dashboard was designed with a business-first approach.

Key principles include:

- Executive-friendly layout
- Minimal visual clutter
- Consistent color palette
- Logical page flow
- Interactive storytelling
- Easy KPI interpretation
- Actionable insights

Each page answers a specific business question rather than simply displaying charts.

---

# Analytical Approach

The project follows a structured analytics methodology.

```text
Business Problem

↓

Data Collection

↓

Data Cleaning

↓

Data Transformation

↓

Data Modeling

↓

KPI Development

↓

Dashboard Design

↓

Insight Generation

↓

Business Recommendations
```

---

# Business Impact

The dashboard enables organizations to make informed decisions in several areas.

### Operational Optimization

- Improve fleet utilization
- Reduce ride cancellations
- Increase ride completion rates

---

### Financial Performance

- Monitor revenue trends
- Optimize pricing strategies
- Analyze payment behavior

---

### Customer Experience

- Improve customer satisfaction
- Monitor service quality
- Increase customer retention

---

### Strategic Planning

- Identify growth opportunities
- Evaluate vehicle performance
- Support executive reporting

---

# Challenges Faced

Developing a comprehensive Business Intelligence dashboard involved several practical challenges.

## Data Quality

The raw dataset contained inconsistencies that required cleaning, validation, and standardization before analysis.

---

## KPI Development

Defining meaningful business metrics required understanding operational workflows and translating them into dynamic DAX measures.

---

## Dashboard Performance

Balancing report responsiveness with multiple visuals and interactive filters required efficient data modeling and optimized calculations.

---

## Storytelling with Data

Presenting complex operational metrics in a way that is intuitive for business stakeholders required careful dashboard layout and visualization design.

---

# Learning Outcomes

This project strengthened practical experience in:

### Business Intelligence

- Interactive Dashboard Development
- KPI Design
- Executive Reporting
- Data Storytelling

---

### Power BI

- Dashboard Development
- Data Modeling
- Power Query
- Report Optimization

---

### Data Analysis

- Exploratory Data Analysis (EDA)
- Trend Analysis
- Revenue Analysis
- Customer Analytics
- Operational Analytics

---

### DAX

- Calculated Measures
- Time Intelligence
- Aggregations
- Dynamic KPIs

---

### Business Analytics

- Financial Analysis
- Performance Monitoring
- Decision Support
- Strategic Recommendations

---

# Future Roadmap

The project can be extended with advanced Business Intelligence capabilities.

### Predictive Analytics

- Ride Demand Forecasting
- Customer Churn Prediction
- Revenue Forecasting
- Driver Demand Estimation

---

### Advanced Analytics

- Dynamic Pricing Recommendations
- Customer Segmentation
- Driver Performance Scoring
- Profitability Analysis

---

### Geographic Intelligence

- Ride Heatmaps
- Route Optimization
- Pickup & Drop-off Analysis
- Regional Demand Analysis

---

### Enterprise Features

- Live Database Integration
- SQL Server Connectivity
- Scheduled Data Refresh
- Incremental Refresh
- Row-Level Security (RLS)
- Power BI Service Deployment

---

# Skills Demonstrated

| Domain | Technologies & Concepts |
|---------|-------------------------|
| Business Intelligence | Power BI Desktop |
| Data Preparation | Power Query |
| Data Analysis | Exploratory Data Analysis (EDA) |
| Data Modeling | Relationships, Star Schema Concepts |
| Business Logic | DAX |
| Dashboard Development | Interactive Reports, KPI Cards |
| Visualization | Charts, Slicers, Drill-down |
| Spreadsheet Analysis | Microsoft Excel |
| Business Analytics | Revenue, Customer & Operational Analysis |
| Reporting | Executive Dashboards & Data Storytelling |

---

# Repository Highlights

- End-to-end Business Intelligence project
- Interactive Power BI dashboard
- 148K+ ride booking records analyzed
- Executive KPI reporting
- Dynamic DAX calculations
- Power Query transformations
- Multi-page dashboard design
- Operational, financial, and customer analytics
- Actionable business recommendations
- Production-style BI solution

---

# Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

Please ensure all enhancements are well documented and maintain the existing dashboard design principles.

---

# Acknowledgements

This project was built using industry-standard Business Intelligence tools and techniques.

Special thanks to:

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX
- The Power BI Community for learning resources and best practices

---

# License

This project is licensed under the **MIT License**.

It is intended for educational, portfolio, and demonstration purposes.

---

<div align="center">

# Taxi Ride Analytics Dashboard

### Transforming Transportation Data into Actionable Business Insights

---

**Built with Power BI • Power Query • DAX • Microsoft Excel**

Business Intelligence • Data Analytics • KPI Reporting • Dashboard Development • Executive Reporting

---

**Developed by Utkarsh Gupta**

**B.Tech Computer Science (Data Science)**

If you found this project useful or insightful, consider giving it a ⭐ on GitHub.

*"Turning raw operational data into strategic business decisions through analytics and visualization."*

</div>
| Analytics Type | Descriptive & Diagnostic Analytics |

---
