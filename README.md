## **📊 Data Analysis Project: Puma US Interactive Sales Data**  

### **📌 About the Dataset**  
This dataset contains **detailed sales information** for **Puma products** sold across various regions in the **United States**. It includes multiple columns that capture essential sales metrics, geographic data, product details, and financial information. The dataset allows for a **comprehensive analysis** of:  
- Sales performance  
- Profitability  
- Regional trends  

---

### **📂 Dataset Description**  
Below is a detailed description of each column:  

| Column Name       | Data Type      | Description |
|------------------|--------------|-------------|
| **Retailer**       | Categorical   | Represents the name of the retailer selling Puma products (e.g., 'Foot Locker'). |
| **Retailer ID**    | Numerical (Integer) | A unique identifier assigned to each retailer. |
| **Invoice Date**   | DateTime      | The date on which the sales transaction was recorded (useful for time-series analysis). |
| **Region**         | Categorical   | Indicates the geographical region within the U.S. where the sale occurred (e.g., 'Northeast'). |
| **State**         | Categorical   | The specific state where the sale took place (e.g., 'New York'). |
| **City**          | Categorical   | The city where the sale was made (e.g., 'New York City'). |
| **Product**       | Categorical   | Describes the product category (e.g., 'Men's Street Footwear', 'Women's Athletic Footwear'). |
| **Price per Unit** | Numerical (Float) | The unit price of the product sold (used for revenue calculations). |
| **Units Sold**    | Numerical (Integer) | The number of units sold in each transaction. |
| **Total Sales**   | Numerical (Float) | The total revenue generated (`Price per Unit × Units Sold`). |
| **Operating Profit** | Numerical (Float) | The profit earned after deducting operating expenses from total sales. |
| **Operating Margin** | Numerical (Float) | The percentage of sales converted into profit (`Operating Profit / Total Sales`). |
| **Sales Method**  | Categorical   | Indicates the sales channel (e.g., 'In-store'). |

---

### **📊 Key Insights & Analysis**  
*1. Sales Distribution by Sales Method: The violin plot revealed significant variations in
total sales across different sales methods. For instance, the distribution shows that
in-store sales tend to have higher variability compared to online sales. This insight
suggests that Puma might benefit from optimizing in-store strategies to reduce variability
and enhance performance consistency.
2. Correlation Between Sales Metrics: The heatmap of correlations among numeric
variables highlighted strong relationships between total sales, operating profit, and
operating margin. Notably, higher total sales are closely correlated with higher operating
profits. This indicates that focusing on strategies that boost total sales could directly
improve profitability.
3. Sales Performance by Product: The bar plot illustrating total sales by product showed
clear differences in sales performance across various product categories.
High-performing products can be prioritized for marketing and inventory, while
underperforming products may require strategic adjustments or discontinuation.
4. Distribution of Units Sold: The histogram of units sold indicated a common range of
sales volumes with some significant outliers. This information can help in inventory
planning by identifying typical sales volumes and preparing for potential high-demand
spikes.
5. Operating Profit by Product: The strip plot revealed variations in operating profit
across different products. Products with higher operating profits can be targeted for
pricing optimization and marketing strategies to maximize profitability.
6. Regional Sales Distribution: The pie chart showing total sales by region highlighted key
regions contributing to sales revenue. Regions with higher sales percentages should be
targeted for further expansion and marketing efforts, while regions with lower sales might
need customized strategies to boost performance.
7. Sales Trends Over Time: The line plot of total sales over time by month uncovered
seasonal trends and fluctuations in sales performance. Understanding these trends helps
in forecasting future sales and planning inventory and marketing activities accordingly.
> *  

Example:  
✅ The **Northeast region** generates the highest revenue.  
✅ **Men's Street Footwear** contributes to **40%** of total sales.  
✅ The **Operating Margin** is highest in **California** due to strong demand.  

---


Example:  
- 🔹 **Bar chart**: Sales by region  
- 🔹 **Pie chart**: Revenue contribution by product category  
- 🔹 **Time-series plot**: Sales trend over time  

---

### **🚀 How to Use This Project**  
1️⃣ **Clone the repository**:  
```bash
git clone https://github.com/your-username/data-analysis-project1.git
```
2️⃣ **Open the Jupyter Notebook (if applicable)**  
```bash
jupyter notebook analysis.ipynb
```
3️⃣ **Run the analysis & explore insights!**  

---



### **🔗 References & Credits**  
*data set from kaggle*  
