# 📊 HR Analytics Dashboard

An interactive multi-page **Power BI** report built to analyze key human resources metrics, including headcount demographics, promotion eligibility, retrenchment risks, and employee satisfaction levels.

---

## 🖼️ Dashboard Preview

### 1. Home View (High-Level Overview)
Provides a bird's-eye view of key workforce KPIs, gender distribution, service duration, and overall status.
![Home View](./HR%20Analytics%20Dashboard_page-0001.jpg)

### 2. Action View (Employee Details)
Lists specific employees eligible for promotion or flagged for retrenchment for direct HR administrative action.
![Action View](./HR%20Analytics%20Dashboard_page-0002.jpg)

### 3. Detail View (Deep-Dive Insights)
Breaks down retrenchment and promotions by department, job role, job satisfaction, overtime, and performance ratings.
![Detail View](./HR%20Analytics%20Dashboard_page-0003.jpg)

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Used to design the interface, construct interactive visualizations, establish data models, and build seamless report navigation.
* **DAX (Data Analysis Expressions):** Used to write dynamic measures and calculated fields for KPIs such as promotion percentages, total retrenchments, and employee distributions.
* **Power Query:** Utilized for data cleaning, ETL processes, field transformations, and standardizing raw CSV datasets.
* **CSV / Excel:** Served as the underlying data source for employee profiles, service records, and promotion history.

---

## ⚙️ How I Built This Dashboard

1. **Data Cleaning & Transformation:**
   * Cleaned and transformed raw CSV files in Power Query by standardizing column types, removing duplicates, and handling null values.
2. **Data Modeling:**
   * Established relationships between main employee tables and supplementary lookup/reference tables using unique identifiers.
3. **DAX Calculations:**
   * Created calculated metrics for key indicators such as:
     * **Total Headcount:** `1,470`
     * **Gender Breakdown:** `60% Male` (882) / `40% Female` (588)
     * **Promotion Status:** `72` Due for Promotion (4.9%) vs. `1,398` Not Due (95.1%)
     * **Retrenchment Status:** `117` Flagged for Retrenchment (8.0%) vs. `1,353` Active On Service (92.0%)
4. **Interactive UI/UX Design:**
   * Structured the dashboard into 3 clean, dedicated views (**Home**, **Action**, and **Detail**) with custom side-bar navigation buttons for seamless page transitions.

---

## 📂 Repository Structure

```text
HR_Analytics_Dashboard/
│
├── HR Analytics Dashboard_page-0001.jpg # Home view preview image
├── HR Analytics Dashboard_page-0002.jpg # Action view preview image
├── HR Analytics Dashboard_page-0003.jpg # Detail view preview image
├── README.md                            # Repository documentation
└── HR_Analytics_Dashboard/              # Project files and data
    ├── HR Analytics Dashboard.pbix      # Main Power BI project file
    ├── HR Analytics Dashboard.pdf       # Full PDF report export
    ├── HR Analytics Data.csv            # Primary employee dataset
    ├── HR Analytics My Ref.csv         # Reference lookup dataset
    ├── HR employee data.csv             # Employee demographics
    ├── data.csv Retrenchment.csv        # Retrenchment records
    └── data.csv prommtion.csv           # Promotion history dataset
