# Tech-Prep-Week4
## Question: 
You are given three Excel tables: 

<br>**1. Sales (OrderID, OrderDate, ProductID, Quantity, SalesAmount)**

**2. Products (ProductID, ProductName, Category)** 

**3. Regions (RegionID, RegionName)** 

Management asks for an interactive dashboard that shows: 

<br>● **Monthly sales trend and weekday-wise performance**
 <br>=TEXT(B2,"MMMM")  and =TEXT(B2,"DDDD") used to find Month name and weekday name from OrderDate. Pivot table created based on month,weekday ,Total sales, count of sales. From the table, the combination of clustured-column  and Line chart created to find monthly trends analysis and weekday wise performace.
 
● **Top 5 products by sales** 
 <br>Make relationship between sales table and Products table based on ProductID . Create a pivot table for list of products and their total sale.Find the total 5 Products using clustured column chart and filter the products and show it using Pie chart for better view.
 
●**Sales contribution by category and region** 
<br>Create a pivot table based on Category, Region and Total sales. From the table, Create a clustured-column chart to find Total sales by category and region.

● **Create a dynamic, interactive dashboard using slicers and filters**
 <br>Create a dashboard by adding Pivot charts, Total Sales, Total Products and slicers for Category and Region .Provide connection to Pivot tables. Slicers and filters are essential tools used in Excel dashboards to transform static data into interactive, dynamic reports. It provide interactive data exploration, Visual Simplicity and Appeal, Synchronized Multi-Chart Control, Focused Analysis for users.
 
● **Leverage Excel AI features (Quick Analysis / AI analyst) to generate insights efficiently**
<br>Excel’s built-in Quick Analysis tool used for instant visualizations and calculations. The AI features like Copilot in Excel can Analyze Data through natural language queries and automated pattern recognition.
<br>**Excel's Quick Analysis Tool**
   <br>  **Core Capabilities:**
  <br> **Formatting:** Instantly apply data bars, color scales, or icon sets to spot top/bottom performers.
 <br>**Charts:** Hover over recommended charts to see live previews tailored to your data set.
 <br>**Totals:** Instantly calculate Running Totals, Sums, Averages, or % of Total across rows or columns without typing formulas.
  <br> **Tables & Sparklines:** Insert quick PivotTables or mini inline trendlines inside cells.
   
   **Excel's AI Analyst**
   ----------------------
   **Key Reasons & Benefits**
   
**1. No Need to Memorize Complex Formulas**

Instead of searching or memorizing syntax for complex functions like XLOOKUP, SUMIFS, or INDEX/MATCH, you can simply type what you want in plain English.
 * Example prompt: "Calculate total sales for South region where amount is over 5000" → AI generates the exact formula automatically.
   
**2. Instant Data Cleaning & Formatting**
   
Data preparation often takes up most of the time in Excel. AI features automate:

 * Removing duplicate entries and standardizing text/date formats.
 * Converting plain text data into structured Excel tables instantly.
 * Applying automated conditional formatting to highlight high/low values or outliers.
   
**3. Automated Data Analysis & Pattern Spotting**

 * AI scans datasets instantly to detect trends, spikes, or sudden declines.
 * It recommends relevant chart types or automatically builds PivotTables tailored to your data context.
 * It creates short executive summaries highlighting top-performing metrics or anomalies.
   
**4. Advanced Python Capabilities Without Coding**

For heavy data analysis, Excel allows users to run Python scripts directly through Copilot prompts. You can perform advanced statistical modeling, predictive forecasting, or custom visualization (using libraries like Pandas or Matplotlib) without writing line-by-line Python code.

**5. Reduces Human Error & Saves Time**

 * Fewer Formula Mistakes: AI-generated logic reduces manual errors in nested or multi-condition calculations.
 * Speed: Tasks that usually take hours—like monthly financial reporting or trend comparison—are completed in seconds.
   
●Justify why you choose specific functions, pivot features, and chart types in your 
approach.
