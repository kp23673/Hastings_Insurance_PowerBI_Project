## Background

The Commercial team are responsible for developing and delivering Hastings’ Street pricing strategy and driving commercial performance whilst ensuring fair customer outcomes.
Your Commercial Director would like you to identify some pricing opportunities in the data we have available. 
You are given a dummy sample dataset of quotes with sale information (please find column descriptions in the appendix below). 
An existing A/B price test can be analysed, where group A saw no price change and group B received a 1% discount.

## Dataset Overview

- Contains **10,000 rows** and **16 columns**.  
- Related to an **insurance price test experiment**.  
- Records customer **quotes and sales**.  
- Segmented into different **pricing test groups (A & B)**.  
- Purpose:  
  - Analyze the effectiveness of **different pricing strategies**.  
  - Measure the impact on **conversion rates** and **profitability**.
 
## Key Columns in the Dataset  

- **price_test_group** – Identifies the pricing strategy being tested (**A** or **B**).  
- **quote & sale** – Determines whether a customer received a quote and whether they proceeded with the purchase.  
- **net_premium** – The premium amount collected for an insurance policy.  
- **total_profit** – The profit generated from each transaction.  
- **business_provider** – Identifies the source (e.g., **direct, third-party comparison sites**).  
- **vehicle_value, vehicle_age, vehicle_annual_mileage** – Key risk-related factors.  
- **driver_age, transmission, driver_gender** – Additional risk and demographic data.

## Key Findings from the Data Analysis  

### A) Conversion Rate & Performance of Price Test Groups  
- **Group A**: No discount  
- **Group B**: 1% discount  
- Group B has a slightly higher **conversion rate** (**3.53%**) compared to Group A (**2.92%**).  
- Customers in **Group B are more likely to proceed** with the purchase after receiving a quote.  
- Even a small **1% discount increased sales by 16.7%** (from **2.92% to 3.53%**).  

### B) Impact on Premium Revenue  
- The **average net premium** decreased slightly in Group B (**$647.96 vs. $655.50**).  
- This is expected since Group B received a **1% discount** on the price.  

### C) Impact on Profitability  
- Surprisingly, **Group B generated slightly higher profit per sale** (**$70.01 vs. $65.62**).  
- This means the **increase in sales volume compensated for the lower price per sale**.

  
## Why Did These Results Occur?  

### Several factors could explain these results:  

- **Price Sensitivity**: Customers may have been more likely to purchase after seeing even a small price reduction.  
- **Psychological Effect of Discounts**: Even a **1% discount** can create a **perception of value**, leading to more conversions.  
- **Competitive Positioning**: If competitors were offering lower prices, the **1% discount** might have helped **match or undercut** their prices.  
- **Elasticity of Demand**: If the product is **price-sensitive**, small changes can result in **significant differences** in conversion rates.  

## What Should the Next Price Change Be?  

#### **Option 1: Maintain the 1% Discount**  
- If the goal is to **maximize conversions**, the **1% discount is effective**.  
- Increased **conversion rates** could lead to **higher total profit**, even with slightly lower premiums.  

#### **Option 2: Test a Slightly Higher Discount (e.g., 1.5% or 2%)**  
- If demand is **highly price-sensitive**, a **slightly higher discount** could further increase conversions.  
- However, **profitability should be carefully monitored** to ensure margins remain healthy.  

#### **Option 3: Segment-Based Pricing**  
- Instead of a **blanket discount**, pricing could be adjusted based on **customer behavior** or **vehicle risk factors**.  
- **High-risk customers** might receive **lower discounts**, while **price-sensitive customers** could receive **higher discounts**.

## Summary  

Overall, this report provides a **comprehensive analysis** of key insurance metrics, including:  
- **Net premiums, sales, quotes, and profits**  
- Various factors such as **vehicle value, vehicle age, driver age, mileage, business providers, and price test groups**  

### Key Insights:  
- **Higher premiums** are observed for **newer vehicles, younger and older drivers, and higher-value cars** due to increased risk.  
- **Sales performance** varies significantly by **business provider and vehicle make**, helping identify **top-performing channels** and **customer preferences**.  
- The **comparison of price test groups** reveals **which pricing strategies** are more effective in **driving sales and profitability**.  

### Business Impact:  
This analysis supports **data-driven decisions** for:  
- **Pricing optimization**  
- **Targeted marketing**  
- **Improving conversion rates**  
Ultimately, these insights help drive **business growth and profitability**.  




