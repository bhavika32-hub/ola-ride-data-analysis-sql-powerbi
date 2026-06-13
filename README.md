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
- Total Revenue  
- Total Revenue Loss 
- Total Successful Rides 
- Overall Cancellation Rate  
- Customer Cancellation %  
- Driver Cancellation %  
- Average Driver Rating  
- Average Customer Rating  
---

## Key Insights

## Key Insights

* The overall cancellation rate was **28%**.
* Customer cancellations accounted for approximately **10%** of total bookings, while driver cancellations accounted for approximately **18%**.
* Among customer-cancelled rides, around **30%** occurred because drivers did not move toward the pickup location, leading to customer frustration.
* Among customer-cancelled rides, approximately **25%** were cancelled because drivers asked customers to cancel the ride.
* Among customer-cancelled rides, approximately **14%** were due to AC or comfort-related complaints.
* Among driver-cancelled rides, approximately **35%** were caused by driver personal or vehicle-related issues.
* The highest number of bookings and cancellations were observed on **Monday, Tuesday, and Wednesday**, indicating peak operational pressure during these days.
* Total potential revenue loss of approximately **₹21M** was observed due to cancellations and driver-related issues.
* Approximately **₹16M** of revenue loss was attributed to ride cancellations, indicating significant demand leakage.
* Approximately **₹5M** of revenue loss was caused by Driver Not Found cases, highlighting supply-side inefficiencies.
* Around **40%** of incomplete rides were caused by vehicle breakdown issues, indicating operational and maintenance gaps.

**Overall Insight:** Driver behavior, vehicle-related issues, and peak-day operational pressure were the primary contributors to ride cancellations, incomplete rides, and revenue loss.


**Overall Insight:** Driver behavior, vehicle condition, and peak-day operational pressure are the major contributors to cancellations and revenue loss.

---

## SQL Analysis

SQL was used to extract insights, calculate KPIs, and understand booking, cancellation, and customer behavior patterns.

### Key Areas Covered

**1. Booking & Revenue Analysis**
* Total bookings by vehicle type  
* Revenue contribution by vehicle type  
* Successful vs cancelled bookings  

**2. Customer Analysis**
* Total rides per customer  
* Frequent customers (5+ rides)  
* Top customers by number of bookings  

**3. Cancellation Analysis (Core Focus)**
* Customer vs Driver cancellations  
* Cancellation reasons (frequency-based)  
* Vehicle-type-wise cancellation trends  
* Location-wise cancellation hotspots  

**4. Ratings & Experience Analysis**
* Average driver and customer ratings  
* Low-rating + high-cancellation locations  

**5. Operational Insights**
* High-demand pickup locations  
* Payment method usage (e.g., UPI)  
* Incomplete rides and reasons  

---

## Business Recommendations (with Reason)

### 1. Driver Accountability & Incentives
* Penalize or warn drivers who do not move toward pickup location  
* Provide incentives for drivers with high acceptance and low cancellation rates  
**Reason:** Improves ride completion and driver responsibility  

---

### 2. Driver Quality Monitoring
* Identify drivers with repeated cancellations  
* Provide training or restrict access for poor performers  
**Reason:** Ensures platform reliability and service quality  

---

### 3. Vehicle & Comfort Compliance
* Regular vehicle inspections (AC, cleanliness, condition)  
* Remove non-compliant drivers  
**Reason:** Improves customer satisfaction and trust  

---

### 4. Demand-Based Optimization
* Focus driver availability on high-demand days (Mon–Wed)  
* Optimize driver allocation during peak booking periods  
**Reason:** Reduces cancellations during high-demand pressure  

---

### 5. Vehicle Maintenance & Breakdown Reduction
* Regular vehicle health checks and preventive maintenance  
* Monitor vehicles with repeated breakdown history  
* Partner with service centers for quick repair turnaround  
**Reason:** Around 40% incomplete rides were due to vehicle breakdowns, impacting ride completion and customer trust  

---

## Success Measurement (Expected Impact)

* Reduction in overall cancellation rate  
* Improvement in ride success rate and customer satisfaction  
* Decrease in driver-related complaints and repeated cancellations  
* Reduction in revenue loss (~₹21M impact area)
* Better operational efficiency through improved driver allocation  
