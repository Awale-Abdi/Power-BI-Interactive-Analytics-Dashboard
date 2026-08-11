<h1 align="center">Business Intelligence & Customer Analytics | Interactive Power BI Dashboard</h1>

This project showcases an **end-to-end Business Intelligence workflow** built using approximately **119,000 hotel booking records**. I developed it to demonstrate enterprise-scale data preparation, dimensional modeling, DAX development, KPI creation, customer analytics, dashboard design, and executive reporting.

Although the project uses **hotel booking data** as its case study, the Business Intelligence techniques applied throughout such as customer segmentation, revenue analysis, cancellation analysis, dimensional modeling, and interactive dashboard development are broadly transferable to hospitality, retail, finance, healthcare, operations, and other industries requiring performance reporting and decision support.

Using **Power BI**, **Power Query**, DAX, and star-schema modeling, I transformed raw booking data into interactive executive dashboards that uncover booking behavior, revenue drivers, cancellation trends, and operational opportunities.

As an additional challenge, I independently completed the project within **two days** while mentoring classmates on dimensional modeling, DAX, and dashboard development. The final submission earned **97/100** for its analytical insights, storytelling, and dashboard design **from my professor at the time who is currently the Vice President of AI at Oracle.**


## 🎥 Executive Dashboard Walkthrough

Alongside the interactive Power BI report, the repository includes a concise **7-minute executive presentation** designed for non-technical stakeholders.

Rather than requiring viewers to explore every dashboard manually, the walkthrough summarizes:

- Business problem and analytical objectives
- Data preparation and dimensional modeling
- KPI development using DAX
- Dashboard walkthrough
- Customer behavior analysis
- Cancellation trends
- Revenue drivers
- Operational insights
- Business recommendations

The presentation demonstrates the ability to communicate complex analytical findings clearly and translate dashboard insights into executive-level decision support.

## 💼 Analytical Goals

This project applies Business Intelligence techniques to identify the factors influencing hotel booking performance, customer behavior, cancellations, and revenue generation.

The primary objectives were to:

- Prepare and model booking data for Business Intelligence reporting
- Analyze cancellation behavior and revenue loss
- Identify customer segments and booking patterns
- Develop executive dashboards for interactive analysis
- Build reusable KPIs using DAX
- Translate analytical findings into actionable business recommendations


## 🏗️ Solution Architecture

#### Workflow

```text
Raw Parquet Datasets
        ↓
Amazon S3
        ↓
Power Query ETL
        ↓
Data Cleaning & Transformation
        ↓
Feature Engineering
        ↓
Dimensional Modeling
        ↓
Star Schema
        ↓
DAX & KPI Development
        ↓
Interactive Power BI Dashboards
        ↓
Executive Reporting
```

#### Data

- **Dataset:** Hotel Booking Demand Dataset
- **Records:** ~119,390
- **Features:** 32
- **Format:** CSV

#### Data Preparation

Data preparation included:

- Cleaning booking records
- Removing redundant attributes
- Correcting data types
- Handling invalid observations and outliers
- Creating business-friendly categorical fields
- Preparing dimensional tables for analytical modeling

#### Data Modeling

Designed an enterprise-style dimensional model consisting of:

- 1 Fact Table
- 5 Dimension Tables
- Calendar Table using **List.Dates()**
- Optimized Star Schema relationships

#### KPI Development

Custom DAX measures were created to evaluate:

- Cancellation Rate
- Average Daily Rate (ADR)
- Revenue
- Lead Time
- Special Request Frequency
- Booking Channel Performance
- Customer Segment Performance

#### Dashboard Development

Three interactive dashboards were developed covering:

- Cancellation Analysis
- Customer Analytics
- Revenue Performance
- Operational Performance
- Booking Trends

## 📊 Analytical Insights

#### Cancellation Analysis

- Online Travel Agencies (OTAs) generated the highest cancellation rates.
- New guests cancelled significantly more frequently than returning customers.
- Guests making more special requests demonstrated stronger booking commitment.
- Western European markets generated the largest share of cancellations.

#### Customer & Revenue Analysis

- Couples represented the greatest source of cancellation-related revenue loss.
- High-value markets including France, Italy, and Brazil experienced substantial financial losses.
- Peak-season cancellations produced the largest revenue impact.

#### Operational Analysis

- Agent 9 generated unusually high cancellation activity.
- Premium room categories produced the greatest revenue leakage.
- City hotels attracted significantly more couple bookings than resort hotels.
- Shorter booking lead times generally reduced cancellation rates.

#### Business Intelligence Outcomes

- Customer segmentation revealed meaningful behavioral differences across booking channels.
- Interactive dashboards enabled rapid identification of operational bottlenecks.
- DAX-driven KPIs provided executive visibility into performance metrics.
- Dimensional modeling significantly improved analytical flexibility and dashboard performance.

## 📈 Analytical Recommendations

- Encourage direct bookings to reduce OTA cancellations.
- Expand loyalty programs targeting repeat guests.
- Personalize campaigns for high-value customer segments.
- Review high-risk booking agents and channels.
- Optimize pricing for premium room categories.
- Introduce flexible booking policies and proactive customer engagement.

## 🛠️ Technical Skills Demonstrated

#### Business Intelligence

- Power BI
- Interactive Dashboard Development
- Executive Reporting
- KPI Development

#### Data Modeling

- Star Schema
- Fact & Dimension Modeling
- Calendar Tables
- Relational Modeling

#### Data Transformation

- Power Query
- ETL
- Data Cleaning
- Data Validation

#### DAX

- Calculated Measures
- Calculated Columns
- Time Intelligence
- KPI Development

#### Data Analysis

- Customer Analytics
- Revenue Analysis
- Cancellation Analysis
- Customer Segmentation
- Exploratory Data Analysis (EDA)

## 💡 What This Project Demonstrates

This project demonstrates the ability to independently design and deliver an end-to-end Business Intelligence solution using enterprise-scale booking data.

Specifically, it showcases proficiency in:

- Business Intelligence
- Interactive Dashboard Development
- Power BI
- Power Query
- DAX
- Data Modeling
- Customer Analytics
- Revenue Analysis
- KPI Development
- Executive Reporting
- Communicating analytical insights to technical and non-technical stakeholders

## 📁 Repository Structure

```text
Datasets/
    hotel_bookings_viz.csv

Outputs/
    A1 - Visualization Challenge by Awale Abdi.pbix (contains link to Executive Dashboard Walkthrough on YouTube)
```

## 📋 Replicating the Project

#### Clone the Repository

```bash
git clone https://github.com/Awale-Abdi/Power-BI-Interactive-Analytics-Dashboard.git
```

#### Explore the Repository

The repository includes:

- Original dataset
- Complete Power BI report
- Star-schema data model
- Interactive dashboards
- Executive dashboard walkthrough (~7 minutes)

For the quickest overview of the project, begin with the executive presentation before exploring the Power BI report.

Open:

```text
Outputs/
```

Then review:

```text
Executive Dashboard Walkthrough.mp4
```

or launch:

```text
A1 - Visualization Challenge by Awale Abdi.pbix
```

to interact directly with the dashboards and explore the complete Business Intelligence workflow.

## 📬 Contact Me

**Email**

Awaleiabdi@outlook.com

**LinkedIn**

https://www.linkedin.com/in/awale-abdi/
