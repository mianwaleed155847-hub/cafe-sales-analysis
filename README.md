#  Cafe Sales Analysis

Exploratory Data Analysis (EDA) on cafe sales transactions using Python.  
Raw data was cleaned and visualized to extract actionable business insights.

---

##  Tools & Libraries
- **Python** — Pandas, NumPy, Matplotlib, Seaborn

---

##  Project Structure
| File | Description |
|------|-------------|
| `cafe.ipynb` | Main notebook — cleaning + EDA |
| `cafe_sales.csv` | Raw dataset |
| `cafe_sales_cleaned.csv` | Cleaned dataset |

---

##  Data Cleaning Steps
1. Loaded raw CSV and checked null values
2. Replaced `UNKNOWN` and `ERROR` strings with `NaN`
3. Fixed data types (Price, Quantity, Total Spent → float)
4. Filled missing values — Mode for categorical, Median for numerical
5. Dropped rows with missing Transaction Date
6. Converted Transaction Date to datetime format
7. Saved cleaned data as new CSV

---

##  EDA & Visualizations
-  Most Popular Items (Bar Chart + Count Plot)
-  Payment Method Distribution (Bar + Pie Chart)
-  Sales by Location
-  Monthly Revenue (Bar Chart)
-  Total Spent per Item (Box Plot)
-  Correlation Heatmap (Quantity, Price, Total Spent)
-  Monthly Revenue Trend (Line Plot)

---

##  Key Insights
1. Certain items consistently dominate orders — useful for stock planning
2. Customers prefer digital/card payments over cash
3. Monthly revenue shows seasonal peaks — guides promotional campaigns
4. Strong correlation between Quantity and Total Spent confirms volume-driven revenue
5. Boxplot outliers indicate occasional high-value bulk orders

---

##  Author
**Waleed Ahmad**  
BS Data Science (2nd semester)— Riphah International University  
[GitHub](https://github.com/mianwaleed155847-hub)
