# Sales-Report Dashboard (Power BI)
Power BI Sales Report project demonstrating data modeling, interactive dashboards, drill-down analysis, and data visualization using real-world datasets.
**Project Overview**

This project demonstrates how to build an interactive **Sales Report Dashboard** using Power BI.
It covers data import, data modeling, and visualization techniques to generate business insights.

**Objectives**

* Import data from web sources
* Build a relational data model
* Create hierarchies for drill-down analysis
* Design interactive dashboards
* Use maps, charts, and filters for insights

**Tools & Technologies**

* Power BI Desktop
* CSV Data Sources (Web)

**Step 1: Install Power BI Desktop**

1. Download Power BI Desktop:
   https://aka.ms/power-bi-desktop
2. Install using the setup wizard.

**Step 2: Import Data**

**2.1 Load Customers Data**

1. Open Power BI Desktop
2. Click **Get Data → Web**
3. Enter:
   https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/customers.csv
4. Click **Load**
   
**2.2 Load Products Data**

Repeat the steps above using:
https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/products.csv

**2.3 Load Orders Data**

Repeat again using:
https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals/raw/master/power-bi/orders.csv

**Step 3: Data Modeling**

1. Go to **Model View**

2. Format **Revenue** column:

   * Select Revenue → Set Format = Currency

3. Create Hierarchy:

   * Right-click **Category** → Create hierarchy
   * Add **ProductName** to hierarchy
   * Rename to: **Categorized Product**

4. Set Data Category:

   * Select **City column** → Set Data Category = City

---

**Step 4: Create Report**

**4.1 Add Title**

* Insert Text Box → “Sales Report”
* Make font bold and size 32

**4.2 Revenue by Category (Column Chart)**

1. Add **Categorized Product**
2. Add **Revenue**
3. Convert to **Stacked Column Chart**

**4.3 Enable Drill-Down**

* Click drill-down icon
* Click on chart to view product-level data

**4.4 Quantity by Category (Pie Chart)**

1. Add **Category**
2. Add **Quantity**
3. Convert to **Pie Chart**

**4.5 Revenue by City (Map)**

1. Add **City**
2. Add **Revenue**
3. Convert to **Map Visualization**

**Step 5: Interactivity**

* Click on a city in the map
* Observe cross-highlighting across visuals
* Use drill-down to explore deeper insights

 **Step 6: Save Project**

* Save file as: `SalesReport.pbix`

**Step 7: (Optional) Publish**

* Sign in to Power BI Service
* Click **Publish**
* Share with workspace

**Key Features**

* Drill-down analysis
* Cross-filtering and highlighting
* Data hierarchy creation
* Interactive dashboards
* Geographic visualization

**Project Files**

* `SalesReport.pbix`

**Author**

Anusha A
