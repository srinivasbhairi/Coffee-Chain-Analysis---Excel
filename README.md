<img width="828" height="466" alt="image" src="https://github.com/user-attachments/assets/49d1d18b-2a35-4394-b77b-fa58d33948c8" />

SRINIVAS BHAIRI | Data Scientist Aspirant

[Connect me on LinkedIn](https://www.linkedin.com/in/srinivas-bhairi) 


# **Coffee Chain Business Case Study (CCD)**

## **1. Project Context**

CCD (Coffee Chain Business) has been consistently **losing money**. The management wants to understand **why profits are declining** and **which areas of the business are causing losses**.

You have been tasked with:

* Analyzing their historical sales, expenses, and profits.
* Identifying **loss-making products**, markets, and trends.
* Building an **interactive dashboard** to help decision-makers explore data dynamically.

---

## **2. Dataset Overview**

The dataset contains **two tables**:

### **Table 1: Coffee Chain**

Contains detailed data about each store, product, and financial metrics.

| **Feature**       | **Description**                                         |
| ----------------- | ------------------------------------------------------- |
| **Store\_ID**     | Unique identifier of each store                         |
| **COGS**          | Cost of Goods Sold – total direct cost to produce goods |
| **Date**          | Date of sale                                            |
| **Market Size**   | Size of the store (e.g., Small, Medium, Large)          |
| **Market**        | Region where the store operates (North, South, etc.)    |
| **Marketing**     | Marketing expenses spent on promotions                  |
| **Product Line**  | Product line category                                   |
| **Product Type**  | Product sub-category                                    |
| **Product**       | Product name                                            |
| **Profit**        | Net profit generated from the sale                      |
| **Sales**         | Total sales revenue                                     |
| **State**         | State where the store is located                        |
| **Target COGS**   | Pre-defined target cost of goods sold                   |
| **Target Profit** | Target net profit for a product/store                   |
| **Target Sales**  | Target revenue expected                                 |

---

### **Table 2: Product Types**

Contains product classification information.

| **Feature**      | **Description**     |
| ---------------- | ------------------- |
| **Products**     | Product description |
| **Product Type** | Category of product |

---

## **3. Objective**

The main goals of this analysis are:

1. Identify **loss-making products**, markets, and store segments.
2. Compare **actual performance vs. targets**.
3. Provide **data-driven recommendations** to improve profitability.
4. Build an **interactive Google Sheets dashboard** for real-time decision-making.

---

## **4. Dashboard Features**

Your dashboard contains the following **key KPIs and visualizations**:

| **Dashboard Element**                  | **Purpose**                                                      |
| -------------------------------------- | ---------------------------------------------------------------- |
| **Total Revenue**                      | Displays total revenue generated                                 |
| **Total Expenses**                     | Displays overall expenses incurred                               |
| **Net Profit**                         | Total revenue - Total expenses                                   |
| **Target Profit Comparison**           | Shows whether profit targets were met                            |
| **Profit Margin (%)**                  | Percentage of revenue converted into profit                      |
| **Top 5 Profitable Products**          | Bar chart to highlight top-performing products                   |
| **Top 5 Loss-Making Products**         | Bar chart to highlight poor-performing products                  |
| **Loss Indicator vs Profit Indicator** | Total count of loss-making vs profit-making items                |
| **Filters (Slicers)**                  | Year, Market, Product Line, Product Type for dynamic exploration |

---

## **5. Key Insights (Why CCD is Losing Money)**

### **1. High Total Expenses**

* Total revenue is **₹74.1 Lakhs**, but expenses are **₹49.1 Lakhs**.
* A high portion of revenue is consumed by **production and operational costs**, leaving minimal profit.

---

### **2. Very Low Net Profit**

* Net profit is just **₹64,311**, which is **only 0.86% of total revenue**.
* Despite decent sales numbers, inefficiencies are preventing profits from growing.

---

### **3. Many Products Operating at a Loss**

* 7 out of 13 products are **loss-making**.
* **Caffe Mocha** and **Decaf Irish Cream** have the highest negative profit margins.
* These underperformers are pulling down the overall profitability.

---

### **4. Heavy Dependence on a Few Products**

* **Colombian Coffee** alone contributes **₹12,932 profit**, accounting for over **20% of the total net profit**.
* Over-reliance on one product makes the business risky.

---

### **5. Profit Margin Issues**

* Overall profit margin is **30.92%**, below the expected threshold of 40%.
* This suggests either:

  * **Overpricing of raw materials (high COGS)**, or
  * **Underpricing of products**, leading to thin margins.

---

### **6. Variance Between Actual and Target Profits**

* Variance across products shows **significant deviation** from targets.
* Target Profit: **₹63,900**
* Actual Profit: **₹64,311** (Almost equal, but driven by only 5 profitable products).

---

### **7. Regional Performance Inequality**

* Certain markets (like South or Central) have very few profitable products.
* Example: In some regions, only **4 product categories** are performing well, while others consistently lose money.

---

### **8. Inefficient Marketing Spend**

* High marketing expenses **do not correlate with sales growth**.
* Some products with high marketing budgets still show **negative profits**.

---

### **9. Small Store Sizes Underperforming**

* Smaller market-size stores are generating lower revenues but have **fixed overhead costs**, making them unprofitable.

---

### **10. Loss Indicator vs Profit Indicator**

* **Loss Indicator Count: 591**
* **Profit Indicator Count: 451**
* This clearly shows that **more than 56% of products are unprofitable**, which is unsustainable for long-term growth.

---

## **6. Recommendations**

| **Recommendation**                                                      | **Expected Outcome**                   |
| ----------------------------------------------------------------------- | -------------------------------------- |
| Discontinue loss-making products (e.g., Caffe Mocha, Decaf Irish Cream) | Reduce waste and improve profitability |
| Focus marketing on top performers (Colombian, Lemon, Darjeeling)        | Higher ROI on marketing spend          |
| Reduce COGS by negotiating with suppliers                               | Lower production costs                 |
| Expand only in profitable regions and store sizes                       | Avoid losses from small stores         |
| Set realistic profit targets per product                                | Better performance tracking            |

---

## **7. Conclusion**

The analysis shows that CCD’s losses are primarily due to **inefficient cost management, unprofitable products, and unequal regional performance**.
By discontinuing low-performing products, optimizing expenses, and focusing on high-performing areas, CCD can **turn around its profitability**.

---

Would you like me to prepare a **final PDF version** of this report so you can directly upload it to your portfolio?
