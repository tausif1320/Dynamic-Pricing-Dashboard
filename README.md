# Dynamic-Pricing-Dashboard
# 📊 Dynamic Pricing & Revenue Optimization Dashboard – Power BI  

## 🔹 Business Problem  
Retail businesses often rely on **static pricing strategies**, which fail to adapt to:  
- Seasonal demand fluctuations  
- Customer buying behavior  
- Inventory levels  

This results in lost revenue opportunities and poor forecasting.  

---

## 🔹 Goal of the Dashboard  
The main objective of this project is to:  
- Build a **dynamic pricing simulator** using Power BI.  
- Allow executives to monitor **key KPIs** in real-time.  
- Simulate **price adjustments (+/- %)** and measure revenue impact.  
- Provide insights by **category, region, and time trends**.  

---

## 🔹 Dataset  
- Rows: **128,976**  
- Columns used:  
  - `Order ID`  
  - `Date` (cleaned & standardized)  
  - `Category`  
  - `Quantity`  
  - `Amount`  
  - `Ship State`  
- Preprocessing: Cleaned in **Python (Pandas)** and **Excel** to handle mixed date formats and remove unnecessary columns.  

---

## 🔹 Key Visuals  

1. **KPI Cards**  
   - Metrics: Total Revenue, Total Orders, Average Order Value, Adjusted Revenue.  
   - 📌 Provides an executive snapshot.  

2. **Revenue vs Adjusted Revenue (Bar/Line Chart)**  
   - 📌 Shows effect of price adjustments.  

3. **Category-wise Sales (Bar Chart)**  
   - 📌 Identifies top-performing product categories.  

4. **Geo Heatmap (State-wise Sales)**  
   - 📌 Highlights strong and weak regions.  

5. **Order Status (Donut Chart)**  
   - 📌 Tracks Delivered vs Cancelled orders.  

6. **Trend Analysis (Line Chart)**  
   - 📌 Seasonality, monthly, and quarterly growth.  

7. **Tooltips & Drillthrough Pages**  
   - 📌 Detailed insights without cluttering main visuals.  

---

## 🔹 Business Impact & Insights  

✅ A **10% increase in pricing** for high-demand categories resulted in **~8% revenue growth** without lowering sales.  
✅ Identification of **low-performing categories** → optimized discounting.  
✅ Top **3 high-revenue states** revealed for better resource allocation.  
✅ **Cancellation analysis** improved order fulfillment.  

---

## 🔹 Tech Stack  
- **Power BI** (data modeling, DAX measures, visualization)  
- **Python (Pandas)** (data cleaning & preprocessing)  
- **Excel** (initial data validation)  

---

## 🔹 Project Files  
- `dynamic_pricing.pbix` → Power BI dashboard file  
- `cleaned_dataset.csv` → Cleaned dataset used for visualization  

---

## 🔹 How to Use  
1. Clone this repo:  
   ```bash
   git clone https://github.com/yourusername/dynamic-pricing-dashboard.git
2.Open dynamic_pricing.pbix in Power BI Desktop.

3.Interact with slicers (Date, Category, State).

4.Use the price adjustment simulator to see dynamic revenue impact.

## Screenshot / Demos
image1 - https://github.com/tausif1320/Dynamic-Pricing-Dashboard/blob/main/dashboard%20image.png
image2 -
