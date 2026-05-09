# 🛒 Durga Ecommerce Sales Dashboard

> **⚠️ Disclaimer:** This project uses a **mock/practice dataset** — not real business data. Created purely for learning and portfolio demonstration purposes.

---

## 📌 Project Objective

To design and develop an interactive **Power BI dashboard** that helps the Durga Ecommerce business track and analyze their online sales performance across India — enabling data-driven decisions around revenue, profitability, customer behavior, and product performance.

---

## 📊 Live Dashboard Preview

![Durga Ecommerce Sales Dashboard](./Screenshot_2026-04-25_122541.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Dashboard creation, DAX measures, data modelling |
| **Microsoft Excel / CSV** | Raw data storage and preparation |
| **DAX (Data Analysis Expressions)** | Custom KPI calculations and measures |
| **Power Query** | Data transformation and cleaning |

---

## 📁 Dataset Description

> **Data Type: Mock / Practice Dataset — Not Real Business Data**

Two CSV files form the data model, joined on `Order ID`:

### 📋 Orders.csv — 501 records
| Column | Description |
|--------|-------------|
| `Order ID` | Unique order identifier (e.g. B-25681) |
| `Order Date` | Date of purchase (DD-MM-YYYY) |
| `CustomerName` | Customer first name |
| `State` | Indian state of delivery |
| `City` | City of delivery |

### 📋 Details.csv — 1,500 records
| Column | Description |
|--------|-------------|
| `Order ID` | Links to Orders.csv |
| `Amount` | Revenue generated (₹) |
| `Profit` | Profit earned or lost (₹) |
| `Quantity` | Number of units sold |
| `Category` | Product category (Clothing, Electronics, Furniture) |
| `Sub-Category` | Product sub-category (Saree, Printers, Bookcases, etc.) |
| `PaymentMode` | Payment method used (COD, UPI, Credit Card, Debit Card, EMI) |

**Coverage:** Year 2018 | Pan-India | 19+ states and cities

---

## 📈 Dashboard Features

### 🔢 KPI Cards (Top Summary)
- **₹4,38,000** — Total Sales Amount
- **5,615** — Total Quantity Sold
- **₹37,000** — Total Profit
- **₹1,21,000** — Sum of Average Order Value (AOV)

### 📊 Visualizations Included

| Visual | Type | Insight Provided |
|--------|------|-----------------|
| Sum of Amount by State | Horizontal Bar Chart | Geographic revenue distribution |
| Sum of Quantity by Category | Donut Chart | Category volume contribution |
| Sum of Quantity by PaymentMode | Donut Chart | Customer payment preferences |
| Profit by Month | Column Chart (with negatives) | Monthly profit trend & seasonality |
| Sum of Profit by Sub-Category | Bar Chart | Best and worst performing sub-categories |
| Sum of Amount by CustomerName | Bar Chart | Top revenue-generating customers |

### 🎛️ Interactive Filters / Slicers
- **Quarter Filter** — Qtr 1, Qtr 2, Qtr 3, Qtr 4 (+ Select All)
- **State Filter** — Dropdown to filter all visuals by Indian state

---

## 🔍 Key Business Insights

> These insights were derived from the mock dataset and are intended to demonstrate analytical thinking.

1. **💳 Cash on Delivery dominates payments at 44%** — suggesting customers prefer to pay upon delivery, which is typical for Tier-2 and Tier-3 Indian cities. UPI follows at 21%, reflecting the rise of digital payments.

2. **👗 Clothing drives volume, Electronics drives value** — Clothing contributes 63% of total quantity sold, but Electronics (Printers, Phones) generates higher per-order revenue. A dual-strategy approach is needed.

3. **📍 Maharashtra leads in revenue** — Maharashtra is the top-performing state by sales amount, followed by Madhya Pradesh and Uttar Pradesh. This signals strong urban demand in cities like Mumbai and Pune.

4. **📉 Profit goes negative in June–August (Q3)** — The Profit by Month chart reveals significant losses in mid-year months. This could indicate seasonal discounting, high return rates, or supply cost spikes — warranting further investigation.

5. **🖨️ Printers are the most profitable sub-category** — Within Electronics, Printers lead profit contribution. Bookcases (Furniture) and Sarees (Clothing) follow, while Tables and Electronic Games show inconsistent margins.

6. **👤 Top customers show high concentration risk** — Harivansh, Madhav, and Madan Mohan account for a disproportionate share of order value, indicating the business may be over-reliant on a small customer base.

7. **📦 EMI usage signals high-ticket purchases** — Orders paid via EMI tend to be higher in value (Furniture, Electronics), which is consistent with consumer behaviour for big-ticket items in India.

---

## 🚀 How to Open and Use the Dashboard

### Prerequisites
- Download and install **[Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)** (free)

### Steps
1. Clone or download this repository
   ```bash
   git clone https://github.com/your-username/Durga-Ecommerce-Dashboard.git
   ```
2. Open **Power BI Desktop**
3. Go to `File → Open report → Browse`
4. Select `Durga_Dashboard.pbix`
5. Use the **Quarter** and **State** slicers to explore the data interactively

> If the data doesn't load, go to `Transform Data → Data Source Settings` and re-point to the CSV files in this folder.

---

## 🎯 Skills Demonstrated

- ✅ Data cleaning and transformation using **Power Query**
- ✅ Data modelling — joining two tables via a **one-to-many relationship** on `Order ID`
- ✅ Writing **DAX measures** for KPIs (Sum, Profit %, AOV)
- ✅ Designing a dark-themed, professional **executive dashboard**
- ✅ Building **interactive slicers** for dynamic filtering
- ✅ Identifying **business insights** from raw transactional data
- ✅ Communicating findings visually for non-technical stakeholders

---

## 📚 Learnings & Takeaways

This project helped me practise:
- End-to-end dashboard development workflow (data → model → visuals → insights)
- Choosing the right chart type for each analytical question
- Handling negative profit values in bar/column charts meaningfully
- Designing for readability: dark theme, consistent color palette, clear typography

---

## 🙋 About the Developer

**Aryan** — Aspiring Data Analyst passionate about turning raw data into actionable business insights using Power BI, Excel, and SQL.

📫 Connect with me on [LinkedIn](www.linkedin.com/in/aryan-singh-bb07b1269) | [GitHub](https://github.com/aryan01-analytics)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
The dataset is entirely fictional and created for educational purposes only.

---

*⭐ If you found this project helpful or interesting, feel free to star the repository!*
