# 📊 Superstore Sales & Profit Data Analysis

An end-to-end data analysis project using **Python** and **Jupyter Notebook** to analyze retail store data, uncover hidden profit leaks, identify high-value VIP customers, and visualize geographical sales dominance.

---

## 🚀 Project Overview
This project focuses on exploring a business dataset (`Superstore.csv`) to provide actionable business insights for stakeholders. The analysis covers:
1. **Product Performance Analysis:** Finding which products drive revenue and which cause financial losses.
2. **Customer Segmentation:** Identifying the top 10 VIP clients contributing to the majority of sales.
3. **Geographical Visualization:** Building an interactive geographic map to plot sales distributions across major US hubs.

---

## 🛠️ Tech Stack & Libraries Used
* **Python 3**
* **Pandas:** For data manipulation, cleaning, and aggregation (`groupby`).
* **Folium:** For generating interactive, web-based geographic maps.
* **IPyWidgets:** For rendering interactive components.
* **VS Code (Jupyter Extension):** Environment for code development.

---

## 🔍 Key Insights & Business Discoveries

### 1. Product Performance (The Financial Leak) 🛑
* **The Good:** The **Technology** category is the store's primary cash cow, driving consistent, high profits.
* **The Bad:** The **Furniture** category is suffering from severe margin bleeding. 
* **The Leak:** Even though **Tables** ($206k) and **Bookcases** ($114k) have massive sales volumes, they generated a net loss of **-$17.7k** and **-$3.4k** respectively.
* *💡 Recommendation:* Management must immediately adjust pricing strategies, reduce heavy discounts on furniture, or audit shipping logistics for bulky items.

### 2. High-Value Customers (The VIPs) 💎
* The top revenue generators are **Sean Miller** ($25.0k) and **Tamara Chand** ($19.0k).
* *💡 Recommendation:* Implement targeted loyalty programs to retain the top 10 customers who carry a massive share of the store's revenue.

### 3. Geographical Sales Hubs 🗺️
* Sales are highly concentrated in prime metropolitan areas:
  * **New York City:** $256.3k
  * **Los Angeles:** $175.8k
  * **Seattle:** $119.5k
* *💡 Recommendation:* Focus regional marketing budgets on East and West coast hubs, while auditing lower-performing, high-sales cities (e.g., Philadelphia) for profit efficiency.

---

## 🗺️ Interactive Map Features
Using **Folium**, an interactive map was embedded directly within the notebook.
* **Dynamic Circles:** Circle radius scales proportionally with the total sales of the city.
* **Interactive Popups:** Clicking on any city marker displays its exact name and revenue instantly.

---

## 💻 How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)