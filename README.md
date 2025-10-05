# 📱 Mobile Sales Dashboard (Power BI + DAX)

---

## 🧩 1. Problem Statement
The goal of this project is to analyze and visualize mobile sales performance across different cities, brands, and time periods.  
The dashboard helps stakeholders identify top-performing brands, track revenue trends, and understand customer behavior through data-driven insights.

---

## 📁 2. Data Overview

### a. Data Description
The dataset contains transactional-level sales data from a mobile retail business.  
It includes details about customers, sales performance, and payment methods, enabling a holistic view of sales and customer satisfaction.

### b. Data Fields

| Column Name | Description |
|--------------|-------------|
| `Transaction ID` | Unique identifier for each sales transaction |
| `Day` | Day of the transaction |
| `Month` | Month of the transaction |
| `Year` | Year of the transaction |
| `Day Name` | Name of the day (e.g., Monday, Tuesday) |
| `Brand` | Brand of the mobile phone sold |
| `Mobile Model` | Specific mobile phone model |
| `Units Sold` | Number of units sold per transaction |
| `Price Per Unit` | Selling price per mobile unit |
| `Customer Name` | Name of the customer |
| `Customer Age` | Age of the customer |
| `City` | City where the sale occurred |
| `Payment Method` | Mode of payment (Cash, UPI, Credit Card, etc.) |
| `Customer Ratings` | Customer satisfaction rating (1–5 scale) |

---

## ⚙️ 3. Approach
1. **Data Cleaning & Transformation:**  
   - Used Power Query to clean and transform data for consistency.  
   - Standardized date columns and handled missing or incorrect entries.  

2. **Data Modeling:**  
   - Created a relational model with a **Sales Fact Table** linked to **Date** and **Customer Dimensions**.  
   - Established relationships to support time-based and brand-based analysis.  

3. **DAX Measures:**  
   - `Total Revenue = SUM(Units Sold * Price Per Unit)`  
   - `Total Units Sold`  
   - `Average Rating`  
   - `YoY Growth %` and `MoM Growth %` (for sales trends)  
   - `Average Selling Price per Unit`  

4. **Dashboard Design:**  
   - Added filters for **Brand**, **City**, **Payment Method**, and **Time (Month/Year)**.  
   - Created KPIs for Total Revenue, Total Units Sold, and Average Customer Rating.  
   - Built interactive visuals like bar charts, line charts, and cards.  

5. **Automation:**  
   - Scheduled automatic data refresh in Power BI Service to ensure dashboards are always up to date.

---

## 📈 4. Results
- Identified **top-performing brands** and **high-demand cities** driving most of the revenue.  
- Observed that **UPI and Credit Card** payments account for more than **70% of total sales**.  
- Customers aged **25–35 years** rated their experience highest, with an average score above **4.2**.  
- Improved data-driven decision-making for marketing and sales teams.  

---

## 🖥️ 5. Output
### Power BI Dashboard  
Overview of the Sales
<img width="1298" height="733" alt="Screenshot 2025-10-05 122856" src="https://github.com/user-attachments/assets/40215656-0b1e-4105-8899-36d85f78f07d" />
MTD Report
<img width="1294" height="731" alt="Screenshot 2025-10-05 122910" src="https://github.com/user-attachments/assets/38de4bf1-8a1e-4849-ace8-4c9d54ba1d19" />
Same Period Last Year
<img width="1303" height="734" alt="Screenshot 2025-10-05 123015" src="https://github.com/user-attachments/assets/00b2ffe0-2485-4368-9cb4-e1e89112c4b2" />


**Key Visuals:**  
- 💰 Total Revenue & Units Sold (KPI Cards)  
- 📊 Brand-wise Sales Comparison  
- 📈 Monthly Sales Trend (YoY & MoM Growth)  
- 🏙️ City-wise Revenue Distribution  
- ⭐ Customer Rating by Age Group  
- 💳 Payment Method Analysis  

---

## 🧾 6. Conclusion
The Mobile Sales Dashboard provides actionable insights into sales trends, customer satisfaction, and brand performance.  
It enables management to track KPIs, identify sales opportunities, and improve overall business performance.  
Future enhancements may include predictive analytics to **forecast monthly sales** and **recommend inventory adjustments**.

---

## 🧠 Tools & Technologies Used
- **Power BI** – Dashboard design and DAX measures  
- **Power Query** – Data transformation and cleaning  
- **DAX** – Calculated columns and KPIs  
- **Excel / CSV** – Source data preparation  

---


