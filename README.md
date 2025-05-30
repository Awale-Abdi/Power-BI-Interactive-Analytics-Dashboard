<h1 align="center">Hotel Booking Analytics Dashboard – Power BI Report on Guest Patterns & Revenue Drivers</h1>

This solo-developed **Power BI dashboard** was built under a **tight 2-day deadline** for a graduate-level *Visualization Challenge*, taught by a current **Senior Director of AI & Product at Oracle** and former **Head of NLP at AWS**. While completing the assignment, I also **mentored multiple classmates**, explaining Power BI best practices, DAX logic, and star-schema modeling—demonstrating both **technical expertise** and **leadership under pressure**.

Using the `hotel_bookings_viz.csv` dataset (~119K rows × 32 columns, 16MB), I designed a **star-schema data model**, created **custom KPIs using DAX**, and built **three interactive dashboards** that uncover root causes of cancellations and revenue loss. The final submission earned a **97/100**, with top marks for insight generation, data storytelling, and dashboard clarity—delivered through a concise **7-minute executive video presentation** tailored to stakeholders.


---

## 🎯 Objective

To analyze hotel booking behavior and cancellations and deliver actionable business recommendations using Power BI, DAX, and Power Query—framed through interactive, executive-friendly dashboards.

---

## 📁 Project Scope

- **Timeline**: Completed in 2 days  
- **Peer Collaboration**: Guided peers in building star schemas, calculated fields, and Power BI visuals whilst working on own project 
- **Dataset**: `hotel_bookings_viz.csv` (~119,390 rows, 32 columns)  
- **Modeling**:  
  - Built a **star schema** with 5 dimension tables, 1 fact table, and a calendar table using `List.Dates()`  
  - Created **DAX-calculated measures and columns** to track:
    - Cancellation Rate
    - Lead Time Impact
    - Special Request Frequency
    - ADR by Month, Hotel Type, and Room Type
- **Data Cleaning**:  
  - Removed redundant columns  
  - Converted binary fields into readable formats  
  - Corrected data types and handled outliers (e.g., 0 adults, 9 babies)

---

## 📁 Project Structure

- `Datasets/`  
  - `hotel_bookings_viz.csv` – original hotel booking data (~119K rows × 32 columns) used for modeling and dashboarding

- `Outputs/`  
  - `A1 - Visualization Challenge by Awale Abdi-.pbix` – full Power BI report file containing:
    - Star schema model (1 fact table, 5 dimension tables, calendar table)
    - 3 interactive dashboards with slicers, custom DAX, and drill-throughs
    - Embedded stakeholder-ready video presentation (~7 mins)

---

## 🧠 Key Findings from Dashboard Narratives

**Dashboard 1 – Cancellation Patterns**  
- **Online Travel Agencies (OTA)** show the highest cancellation rates  
- **Western European markets** (France, UK, Spain) have the most cancellations  
- **Special requests inversely correlate with cancellations** (more requests = more commitment)  
- **New guests** cancel far more often than repeat guests  
- **Portugal** skewed the data due to its dominance—removing it revealed deeper patterns  

**Dashboard 2 – Customer Demographics & Financial Impact**  
- **Couples** (regardless of children) are the top source of lost revenue  
- High-revenue markets like **Italy, France, and Brazil** also suffer from high cancellation losses  
- Summer months show peak loss due to couple-driven cancellations  
- Suggested targeted loyalty programs, romantic getaway bundles, and more flexible terms  

**Dashboard 3 – Room Types & Agent Behavior**  
- **Agent 9** triggered unusually high cancellations  
- **Rooms A, D, F, E, and G** had high ADRs but lost the most revenue  
- **City hotels** are more popular among couples than resorts  
- Shorter lead times reduce cancellations, especially among couples  
- Suggested better direct booking incentives, room repricing, and stricter cancellation rules

---

## 📊 Tools & Techniques Used

- 📈 **Power BI** – Report development, dashboard design, and DAX  
- 🧼 **Power Query Editor** – Data shaping, ETL, and cleaning  
- 🧩 **DAX** – Calculated measures and KPIs  
- 🔗 **Star Schema Modeling** – 1 Fact Table + 5 Dimensions + Calendar Table  
- 🎥 **Presentation Video** – 6-minute walkthrough, embedded into the report

---

## 📝 Instructor Feedback

- “Excellent submission. Good storytelling and insights.”  
- “Great identification of high-risk agents and segments. Clean visuals.”  
- “Be mindful of filtering out key data like Portugal—it may hide trends.”

---

## 🧠 Recommendations Summary

- Incentivize repeat stays and special requests to reduce cancellations  
- Investigate OTA policies and promote **direct booking via hotel website**  
- Tailor marketing campaigns for **Western European couples**  
- Audit **Agent 9** and reprice **high-ADR rooms** with cancellation issues  
- Introduce **flexible booking windows, early bird deals**, and pre-arrival engagement  

---

### **Contact Me**

- **Email**: Awaleiabdi@outlook.com  
- **LinkedIn**: [linkedin.com/in/awale-abdi](https://www.linkedin.com/in/awale-abdi/)
