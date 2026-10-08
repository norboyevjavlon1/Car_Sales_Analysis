
# 🚗 Car Sales & Margin Analytics - Power BI Dashboard

## 📌 Project Overview
This project is an end-to-end Business Intelligence solution developed in Power BI to analyze car sales performance, profitability margins, and seller efficiency. The dashboard provides actionable insights into pricing strategies, helping business stakeholders identify underpriced vehicles and optimize revenue.

## 🛠️ Tools & Technologies Used
* **Power BI:** Data Modeling, Visualization, Dashboard Design.
* **Power Query:** Data cleaning, transformation, and handling missing values.
* **DAX (Data Analysis Expressions):** Complex measures, Time Intelligence, What-If Parameters.

## 📊 Dashboard Architecture (Pages)

### 1. Executive Overview
Displays high-level KPIs including Total Sales Revenue, Total Cars Sold, and Average Selling Price. Features a geographic map of sales distribution and dynamic trend analysis.

### 2. Brand & Model Deep Dive (Drillthrough)
Utilizes Power BI's **Drillthrough** functionality. Users can right-click any car make to navigate to this page and see specific metrics like predominant body type, top colors, and the correlation between odometer readings and pricing via a Scatter Chart.

### 3. Seller Performance (Report Page Tooltips)
Analyzes top-performing dealers using Treemaps and Stacked Bar Charts. Implemented custom **Report Page Tooltips** — hovering over a seller reveals a dynamic mini-dashboard showing their specific portfolio, average car condition, and top-selling brands.

### 4. Price & Margin Analysis (What-If Parameters)
Focuses on profitability by comparing actual selling prices against Market Value (MMR). 
* Includes a **Waterfall Chart** to visualize price deviations.
* Features a **What-If Parameter** allowing stakeholders to simulate future margins by adjusting pricing models dynamically (-20% to +20%).

## 💡 Key DAX Implementations
* **Price Classification:** Segmented vehicles into "Underpriced", "Fair", and "Overpriced" categories using logical DAX functions.
* **Total Margin & Variance:** Calculated the absolute dollar difference between Total Sales and Market Value (MMR).
* **Dynamic Modifiers:** Built measures that respond interactively to the What-If slicer to project future revenue.

## 📸 Dashboard Screenshots
*(Bu yerga loyihangiz skrinshotlarini qo'shing)*
Overview<img width="1109" height="620" alt="image" src="https://github.com/user-attachments/assets/4ac8612a-94d6-44b5-a5da-f13554408855" />
Brand & Model Deep<img width="1113" height="625" alt="image" src="https://github.com/user-attachments/assets/e8be2cc8-e9cd-48c6-bddf-3913e1f6edde" />
Drillthrough Page<img width="1110" height="625" alt="image" src="https://github.com/user-attachments/assets/705f69df-c364-489b-8274-9b0b1e664fde" />
Seller Performance & Margin Analysis<img width="1111" height="590" alt="image" src="https://github.com/user-attachments/assets/2e99baf1-ef64-49eb-899c-f33193d993c4" />
Tooltip Page<img width="1112" height="621" alt="image" src="https://github.com/user-attachments/assets/3a84fc8d-25db-4cf2-a0a5-c34fabd52c30" />

