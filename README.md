# 🏨 Hotel Booking Analysis – Power BI Project  

### 📊 Overview  
This Power BI project explores **hotel booking data (2015–2017)** for two types of hotels — **🏙️ City Hotel** and **🏖️ Resort Hotel**.  
The goal is to understand **guest booking patterns, cancellations, and revenue trends**, and derive actionable insights for business growth.

---

## 🎯 Objectives  
- Analyze **hotel performance** across years and types.  
- Identify **booking trends**, **cancellation patterns**, and **revenue drivers**.  
- Compare **City vs Resort Hotel** performance.  
- Provide **interactive Power BI dashboards** for management decision-making.

---

## 🧾 Dataset Information  
- **Period Covered:** July 2015 – August 2017  
- **Records:** 87,292  
- **Columns:** 32  
- **Hotel Types:** City Hotel and Resort Hotel  

### 🔹 Data Cleaning & Preparation  
Performed within Power BI using Power Query:
1. Removed errors, blanks, and duplicates.  
2. Dropped unnecessary columns (`company` – 94% null).  
3. Filled missing agent records as “Direct Booking.”  
4. Removed rows where total guests = 0.  
5. Created calculated columns:  
   - `arrival_date` = day + month + year  
   - `total_stay` = weekday + weekend nights  
   - `total_people` = adults + children + babies  
6. Transformed date fields for time-based analysis.  
7. Ensured proper data types for measures and visuals.  

---

## 📊 Dashboards & Insights  

### 🟦 1️⃣ Annual Insights Dashboard  
**Purpose:** Overview of total bookings, hotel preferences, market segments, and booking status.  

**Key Highlights:**  
- **Total Bookings:** 87.22K  
- **City Hotel:** 61.07% | **Resort Hotel:** 38.93%  
- **Top Market Segment:** Online TA (51.5%)  
- **Booking Status:**  
  - Checked-out – 72.5%  
  - Canceled – 26%  
  - No-show – 1.5%  
- **Top Guest Countries:** Portugal, UK, France, Spain  
- **Steady booking growth** observed through 2017.  

---

### 🟦 2️⃣ Daily Insights Dashboard  
**Purpose:** Analyze daily booking behavior, cancellations, and meal preferences.  

**Key Highlights:**  
- **Total Cancellations:** 24K (~27%)  
- **Most Canceled Hotel:** City Hotel (66.8%)  
- **Meal Type Preference:**  
  - BB (Bed & Breakfast) – 77.8%  
  - SC – 10.4%, HB – 10.7%, FB – very few  
- **City Hotel dominates bookings** and cancellations both.  

---

### 🟦 3️⃣ Revenue Insights Dashboard  
**Purpose:** Understand revenue trends across hotel type, room type, and market segment.  

**Key Highlights:**  
- **Total Revenue:** 9.29M  
  - City Hotel – 5.93M (63.8%)  
  - Resort Hotel – 3.36M (36.2%)  
- **Top Revenue Segments:**  
  - Online TA – 6.1M  
  - Direct – 1.4M  
- **Top Room Types:** A (5.2M), D (2.1M)  
- **Revenue Peaks:** Mid-2016 and mid-2017  
- **Resort Hotels show seasonal rise** in mid-year months.  

---

## ✅ Key Insights Summary
- Majority of bookings are from **City Hotels** (61%).  
- **Online Travel Agencies** dominate with over 50% of total bookings.  
- **Cancellations account for 27%** of total bookings.  
- **July–August** show the highest booking activity (summer season).  
- **Portugal, UK, France, and Spain** are top customer origins.  
- **Average stay length:** around 7 days.  
- **Meal Preference:** BB plan highly favored.  
- **Room Types A & D** are most booked.  
- Very **few repeat customers**, indicating potential for loyalty programs.  

---

## 💡 Recommendations for Business
| Area | Suggestion |
|------|-------------|
| **Resort Hotel Bookings** | Launch seasonal discounts, family packages, and OTA partnerships |
| **Cancellations** | Offer flexible rebooking and loyalty discounts for confirmed guests |
| **Revenue Optimization** | Apply dynamic pricing based on demand and season |
| **International Guests** | Market towards underrepresented countries |
| **Guest Retention** | Introduce loyalty or membership programs |
| **Customer Experience** | Expand meal options, offer complimentary upgrades during off-peak months |

---

## 🧠 Key Learnings
- Hands-on experience in **data transformation using Power Query**.  
- Developed **calculated columns and DAX measures** for KPIs.  
- Gained strong understanding of **data visualization and storytelling** in Power BI.  
- Built interactive dashboards with slicers, filters, and year-wise comparisons.  

---

## 🛠️ Tools Used
- **Microsoft Power BI** – Data transformation, DAX, and dashboard design  
- **Excel (optional)** – Data review and structure validation  

---

## 📁 Project Deliverables
- `Hotel_Booking_Analysis.pbix` – Power BI file  
- Dashboards:  
  1. Annual Insights  
  2. Daily Insights  
  3. Revenue Insights  

---

## 🏁 Conclusion
This Power BI project highlights how **data visualization can drive business intelligence** in the hospitality industry.  
By analyzing booking trends, cancellations, and revenue patterns, hotels can **optimize pricing, marketing, and guest satisfaction strategies** effectively.  
