# **Superstore Profitability Optimization Project**


### ***A Data-Driven Approach to Identifying Loss Drivers and Increasing Profit Margins***


---
<img width="1536" height="1024" alt="ChatGPT Image Oct 6, 2025, 11_52_30 PM" src="https://github.com/user-attachments/assets/070c8788-dffc-436e-98dc-42ae5dadbb3b" />


## **1. Project Overview**

This project investigates a Superstore’s retail operations over several years to identify profitability challenges, evaluate discount policies, and develop actionable strategies to enhance overall performance.

Although the store demonstrates positive net profit, deeper analysis reveals that certain categories—particularly **Furniture**—consistently underperform, dragging down overall margins despite the strong performance of **Technology** and **Office Supplies**.

By leveraging **Microsoft Excel** and **Tableau**, this project explores the interplay between **sales, discounts, regions, product categories, and profitability**, providing a comprehensive profitability optimization roadmap.

**Key Business Questions:**



* Which categories and cities are most and least profitable? \

* What role do discounts play in driving or eroding profits? \

* How do seasonal trends influence profitability? \

* Which regions and customer segments offer the greatest potential for improvement? \



---


## **2. Data Sources**

**Primary Dataset:** *Sample Superstore Orders (2014–2017)*



* **Records:** 2,500+ transactions \

* **Fields:** Category, Sub-Category, Sales, Profit, Quantity, Discount, Segment, Region, State, City, Order Date \

* **Source:** Tableau public dataset \



---


## **3. Tools Used**



* **Microsoft Excel:** Data validation, cleaning, and computation using Power Query and Pivot Tables \

* **Tableau:** Data visualization, dashboard creation, and trend analysis \

* **Power Query:** Data transformation and normalization \



---


## **4. Data Cleaning & Preparation**

**Steps Undertaken:**



1. **Validation**
    * Removed null and duplicate entries \

    * Verified consistency of city and state names \

    * Checked profit and sales data for outliers \

2. **Transformation**
    * Extracted *Year* and *Month* from Order Date \

    * Created calculated fields for *Profit Ratio (%)* and *Discount Rate*
    * Standardized categorical fields and numeric formats \

3. **Standardization**
    * Normalized text case across all fields \

    * Corrected duplicate or inconsistent city entries (e.g., Philadelphia duplicates removed) \



---


## **5. Exploratory Data Analysis (EDA)**

EDA in Tableau and E0xcel revealed patterns and relationships that shaped the final recommendations.



<img width="999" height="1099" alt="Dashboard 2 (2)" src="https://github.com/user-attachments/assets/fe9b00b8-3b7b-44e1-8adb-3a9e466fe947" />

