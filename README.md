# uber-trip-data-analysis
https://github.com/Pri-ya23/uber-trip-data-analysis/blob/main/uber%20trip%20analysis.jpeg
https://github.com/Pri-ya23/uber-trip-data-analysis/blob/main/uber%20trip%20vechicle%20analysis.jpeg
🚗 Uber Trip data  Analysis: Dynamic Ride-Hailing Insights Dashboard

A dynamic, interactive data visualization tool built to explore Uber ride metrics—focusing on booking statuses, revenue trends, fleet vehicle performance, and customer/driver satisfaction ratings.

 2. Purpose

The Uber Analytics Dashboard is a visually engaging and analytical Power BI report designed to help operations managers and stakeholders monitor and analyze ride-hailing performance metrics across multiple vehicle categories. The dashboard focuses on highlighting key operational metrics like completed vs. lost bookings, peak revenue months, vehicle performance matrix, and customer satisfaction to drive data-driven decision-making for ride-hailing optimization.

 3. Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization platform used for report layout and interactive canvas creation.
* 📂 **Power Query** – Data transformation layer used to clean, shape, and prepare ride booking records.
* 🧠 **DAX (Data Analysis Expressions)** – Used for dynamic measures, calculating averages, contribution percentages, and time-series aggregations.
* 📝 **Data Modeling** – Structured relationships established to enable seamless cross-filtering across vehicle types, ratings, and timeline toggles.
* 📁 **File Format** – `.pbix` for development and `.jpg` for dashboard previews.

4. Data Source

The dataset used in this project was independently sourced and compiled specifically for this analysis. It features highly detailed booking records designed to simulate a comprehensive, real-world ride-hailing environment, tracking structural details such as booking statuses (Completed, Cancelled, Incomplete), vehicle types, total/average distances, customer and driver ratings, and revenue timelines across 12 months.

 5. Features / Highlights

 • Business Problem

The ride-hailing industry deals with massive volumes of daily transactions, making it challenging for operators to quickly identify operational bottlenecks, track lost revenue from cancelled rides, or understand which vehicle segments drive the highest contribution. Key questions such as: *Which vehicle types are driving the most revenue? What is the core reason for incomplete trips? Are customer and driver satisfaction levels aligned across different options?* ...are difficult to answer quickly with raw data.

• Goal of the Dashboard

To deliver an interactive business intelligence tool that:

* Provides a birds-eye view of operational efficiency (completed vs. lost bookings).
* Empowers managers to track monthly revenue patterns and analyze ride outcome distributions.
* Segments performance metrics dynamically by vehicle type (Auto, Bike, Sedan, XL) to optimize fleet management.

• Walkthrough of Key Visuals

* **Key KPIs (Top Bar):** Highlights high-level performance across the entire dataset, including Total Completed Bookings (93K), Lost Bookings (57K), Total Distance (2.51M), Average Distance (25), and Total Revenue (51.85M).
* **Interactive Vehicle Sidebar Slicer:** Features a custom icon navigation layout allowing seamless filtration of the entire dashboard for specific vehicle categories (e.g., selecting Auto changes the view to isolate its specific 23K Completed Bookings and 12.88M Revenue).
* **Ride Status Donut Charts:** Breaks down ride finality into three structural categories: Completed (successfully finished), Cancelled (called off for any reason), and Incomplete (unfinished due to system/operational issues).
* **Completed Bookings over Time (Area Chart):** Provides a granular view of transaction trends across months with integrated Month/Quarter toggle buttons.
* **Revenue Trends (Column Chart):** Maps monthly revenue generation side-by-side to quickly identify peak seasons and performance dips.
* **Vehicle Performance & Sparkline Matrix:** A detailed tabular view displaying Customer Count, Revenue, Completed Bookings, and Contribution Percentage (`cont%`) per vehicle type, complete with inline Sparkline trend graphs showing monthly booking behavior at a glance.
* **Rating & Drop Location Performance:** Tracks customer experience metrics, highlighting Average Customer Rating (4.40), Average Driver Rating (4.23), and pinpointing Top Drop locations (e.g., Badarpur, New Colony).

 • Business Impact & Insights

* **Operational Improvements:** By monitoring "Lost Bookings" and "Incomplete" statuses, dispatch managers can identify technical errors or driver supply gaps.
* **Fleet Strategy & Resource Allocation:** Clear visibility into contribution metrics (e.g., tracking Auto vs. Sedan revenue) helps maximize driver recruitment strategies for high-demand tiers.
* **Quality Assurance:** Real-time tracking of dual-sided customer and driver ratings ensures platform standards remain consistently high.
  
