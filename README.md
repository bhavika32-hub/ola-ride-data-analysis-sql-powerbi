# Ola Ride Cancellation Analysis

---
 
## Problem Statement

The objective was to analyze ride data to identify key reasons behind ride cancellations, incomplete rides, and associated revenue loss, and suggest data-driven strategies to improve booking success rate, operational efficiency, and customer experience.

---

## Business Objective

To identify key factors affecting ride cancellations and improve overall platform efficiency by:

* Reducing cancellation rate and minimizing revenue loss
* Improving ride success rate  
* Enhancing customer and driver experience  
* Optimizing operational decision-making using data  

---

## Tools & Technologies

* Excel – Data Cleaning and Preparation  
* SQL – Exploratory Analysis and Business Queries  
* Power BI – Dashboard creation, Data visualization  

---

## Dataset

* 50K+ ride records  
* Data included: booking status, cancellation reasons, driver behavior, ride details, and revenue impact  

---

## Data Preparation:
* Verified and corrected data types
* Identified and removed exact duplicate records
* Standardized inconsistent values for accurate analysis
* Performed data quality checks before KPI calculation and dashboard development

## 📊 KPI Tracking

- Total Bookings  
- sucessfull ride revenue
- Total Revenue Loss 
- Total Successful Rides 
- Overall Cancellation Rate  
- Customer Cancellation %  
- Driver Cancellation %   
---

## Key Insights

* The overall cancellation rate was **28%**.
* Customer cancellations accounted for approximately **10%** of total bookings, while driver cancellations accounted for approximately **18%**.
* Among customer-cancelled rides, around **28%** occurred because drivers did not move toward the pickup location, leading to customer frustration.
* Among customer-cancelled rides, approximately **25%** were cancelled because drivers asked customers to cancel the ride.
* Among customer-cancelled rides, approximately **14%** were due to AC or comfort-related complaints.
* Among driver-cancelled rides, approximately **35%** were caused by driver personal or vehicle-related issues.
* The highest number of bookings and cancellations were observed on **Monday, Tuesday, and Wednesday**, indicating peak operational pressure during these days.
* Total potential revenue loss of approximately **₹21M** was observed due to cancellations and driver-related issues.
* Approximately **₹16M** of revenue loss was attributed to ride cancellations, indicating significant demand leakage.
* Approximately **₹5M** of revenue loss was caused by Driver Not Found cases, highlighting supply-side inefficiencies.
* Around **40%** of incomplete rides were caused by vehicle breakdown issues, indicating operational and maintenance gaps.

**Overall Insight:** Driver behavior, vehicle-related issues, and peak-day operational pressure were the primary contributors to ride cancellations, incomplete rides, and revenue loss.



---

## SQL Analysis

SQL was used to extract insights, calculate KPIs, and understand booking, cancellation, and customer behavior patterns.

### Key Areas Covered

### 🚖 1. Booking & Revenue Analysis
- Total bookings by vehicle type
- Revenue contribution by vehicle type
- Successful vs. cancelled bookings
- Revenue loss analysis (Cancelled & Incomplete rides)
- Revenue loss by booking status

---

### 👥 2. Customer Analysis
- Total rides per customer
- Frequent customers (5+ rides)
- Top customers by number of bookings

---

### ❌ 3. Cancellation Analysis (Core Focus)
- Customer vs. driver cancellations
- Customer & driver cancellation reason analysis
- Vehicle-wise cancellation trends
- Pickup location cancellation hotspots

---

### ⭐ 4. Ratings & Customer Experience Analysis
- Average driver and customer ratings
- Driver vs. customer rating comparison
- Low-rating & high-cancellation locations

---

### ⚙️ 5. Operational Insights
- High-demand pickup locations
- Payment method distribution
- Incomplete ride analysis and reasons
## Business Recommendations (with Reason)

### 1. Improve Driver Pickup Compliance

* Monitor drivers who frequently do not move toward the pickup location after accepting rides.
* Introduce penalties for repeated violations and incentives for timely pickups.

**Reason:** Around **30% of customer-cancelled rides** occurred because drivers did not move toward the pickup location.

---

### 2. Reduce Driver-Initiated Customer Cancellations

* Track drivers who repeatedly ask customers to cancel rides.
* Implement stricter monitoring and accountability measures for such cases.

**Reason:** Around **25% of customer-cancelled rides** occurred because drivers asked customers to cancel the ride.

---

### 3. Improve Vehicle Quality & Comfort Standards

* Conduct regular inspections for AC, cleanliness, and overall vehicle condition.
* Monitor and address repeated customer complaints related to ride comfort.

**Reason:** Around **14% of customer-cancelled rides** were due to AC or comfort-related issues.

---

### 4. Strengthen Driver Quality Monitoring

* Identify drivers with high cancellation rates due to personal or vehicle-related reasons.
* Provide training, performance reviews, or restrictions for repeated offenders.

**Reason:** Around **35% of driver-cancelled rides** were caused by driver personal or vehicle-related issues.

---

### 5. Demand-Based Driver Allocation

* Increase driver availability during high-demand periods.
* Optimize driver allocation on Monday, Tuesday, and Wednesday to better match booking demand.

**Reason:** The highest bookings and cancellations were observed on **Monday, Tuesday, and Wednesday**.

---

### 6. Vehicle Maintenance & Breakdown Reduction

* Perform regular vehicle health checks and preventive maintenance.
* Monitor vehicles with repeated breakdown history and take corrective actions.

**Reason:** Around **40% of incomplete rides** were caused by vehicle breakdown issues, impacting ride completion and customer trust.

## Success Measurement (Expected Impact)

* Reduction in overall cancellation rate  
* Improvement in ride success rate and customer satisfaction  
* Decrease in driver-related complaints and repeated cancellations  
* Reduction in revenue loss (₹21M impact area)
* Better operational efficiency through improved driver allocation  
