Here’s a walkthrough of how I built the Blinkit dashboard in Power BI:

### **1. Importing and Preparing the Data**
I started by loading my dataset into Power BI, which contains data on total sales, average sales, outlet types, item types, outlet establishment years, and other relevant details. The data was in a MS Excel file, so I used the **“Get Data”** option to import it. Once imported, I cleaned up the data a bit, ensuring there were no missing values, duplicates, or inconsistencies. 

### **2. Setting up the Layout**
I wanted a clear, intuitive layout with essential KPIs at the top and detailed visualizations below. I first divided the Power BI canvas into sections. On the left, I added slicers for filtering by **Outlet Location Type**, **Outlet Size**, and **Outlet Type**. The main section was dedicated to displaying high-level KPIs and visualizations, making it easy for users to navigate.

### **3. Adding Key Performance Indicator (KPI) Cards**
To show the overall business performance metrics like **Total Sales**, **Average Sales**, **Number of Items**, and **Average Ratings**, I used **Card visuals**:
- For each card, I dragged the respective measure (e.g., Total Sales) and dropped it into the card visual.
- I formatted the cards to match Blinkit’s brand colors with yellow backgrounds and bold icons for clarity.

### **4. Visualizing Outlet Establishment Over Time**
Next, I added a **Line Chart** to show the trend of outlet establishments over time. Here’s how I did it:
- I placed the **Year** field on the X-axis and the **Outlet Count** on the Y-axis.
- The chart was formatted to show the increase in outlets from 2012 to 2022, with callouts for specific years like 2015 and 2018 where there were significant spikes in growth.

### **5. Fat Content and Sales Breakdown**
For the **Fat Content** distribution (Low Fat vs Regular), I used a **Donut Chart**:
- I placed **Fat Content** in the legend and **Sales** in the values.
- This chart clearly shows that Regular products accounted for more sales compared to Low Fat products.

Below that, I broke down **Fat Content by Outlet Type** using a **Stacked Bar Chart**, where each bar represents a different outlet tier (Tier 1, 2, or 3) and shows the split between Low Fat and Regular products.

### **6. Total Sales by Item Type**
I wanted to display sales for different item categories, so I used a **Bar Chart**:
- I dragged **Item Type** into the Y-axis and **Sales** into the X-axis.
- This allowed me to visualize which item types were driving the most revenue, such as **Fruits and Vegetables**, **Snacks**, and **Household Items**.

### **7. Outlet Size and Location Breakdown**
I created a **Pie Chart** to show the distribution of sales by **Outlet Size** (Small, Medium, Large). The chart is split into three categories:
- **Small** (20.72% of sales), **Medium** (37.01%), and **Large** (42.27%).
  
Next to this, I used a **Bar Chart** to show total sales by **Outlet Location** (Tier 1, Tier 2, and Tier 3), making it easy to see that Tier 3 locations had the highest sales.

### **8. Table for Outlet Type Analysis**
For a detailed breakdown, I created a **Table** visual to compare different outlet types (Grocery Store, Supermarket Type 1/2/3) across several metrics:
- **Total Sales**, **Average Sales**, **Number of Items**, **Average Ratings**, and **Sum of Item Visibility**.
- I also used **conditional formatting** in the Sum of Item Visibility column to highlight higher visibility scores in green and lower scores in red.

### **9. Adding Slicers**
On the left, I added **Slicers** for **Outlet Location Type**, **Outlet Size**, and **Outlet Type** to allow users to interactively filter the dashboard. This lets users drill down into specific details, such as analyzing only Tier 1 outlets or focusing on a specific outlet size.

### **10. Final Formatting and Design**
To give the dashboard a polished look:
- I used Blinkit’s brand colors (yellow, green) across the visuals.
- I made sure all fonts and labels were clearly readable and appropriately sized.
- I set up interactions between the slicers and visuals, ensuring everything updates dynamically when filters are applied.
