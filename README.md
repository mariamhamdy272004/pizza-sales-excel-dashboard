# Pizza Sales Dashboard (Excel)

🎯 **Overview**
This project is an interactive **Pizza Sales Dashboard** built in **Microsoft Excel** using **PivotTables, PivotCharts, and Slicers**.  
It helps analyze pizza performance across:
- Total Sales, Quantity, and Orders
- Sales by Pizza Category
- Monthly Order Volume trend
- Weekly Order Distribution
- Top 5 & Bottom 5 best selling pizzas
- Sales distribution by Pizza Size (e.g., L/M/S/XL)
- Dynamic filtering for fast decision-making

---

## 📊 Dashboard Features
✅ **KPI Cards**
- Total Sales (e.g., $859)
- Total Quantity (e.g., 54)
- Total Orders (e.g., 54)

✅ **Visual Insights**
- **Donut Chart:** Total sales per pizza category
- **Line/Cluster Trend:** Monthly order volume peak
- **Bar Chart:** Top 5 best selling pizzas
- **Bar Chart:** Bottom 5 least selling pizzas
- **Pie Chart:** Sales distribution by pizza size (Large leading)
- **Column Chart:** Weekly order distribution

✅ **Interactivity**
- **Slicers** for fields like:
  - `pizza_size`
  - `pizza_category`
  - (Optional) `order_date` month selector

---

## 🔧 How It Works
### 1) Data Preparation
- Raw sales/order data is organized in an Excel table format.
- Key fields include:
  - order_id
  - customer name
  - pizza_category
  - pizza_size
  - order_date
  - quantity
  - sales

### 2) PivotTables
- PivotTables aggregate:
  - Sum of Sales
  - Sum of Quantity
  - Count of order_id (Orders)
  - Percent share per category/size

### 3) PivotCharts
- PivotCharts are connected directly to the PivotTables
- Charts update instantly when slicer filters change.

---

## 🎛️ Slicers & Filters
Use slicers to dynamically filter the dashboard, such as:
- **pizza_size:** L, M, S, XL
- **pizza_category:** Chicken, Classic, Supreme, Veggie
- **order_date:** month-based filtering (optional)

---

## 📌 Key Insights Example (from the dashboard)
- Large sizes show leading sales distribution
- Category contribution is visualized as percentages
- Weekly ordering pattern is displayed per weekday
- Top and bottom pizzas are ranked using sales totals

---

## 🖼️ Screenshots
This project includes screenshots of:
<img width="1635" height="659" alt="Screenshot 2026-11-21 220438" src="https://github.com/user-attachments/assets/76480da0-58e2-4697-925b-f45ad5f0d368" />

- PivotTables used to generate KPI and charts
<img width="1490" height="581" alt="Screenshot 2026-11-21 220619" src="https://github.com/user-attachments/assets/c3c89e3f-415f-4e65-9504-a85f2b1fe1e3" />
<img width="1795" height="672" alt="Screenshot 2026-11-21 220645" src="https://github.com/user-attachments/assets/d6219254-c50a-4d6d-8cc4-ebe596e69698" />
<img width="865" height="468" alt="Screenshot 2026-11-21 220523" src="https://github.com/user-attachments/assets/f5ac544d-24fd-43b3-9e79-b9b0eae25da0" />

---

## 🚀 Future Improvements
- Add year-wise comparisons (if data supports multiple years)
- Include profit/margin analysis (if cost data is added)
- Add interactive drill-down views per customer or region
- Add automatic refresh instructions for updated datasets

---

## 🧠 Tech Stack
- **Excel**
- **PivotTables**
- **PivotCharts**
- **Slicers**
- (Optional) VBA: N/A

---

### 📩 Contact
Feel free to suggest improvements or enhancements!
