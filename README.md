# Hotel Booking Analytics Dashboard – Power BI Report on Guest Patterns & Revenue Drivers

This solo-developed **Power BI dashboard** was built under timed exam conditions for a graduate-level *Visualization Challenge*. Using the `hotel_bookings_viz.csv` dataset (~119K rows × 32 columns, 16MB), I designed a **star-schema data model**, implemented **calculated columns and measures using DAX**, and built **interactive dashboards** that uncover patterns in guest behavior and booking cancellations.

The report identified **high-risk market segments**, behavioral patterns in guest types, and atypical agent activity. My submission received **97/100**, with praise for analytical depth, storytelling, and technical execution.

---

## 🎯 Objective

To analyze hotel booking trends, cancellations, and revenue dynamics through clean and interactive Power BI dashboards built on a star-schema model.

---

## 📁 Project Scope

- **Dataset**: `hotel_bookings_viz.csv` (~119,390 rows, 32 columns, 16.07 MB)
- **Data Modeling**:
  - Built a **star schema** with fact and dimension tables in Power BI
  - Enhanced the model with **DAX-calculated fields** for KPIs like:
    - Cancellation Rate (%)
    - ADR Adjusted by Month and Hotel Type
    - Stay Length Categories
    - Customer Segments by Behavior
- **Key Analytical Focus**:
  - High cancellations in *Online TA* and *Western Europe*
  - *Couples* had the highest cancellation rate regardless of children
  - *Agent ID 9* showed an atypical cancellation pattern
  - Filtered *Portugal* from regional comparisons to reduce skew
  - Addressed **data outliers** (e.g., bookings with 0 adults or 9 babies)
- **Visuals**:
  - Heatmaps, time-series, bar charts, geographic maps
  - Slicers and tooltips for dynamic exploration
  - Drill-through to detailed views by agent and market segment

---

## 🧠 Key Insights

- **Online TA** is the riskiest segment for cancellations  
- **Couples** are the primary drivers of cancellation, more so than family size  
- **Agent 9**'s performance suggests internal policy review  
- **Resort hotels** exhibit greater seasonal pricing variability  
- Filtering **Portugal** prevented bias in cancellation heatmaps

---

## 🛠️ Tools Used

- 🧱 **Power BI** – dashboard creation, DAX, data modeling (star schema)  
- 🧼 **Power Query Editor** – for ETL tasks and data shaping  
- 📐 **DAX** – custom measures, calculated columns, KPIs  
- 🎥 **Video Presentation** – Embedded 6-minute walkthrough of analysis

---

## 🎓 Submission Context

- **Assignment**: Individual Visualization Challenge  
- **Score**: 97/100  
- **Instructor Feedback**:
  - “Excellent submission. Good storytelling and insights.”
  - “Be mindful of filtering out key data like Portugal — it may hide trends.”
  - “Great identification of high-risk agents and segments. Clean visuals.”

---

### 📬 Contact

- **Email**: Awaleiabdi@outlook.com  
- **LinkedIn**: [linkedin.com/in/awale-abdi](https://www.linkedin.com/in/awale-abdi/)
