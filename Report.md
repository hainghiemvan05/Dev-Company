# 1. Sales Performance

![Sales Performance](https://github.com/hainghiemvan05/Dev-Company/blob/18d3633bc8f69a01673931c8a1a4ea98aa5e8e75/image/Sales%20Performance%20Analysis_page-0002.jpg)

- The company's profits have consistently reached 111M over the years and remained stable at around 8,600 orders. 
  - February always sees a decrease in revenue and the number of orders. Customers tend to spend more towards the end of the year.
  - Products 25 and 26 are the most frequently ordered products, generating 2.3 million in revenue each month.

--- 
# 2. Marketing Eficiency

![Marketing Eficiency](https://github.com/hainghiemvan05/Dev-Company/blob/18d3633bc8f69a01673931c8a1a4ea98aa5e8e75/image/Sales%20Performance%20Analysis_page-0003.jpg)

- All advertising campaigns had negative ROI. Campaigns 3 and 5 were the most expensive and least effective in Northeast.
- Direct mail accounts for the largest portion of expenses. Email marketing is the channel that generates the most revenue (overall campaigns).


# 3. Market Geography

![Market Geography](https://github.com/hainghiemvan05/Dev-Company/blob/18d3633bc8f69a01673931c8a1a4ea98aa5e8e75/image/Sales%20Performance%20Analysis_page-0004.jpg)


  - The West and Midwest are the most successful markets, with California leading nationwide.
  - Market penetration is significantly higher in the West and Midwest compared to other regions.
  - Large regions like California and Florida have relatively low Market Penetration indices.

--- 

# 6.Recommendation
# 🚀 Future Phase: Predictive Analytics with Machine Learning

While currently focused on descriptive analytics of historical records, the next phase will introduce predictive forecasting via Machine Learning to drive proactive business decisions.

---

### 📈 1. Sales Forecasting (Time Series Modeling)

* **Context:** Instead of only looking at flat revenue trends (2014-2018), I will utilize Machine Learning to predict future performance.
* **Objective:** Forecast monthly and quarterly revenue for the upcoming year by applying advanced models like **XGBoost** to historical data.
* **Business Value:** * Enables the **Warehouse department** to anticipate demand shifts.
    * Optimizes inventory levels for **Bestsellers (Items 25 & 26)** before peak seasons.
* **Outcome:** Prevents "stock-outs" and ensures high-profit **Wholesale clients** always find their preferred products available.

---

### 🎯 2. Predictive Marketing ROI (Campaign Pre-Evaluation)

* **Context:** Moving away from post-mortem analysis of "money-burning" campaigns (e.g., Campaigns 3 and 5), we will evaluate potential ROI upfront.
* **Objective:** Build a classification/regression model to predict success levels (**High vs. Low ROI**) before committing the marketing budget.
* **Data Features:** The model will analyze key variables:
    * `Strategy Type`
    * `Region`
    * `Budget (Cost)`
    * `Local Median Income`
* **Business Value:** Empowers Marketing Managers to select the optimal strategy per region (e.g., "Email Marketing" vs. "Digital Ads" in California).
* **Outcome:** Minimizes wasted spend on low-performing plans and reallocates resources to high-ROI strategies, similar to the success seen in **Campaign 9**.

---