Link to the dashboard [Click Here](https://www.k5learning.com/worksheets/math/grade-6-integer-multiplication-whole-tens-a.pdf)

**Key EDA Activities:**

* Profit distribution by category and subcategory \

* Segment-level performance analysis \

* Discount vs. profit correlation \

* Geographic profit heatmaps (state and city) \

* Time-based sales and profit trends


### **Key Performance Indicators**



* **Total Sales:** $2,297,200.86 \

* **Total Profit:** $286,397.02 \

* **Overall Profit Ratio:** 12% \

* **Average Discount:** 15.62% \

* **Quantity Sold:** 37,873 \

* **Profit per Order:** $28.66 \



---


## **6. Data Analysis**


### **A. Profitability by City**

The top 10 **most profitable cities (in decreasing order)** are: \
 **New York City**, **Los Angeles**, **Seattle**, **San Francisco**, **Detroit**, **Lafayette**, **Jackson**, **Minneapolis**, **San Diego**, and **Portland**.

The **most unprofitable cities** are: \
 **Philadelphia (worst)**, **Houston**, **San Antonio**, **Lancaster**, **Chicago**, **Burlington**, **Dallas**, **Phoenix**, **Aurora**, and **Jacksonville**.

These results reveal a concentration of profitability in coastal and western regions, while losses persist in parts of Texas, Illinois, and Pennsylvania.


---


### **B. Profitability by Category and Subcategory**

The **most profitable product categories** are:



1. Copiers \

2. Phones \

3. Accessories \

4. Paper \

5. Binders \

6. Chairs \


Machines also perform fairly well (**$33,294 profit**) but incurred notable losses (**–$29,909**) that significantly reduced their net contribution.

The **most unprofitable subcategory** is **Tables**, where total losses exceed gains—making it the single largest contributor to negative profit margins.


---


### **C. Profitability by Segment**

All customer segments—**Consumer**, **Corporate**, and **Home Office**—show similar profit ratios, averaging between 4.7% and 6.9%. \
 This indicates that **segment performance is stable**, and profitability challenges stem primarily from **product and pricing**, not customer type.


---


### **D. Monthly Sales and Profit Trends**

The **all-time best sales months (in decreasing order)** are:



1. **November**
2. **December**
3. **September**
4. **March**

However, the **highest sales months do not necessarily yield the highest profit ratios.**



* **December:** 0.13 \

* **August, July, May, March:** 0.14 \

* **October:** 0.16 (highest monthly profit ratio) \


This suggests that high sales months are often **discount-driven**, not **profit-driven**.


### **Monthly Discount Insights**



* Discounts remain relatively stable across months: \

    * **September:** 14.9% \

    * **November:** 15.83% \

    * **December:** 15.04% \

    * **October:** 16.26% \

    * **June:** 16.28% \

    * **May:** 16.54% \

    * **April:** 16.31% \


This pattern shows that **no special discounts were applied during high-sales months**, yet the overall **average discount (15.62%) remains quite high**, confirming that the company’s sales are **heavily discount-driven**.


---


### **E. Geographic Profitability**

The **least profitable states** include:



1. **Texas:** –$25,729.36 \

2. **Ohio:** –$16,971.38 \

3. **Pennsylvania:** –$15,559.96 \

4. **Illinois:** –$12,607.89 \

5. **North Carolina**\
6. **Colorado**\
7. **Tennessee**\
8. **Arizona**\
9. **Florida**
10. **Oregon:** –$1,190.47 \


These regions have remained consistently underperforming over the analysis period, with recurring losses linked to **Furniture** sales and aggressive discounting.


---


### **F. Category-Level Summary**


<table>
  <tr>
   <td><strong>Category</strong>
   </td>
   <td><strong>Profit ($)</strong>
   </td>
   <td><strong>Profit Ratio</strong>
   </td>
   <td><strong>Observation</strong>
   </td>
  </tr>
  <tr>
   <td>Technology
   </td>
   <td>145,454
   </td>
   <td>0.17
   </td>
   <td>Strong performance
   </td>
  </tr>
  <tr>
   <td>Office Supplies
   </td>
   <td>122,490
   </td>
   <td>0.17
   </td>
   <td>Consistent contributor
   </td>
  </tr>
  <tr>
   <td>Furniture
   </td>
   <td>18,451
   </td>
   <td>0.02
   </td>
   <td>Persistently unprofitable
   </td>
  </tr>
</table>


**Key Takeaways:**



* Furniture category’s profit ratio (0.02) is far below that of Office Supplies and Technology (both 0.17). \

* All categories generate similar sales volumes, but Furniture’s high discounts result in severe profit erosion. \

* The Furniture category’s pricing model is unsustainable under the current discount structure. \



---


## **7. Summary of Findings**



* Profitability is concentrated in **specific high-margin products** (Copiers, Phones, Accessories) and **coastal urban markets** (New York, Los Angeles, Seattle). \

* Persistent losses occur in **Tables**, **Furniture**, and **cities like Philadelphia and Houston**. \

* **High discount dependency (avg. 15.62%)** significantly erodes potential profit margins. \

* **No special discounting occurs in peak sales months**, confirming that **sales volume does not directly translate to profit**. \

* **Furniture** remains the consistent drag on profitability due to high discounting and weak margins. \



---


## **8. Recommendations**


### **Short-Term (0–3 Months)**



1. **Suspend deep discounts (>25%)** on Furniture, especially Tables. \

2. **Audit high-loss regions** like Philadelphia, Texas, and Illinois for operational inefficiencies. \

3. **Implement an automated loss-alert system** to flag transactions exceeding a 10% discount threshold. \



### **Mid-Term (3–12 Months)**



1. **Restructure the Furniture category:**\
    * Discontinue persistently unprofitable products. \

    * Re-negotiate supplier terms and logistics. \

    * Introduce margin-based pricing policies. \

2. **Optimize Pricing Strategy:**\
    * Develop a **tiered discount matrix** based on product profitability. \

    * Tie discount approval to margin thresholds. \

    * Focus marketing on high-margin categories like Technology. \

3. **Regional Profit Improvement:**\
    * Apply successful strategies from California and New York to underperforming states. \

    * Consider **strategic withdrawal** from persistently unprofitable areas. \
    * Find cost effective methods in delivery of order which could be a cause for unprofitabilty in certain region.



---


## **9. Limitations**



* Dataset limited to 2014–2017; may not reflect current market dynamics. \

* Potential data anomalies (e.g., Philadelphia’s profit inconsistency). \

* Missing granular cost data (e.g., COGS, logistics). \

* External market conditions not included in the dataset. \



---


## **10. References**



1. Tableau Public Superstore Dataset \

2. McKinsey Margin Tree Framework \

3. Excel Power Query & Pivot Documentation \

4. Tableau Profitability Analysis Whitepapers \

5. Retail Pricing and Profitability Research \





---

**Prepared by:** Samuel Chukwudozie \
 **Date:** 6th November, 2025 \
 **Project Type:** Retail Analytics & Profitability Optimization \
 **Tools Used:** Excel | Tableau | Power Query

![WhatsApp Image 2025-10-06 at 11 55 44 PM](https://github.com/user-attachments/assets/f471809e-bde2-4080-be34-a34b75e2c886)

---
