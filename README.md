<h1 align="center">Business Intelligence & Customer Analytics | Hotel Booking Performance Dashboard with Power BI</h1>

This project showcases an **end-to-end Business Intelligence workflow** built using approximately **119,000 hotel booking records**. I developed it to demonstrate enterprise-scale data preparation, dimensional modeling, KPI development, DAX calculations, dashboard design, customer analytics, and executive reporting.

Although the project uses **hotel booking data** as its case study, the Business Intelligence techniques I apply, such as data modeling, KPI development, customer segmentation, revenue analysis, cancellation analysis, and interactive dashboard design, are broadly transferable to hospitality, retail, healthcare, finance, operations, and other industries requiring performance reporting and decision support.

Using **Power BI**, **Power Query**, DAX, and dimensional modeling, I transformed raw booking data into interactive executive dashboards that identify revenue drivers, customer behavior patterns, booking trends, and operational opportunities.

As an additional challenge, I independently completed the entire project within **two days** while mentoring classmates on star-schema modeling, DAX, and dashboard development. The final submission earned **97/100** for its analytical insights, storytelling, and dashboard design **from my professor at the time who is currently the Vice President of AI at Oracle.**

## 💼 Analytical Goals

This project focuses on applying Business Intelligence and data visualization techniques to identify the factors influencing hotel booking performance, cancellations, customer behavior, and revenue generation.

The primary goals were to:

- Prepare and model booking data for Business Intelligence reporting
- Analyze booking cancellations and revenue loss
- Identify customer segments and behavioral patterns
- Develop interactive executive dashboards using Power BI
- Build custom KPIs using DAX
- Translate analytical findings into actionable business recommendations

## 🏗️ Solution Architecture

#### Business Intelligence Workflow

- Data preparation
- Power Query transformation
- Star schema modeling
- Calendar table generation
- DAX development
- KPI creation
- Dashboard development
- Executive reporting

#### Data

- **Dataset:** Hotel Booking Demand Dataset
- **Size:** ~119,390 booking records
- **Features:** 32 variables
- **Storage Format:** CSV

#### Data Preparation

Performed structured data preparation by:

- Cleaning booking records
- Removing redundant attributes
- Correcting data types
- Handling invalid and outlier observations
- Transforming categorical variables into business-friendly formats
- Preparing dimensional tables for analytical modeling

#### Data Modeling

Designed an enterprise-style dimensional model consisting of:

- 1 Fact Table
- 5 Dimension Tables
- Calendar Table using **List.Dates()**
- Star Schema relationships optimized for Power BI reporting

#### KPI Development

Developed custom DAX measures to evaluate:

- Cancellation Rate
- Average Daily Rate (ADR)
- Lead Time
- Special Request Frequency
- Revenue by Customer Segment
- Revenue by Hotel Type
- Revenue by Room Type

### Dashboard Development

Built three interactive executive dashboards focused on:

- Cancellation behavior
- Customer demographics
- Revenue performance
- Booking trends
- Operational decision support

## 📊 Analytical Insights

#### Cancellation Analysis

- Online Travel Agencies (OTAs) generated the highest cancellation rates.
- New guests cancelled significantly more often than repeat customers.
- Customers submitting more special requests demonstrated stronger booking commitment.
- Western European markets contributed disproportionately to booking cancellations.

#### Customer & Revenue Analysis

- Couples represented the largest source of cancellation-related revenue loss.
- High-value markets such as France, Italy, and Brazil experienced substantial financial impact.
- Peak-season cancellations produced the greatest revenue losses.

#### Operational Analysis

- Agent 9 generated unusually high cancellation activity.
- High-ADR room types experienced the greatest revenue leakage.
- City hotels attracted significantly more couple bookings than resort hotels.
- Shorter booking lead times generally reduced cancellation rates.

### Quantitative Analysis

- Customer segmentation revealed meaningful behavioral differences across booking channels.
- Interactive dashboards enabled rapid identification of operational bottlenecks.
- DAX-driven KPIs provided executive-level visibility into revenue performance and cancellation trends.
- Dimensional modeling significantly improved analytical flexibility and reporting performance.

## 📈 Analytical Recommendations

- Encourage direct bookings to reduce OTA-related cancellations.
- Develop loyalty programs targeting repeat guests.
- Personalize marketing campaigns toward high-value customer segments.
- Review high-risk travel agents and booking channels.
- Optimize pricing strategies for premium room categories.
- Introduce flexible cancellation policies and proactive customer engagement.

## 🛠️ Technical Skills Demonstrated

### Business Intelligence

- Power BI
- Dashboard Development
- Executive Reporting
- KPI Development

### Data Modeling

- Star Schema
- Fact & Dimension Modeling
- Calendar Tables
- Relational Modeling

### Data Transformation

- Power Query
- ETL
- Data Cleaning
- Data Validation

### DAX

- Calculated Measures
- Calculated Columns
- Time Intelligence
- KPI Development

### Data Analysis

- Customer Segmentation
- Revenue Analysis
- Cancellation Analysis
- Exploratory Data Analysis (EDA)
- Business Intelligence

## 💡 What This Project Demonstrates

This project demonstrates the ability to independently design and deliver an end-to-end Business Intelligence solution using enterprise-scale booking data.

Specifically, it showcases proficiency in:

- Business Intelligence
- Power BI Dashboard Development
- Data Modeling
- Power Query
- DAX
- KPI Development
- Customer Analytics
- Revenue Analysis
- Executive Reporting
- Translating analytical findings into actionable business insights

## 📁 Repository Structure

```text
Datasets/
    hotel_bookings_viz.csv

Outputs/
    A1 - Visualization Challenge by Awale Abdi.pbix
```

## 📋 Replicating the Project

#### Clone the Repository

```bash
git clone https://github.com/Awale-Abdi/Business-Intelligence-Customer-Analytics-PowerBI.git
```

#### Open the Project

The repository includes:

- Original dataset
- Complete Power BI report
- Star schema data model
- Interactive dashboards
- Embedded executive presentation

Open:

```text
Outputs/
```

Then launch:

```text
A1 - Visualization Challenge by Awale Abdi.pbix
```

Explore the interactive dashboards to review the complete Business Intelligence workflow, including data preparation, dimensional modeling, DAX calculations, KPI development, customer segmentation, and executive reporting.

## 📬 Contact Me

**Email**

Awaleiabdi@outlook.com

**LinkedIn**

https://www.linkedin.com/in/awale-abdi/
