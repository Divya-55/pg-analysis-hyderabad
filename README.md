# PG Rental Insights – Hyderabad

## Problem Statement
To analyze PG (Paying Guest) rental data in Hyderabad and identify:
- Pricing patterns (rent vs. deposit)  
- Occupancy trends (single, double, triple, 4-sharing)  
- Facility & amenity distributions  
- Availability timelines  

This helps **students, working professionals, and property owners** make informed decisions about accommodation and investments.

---

## Dataset
- **File:** `final_pg_data.csv`  
- **Source:** PG accommodation listings (synthetic/collected dataset)  
- **Features include:**  
  - Location  
  - Occupancy type  
  - Rent & Deposit  
  - Amenities  
  - Food availability  
  - Availability dates  

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI**: Interactive dashboards & visuals  
- **Jupyter Notebook**: Exploratory Data Analysis (EDA)  

---

## Approach & Methodology
1. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Extracted amenities from string format  
   - Converted dates to datetime format  

2. **Exploratory Data Analysis (EDA)**  
   - Rent & deposit distributions  
   - Location-wise price trends  
   - Occupancy vs. affordability  

3. **Power BI Dashboard**  
   Created visuals to highlight insights:  
   - **Occupancy Type Distribution** → 4-sharing most popular  
   - **Average Rent vs. Deposit by Location** → Banjara Hills highest rent  
   - **Food Facility Availability** → 92% provide full meals  
   - **Upcoming PG Availability** → Spike at beginning of the month  
   - **Room Amenities Distribution** → Beds & fans common, AC/geysers rare  
   - **Heatmap of Average Rents & Returns** → Premium vs. budget areas  

---

## Key Insights
- **Affordability dominates:** 4-sharing PGs are most common.  
- **Location premium:** Banjara Hills, Madhapur, and Gachibowli have higher rents.  
- **Hidden costs:** Some areas (e.g., Kondapur, Begumpet) demand high deposits despite moderate rents.  
- **Convenience factor:** Food facility is almost standard in Hyderabad PGs.  
- **Seasonal availability:** PGs often list new availability at the beginning of the month.  

---

## How to Run the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/pg-rental-insights.git
   cd pg-rental-insights
2. Run Jupyter Notebook for EDA:
   ```bash
   jupyter notebook project.ipynb
3. Open Power BI dashboard:
   - File: ```hyderabad_pg_rental_insights.pbix```
   - Requires Power BI Desktop

## Project Structure
```bash
📂 PG-Rental-Insights
│── final_pg_data.csv                  # Dataset
│── project.ipynb                      # Python EDA notebook
│── hyderabad_pg_rental_insights.pbix  # Power BI dashboard
│── README.md                          # Project documentation
