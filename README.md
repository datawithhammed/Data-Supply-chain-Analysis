# 📦 DataCo Supply Chain Performance Review
### An End-to-End Data Analysis using Excel | Power BI | 2015–2018
 
---
 
> **Analyst:** Hammed Adeoye

> **Tool:** Excel, Microsoft Power BI

> **Dataset:** DataCo Smart Supply Chain Dataset (180,519 rows | 53 columns)

> **Contact:** hammedadeoye2000@gmail.com
 
---

## 📌 Project Overview
 
This project presents a comprehensive performance review of **DataCo's global supply chain operations** spanning four years (2015–2018), but 2018 was an inconclusive year . Using a dataset of over 180,000 order line items across 5 global markets, I designed a 5-page interactive Power BI dashboard that tells the full story of the business — from revenue and profitability to delivery performance and fraud risk.
 
The goal was not just to report numbers, but to **uncover the story behind the data** — asking the hard and right questions that surface operational inefficiencies, financial leakages, and business risks that are invisible on the surface.
 
---


## 🎯 Business Questions Answered
 
1. **How did overall sales and profit perform between 2015 and 2018?**
2. **Which markets, product categories and customer segments drive the most revenue?**
3. **Are high sales volumes translating into high profitability — or are we losing money as we grow?**
4. **How reliable is our delivery system, and which shipping modes are failing customers?**
5. **Are cancelled orders and suspected fraud linked to late deliveries — or are they separate problems?**
6. **Which payment methods and markets carry the highest operational risk?**
---


## 🗂️ Dashboard Structure
 
The dashboard is organized into **5 focused pages**, each answering a specific business question:
 
| Page | Title | Focus |
|---|---|---|
| 1 | Overview | Big picture performance summary |
| 2 | Sales & Revenue | Revenue drivers by market, category and segment |
| 3 | Profit & Loss Analysis | Profitability vs losses and discount impact |
| 4 | Delivery & Shipping Performance | On-time rates, late deliveries and shipping modes |
| 5 | Risk Analysis | Fraud, cancellations and at-risk revenue |
 
---


## 📄 Page 1 — Overview
### *"The Big Picture"*
 
The Overview page serves as the **executive summary** of the entire analysis. It gives any viewer — technical or non-technical — an immediate understanding of how DataCo performed across the full 4-year period.

<img width="1205" height="679" alt="Screenshot 2026-08-18 173439" src="https://github.com/user-attachments/assets/f6ffafae-847c-45d0-b237-731dc88945ce" />



### Key Metrics
| KPI | Value |
|---|---|
| Net Total Sales | **$33.05M** |
| Revenue Lost to Discount | **$3.73M** |
| Total Orders | **65,750** |
| Total Profit | **$3.97M** |
| Total Loss Amount | **($3.88M)** |
| Peak Year | **2015 ($11.09M)** |

 
### Key Findings
- **Sales have been declining since 2015.** The Total Sales by Year line chart reveals a consistent downward trend from the peak of $11.09M in 2015 to an almost negligible figure in 2018 — though it is important to note that *2018 data only covers January to December 1st, making the 2018 figure an incomplete year rather than a true collapse.*

- **Consumer segment dominates orders** with 34,120 orders — nearly double that of Corporate (19,860) and Home Office (11,780) segments combined.

<img width="414" height="489" alt="image" src="https://github.com/user-attachments/assets/ad2701b5-3d5f-47e6-a80c-32e7763d38d0" />




- **Europe leads all markets** with 18,561 orders and $9.77M in net sales, followed closely by LATAM (17,181 orders, $9.24M) and Pacific Asia (17,577 orders, $7.43M).

- **$3.73M was given away in discounts** — a significant revenue leakage that directly impacts bottom-line profitability.

- The interactive **world map** visually confirms DataCo's global reach across North America, South America, Europe, Africa and Asia.

<img width="751" height="503" alt="image" src="https://github.com/user-attachments/assets/74f0a1dc-5839-4214-90f0-3befd1ae58ad" />



---
 
## 📄 Page 2 — Sales & Revenue
### *"Where is the money coming from?"*

This page deep-dives into the **revenue engine** of DataCo — identifying which departments, categories, markets and customer segments generate the most value.

<img width="1120" height="623" alt="Screenshot 2026-08-18 173458" src="https://github.com/user-attachments/assets/458a39eb-e7fe-43b5-8c5e-e58070620fb1" />


### Key Metrics
| KPI | Value |
|---|---|
| Top Department by Revenue | **Fan Shop ($15.38M)** |
| Top Revenue Category | **Fishing ($6.23M)** |
| Highest Sales Market | **Europe ($9.77M)** |
| Average Sales per Order | **$502.71** |
| Profit Margin | **12.00%** |


 ### Key Findings
- **Fan Shop is the highest-grossing department at $15.38M** — significantly ahead of all other departments, suggesting it is the commercial backbone of DataCo's product offering.
- **Fishing is the top revenue-generating category at $6.23M**, followed by Cleats and Camping & Hiking — indicating that outdoor and sports equipment are the strongest product lines.
- **Europe and LATAM are in a near dead heat at the top** — with $9.8M and $9.2M respectively — while Africa trails far behind at just $2.1M, representing a potential growth market that is significantly underpenetrated.
- **Consumers are the dominant customer segment generating $17M** in sales — more than Corporate ($10M) and Home Office ($6M) combined. This signals DataCo's primary market is individual buyers rather than business clients.
- **Standard Class is the most widely used shipping mode** by a large margin, suggesting most customers prioritize cost over speed when placing orders.
- **A 12% profit margin** means DataCo keeps only 12 cents of every dollar earned — highlighting the critical importance of cost management across the supply chain.




## 📄 Page 3 — Profit & Loss Analysis
### *"Are we actually making money?"*

This is the most analytically powerful page of the dashboard. It exposes a deeply concerning paradox at the heart of DataCo's operations: **the more orders the business receives, the more money it loses.**


<img width="1123" height="627" alt="Screenshot 2026-08-18 173512" src="https://github.com/user-attachments/assets/4377001e-1dae-4e47-804a-240af9262559" />


### Key Metrics
| KPI | Value |
|---|---|
| Gross Total Sales | **$36.78M** |
| Net Total Sales (After Discount) | **$33.05M** |
| Revenue Lost to Discount | **$3.73M** |
| Total Profit | **$3.97M** |
| Total Loss Amount | **($3.88M)** |



#### 1. The Discount Problem
The difference between Gross Sales ($36.78M) and Net Sales ($33.05M) is **$3.73M** — the total value given away in discounts. This alone nearly wipes out the entire net profit of $3.97M. The data shows an average discount rate of approximately **10.15% uniformly applied across all markets** — regardless of whether a product can absorb that discount without becoming unprofitable.

#### 2. The Profit-Loss Paradox — "The Higher the Profits, the Higher the Losses"
The most shocking finding in the entire analysis is visualized in the market comparison chart:
 
| Market | Total Orders | Total Profit | Total Loss |
|---|---|---|---|
| Europe | 18,561 | $1.2M | ($1.1M) |
| LATAM | 17,181 | $1.1M | ($1.1M) |
| Pacific Asia | 17,577 | $0.9M | ($0.9M) |
| USCA | 8,579 | $0.6M | ($0.5M) |
| Africa | 3,854 | $0.3M | ($0.2M) |
 
**Every market that earns more profit also incurs nearly equal losses.** This is not a coincidence — it is a structural flaw in the pricing and discounting strategy.

<img width="700" height="279" alt="image" src="https://github.com/user-attachments/assets/a53d8eac-67c7-49cf-884e-e1498afa1fff" />




#### 3. More Orders = More Losses
The dual-axis line chart titled *"More Orders = More Losses"* plots Total Loss Amount against Total Orders by Shipping Mode — and the pattern is unmistakable. As order volumes increase across shipping modes, losses follow in lockstep. This is the clearest evidence that **DataCo's growth strategy is not profitable growth** — it is volume-driven growth that carries built-in financial losses.

<img width="834" height="291" alt="image" src="https://github.com/user-attachments/assets/7e70378f-7a52-4550-b9ad-57acf9b8de86" />


#### 4. Payment Type Breakdown
The Total Profit and Total Loss by Payment Type chart reveals that **losses are not isolated to one payment channel** — they occur proportionally across Debit ($1.5M profit vs $1.5M loss), Transfer ($1.1M each), Payment ($0.9M each) and Cash ($0.5M vs $0.4M). This confirms the loss problem is a **product and pricing issue**, not a payment issue.
 
#### Root Cause
The core problem is **blanket discounting** — applying a uniform ~10% discount across all products regardless of their margin profile. High-cost, low-margin products cannot absorb a 10% discount without going negative. The business is essentially subsidizing customers' purchases at its own expense.


 
---

 
## 📄 Page 4 — Delivery & Shipping Performance
### *"Are we getting orders to customers on time?"*
 
This page evaluates the operational health of DataCo's fulfillment system — measuring how reliably orders reach customers and which shipping modes are performing or failing.

<img width="1119" height="622" alt="Screenshot 2026-08-18 173524" src="https://github.com/user-attachments/assets/3e0e9a67-5f33-43fa-b956-dec04feae0d1" />


### Key Metrics
| KPI | Value |
|---|---|
| Total Orders | **65,750** |
| Total Deliveries | **181,000** |
| On Time Delivery % | **40.88%** |
| Late Delivery % | **54.83%** |
| Cancelled Delivery % | **4.30%** |


### Key Findings
 
#### 1. Over Half of All Deliveries Are Late
With a **54.83% late delivery rate**, DataCo is failing the majority of its customers on the most basic promise of e-commerce — getting orders there on time. Only **40.88% of deliveries arrive on time or early**, which is an unacceptably low performance standard for any supply chain operation.
 
#### 2. First Class Shipping is the Worst Performer — By Far
The Late Delivery % by Shipping Mode chart reveals one of the most counterintuitive findings of the entire analysis:
 
| Shipping Mode | Late Delivery % |
|---|---|
| **First Class** | **95.32%** |
| Second Class | 76.63% |
| Same Day | 45.74% |
| Standard Class | 38.07% |

<img width="878" height="352" alt="image" src="https://github.com/user-attachments/assets/0ce0c52b-23f4-478e-a887-6a8265d692fc" />


**First Class — the most premium and expensive shipping option — has a 95.32% late delivery rate with a 0% on-time rate.** Customers paying the highest premium for the fastest service are receiving the worst delivery experience. Standard Class, by contrast, outperforms all other modes with the lowest late delivery rate at 38.07%.
 
This is a **critical customer trust and satisfaction issue** that demands urgent operational review. The scheduled delivery windows for First Class are either unrealistically aggressive or the fulfillment priority system is fundamentally broken.


#### 3. Standard Class Generates the Most Profit
The Total Profit by Shipping Mode chart confirms Standard Class generates **$2.4M in profit** — far ahead of Second Class ($0.8M), First Class ($0.6M) and Same Day ($0.2M). The best-performing shipping mode operationally is also the most profitable — reinforcing the case for rethinking the premium shipping tiers.

<img width="848" height="331" alt="image" src="https://github.com/user-attachments/assets/79819feb-eb44-4bca-8539-a157e90e8ba9" />


#### 4. Delivery Status Breakdown
- Late delivery: 36,000 orders
- Advance shipping: 15,000 orders
- Shipping on time: 12,000 orders
- Shipping cancelled: 3,000 orders

The dominance of late delivery over all other statuses combined confirms this is not an isolated issue but a **systemic operational failure**.

<img width="877" height="321" alt="image" src="https://github.com/user-attachments/assets/b766d70b-6a2a-4e5e-b643-7b24578ddf7c" />



---
 
## 📄 Page 5 — Risk Analysis
### *"What are we losing to fraud and cancellations?"*
 
The final page addresses a critical question that goes beyond standard supply chain metrics — **what hidden risk exists within DataCo's order base?** This page investigates the relationship between cancelled orders, suspected fraud, payment methods and market exposure.
 
### Key Metrics
| KPI | Value |
|---|---|
| Cancelled Orders | **1,367** |
| Suspected Fraud Orders | **1,488** |
| Total Orders "At Risk" | **2,855** |
| Total Revenue "At Risk" | **$1.41M** |
| High Risk Payment Type | **TRANSFER** |

 <img width="1117" height="629" alt="Screenshot 2026-08-18 173536" src="https://github.com/user-attachments/assets/c6720958-dbe9-4974-94a3-8e33a0ccc3c0" />



 
### Key Findings
 
#### 1. Fraud Outpaces Cancellations
At 1,488 suspected fraud orders vs 1,367 cancellations, **fraud is actually the bigger problem** — both in order count and in revenue impact ($741K for fraud vs $668K for cancellations). Together they put **$1.41M of revenue at risk** — 4.26% of total net revenue.



 
#### 2. The TRANSFER Payment Red Flag — 100% Correlation
This is the single most alarming finding of the entire dashboard:
 
**100% of all at-risk orders — both cancelled and suspected fraud — exclusively use TRANSFER as the payment method.** Not a single at-risk order was paid via Debit, Cash or standard Payment methods.
 
This is not a statistical coincidence. It is a **clear, actionable pattern** that DataCo's risk management team can act on immediately. A simple rule flagging Transfer payment orders for additional verification before processing could theoretically prevent all 2,855 at-risk orders from ever being fulfilled.

<img width="769" height="359" alt="image" src="https://github.com/user-attachments/assets/58dd6a37-3c66-4c54-a19d-43b6299c7842" />


#### 3. Europe Carries the Highest At-Risk Order Volume
| Market | At Risk Orders |
|---|---|
| **Europe** | **798** |
| LATAM | 767 |
| Pacific Asia | 724 |
| USCA | 401 |
| Africa | 165 |
 
Europe leads in both total orders and at-risk orders — suggesting its high order volume comes with a proportionally higher fraud and cancellation exposure.



#### 4. Late Delivery Does NOT Cause At-Risk Orders
The *"Does Late Delivery Cause Orders At Risk?"* dual-line chart provides crucial analytical clarity. By plotting Late Delivery % against At-Risk Orders across all shipping modes, the lines move in **opposite directions** — proving there is no correlation between late deliveries and order cancellations or fraud.
 
This means **late delivery and at-risk orders are two entirely separate operational problems** with different root causes requiring different solutions:
- Late deliveries → caused by shipping mode inefficiencies
- At-risk orders → caused exclusively by Transfer payment fraud patterns

<img width="973" height="393" alt="image" src="https://github.com/user-attachments/assets/574cd49e-b374-43ac-ad66-1c622616abef" />





#### 5. Consumer Segment Carries the Most Risk
By customer segment, Consumers account for **1,505 at-risk orders** — more than Corporate (839) and Home Office (511) combined. This aligns with the earlier finding that Consumer is the dominant order segment, but also suggests individual buyers are more susceptible to fraud patterns or more likely to cancel.
 
---
 



## 💡 Strategic Recommendations
 
Based on the five-page analysis, I identified the following high-priority recommendations for DataCo's leadership:
 
### 1. 🚨 Overhaul the Discounting Strategy (Highest Priority)
Replace the blanket 10.15% discount applied uniformly across all products with a **margin-aware discount framework**. Products with low profit ratios should either receive no discount or be repriced. This single change could recover a significant portion of the ($3.88M) in losses.
 
### 2. 🚨 Flag Transfer Payments for Fraud Review
Implement an **automated payment screening rule** that flags all Transfer payment orders for manual verification or additional authentication before fulfillment. Given the 100% correlation between Transfer payments and at-risk orders, this is the most immediately actionable fraud prevention measure available.
 
### 3. 🔴 Investigate and Fix First Class Shipping
Conduct an urgent operational review of the First Class delivery process. With a **95.32% late delivery rate**, customers are paying a premium for a service that is almost guaranteed to disappoint. Either the scheduled delivery windows must be extended to realistic timeframes or fulfillment prioritization must be restructured.
 
### 4. 🟠 Focus Growth Efforts on Africa
Africa is significantly underperforming relative to other markets in both order volume and revenue — but it also carries the **lowest at-risk order rate**. This makes it a potentially high-quality growth market where targeted expansion could yield profitable, low-risk revenue growth.
 
### 5. 🟠 Prioritize Standard Class Infrastructure
Since Standard Class generates the most profit and has the lowest late delivery rate, investing in its infrastructure and capacity would yield the highest return on operational investment.
 
---
  

 
## 🛠️ Technical Details
 
### Tools & Technologies
- **Excel (Power Query)**- Data Cleaning and transformation  
- **Microsoft Power BI Desktop** — Dashboard design and visualization
- **DAX (Data Analysis Expressions)** — All KPI calculations and measures


### Dataset Summary
| Attribute | Detail |
|---|---|
| Source | DataCo Smart Supply Chain Dataset (Kaggle) |
| Rows | 180,519 |
| Columns | 53 |
| Date Range | January 2015 – December 2018 |
| Markets Covered | Europe, LATAM, Pacific Asia, USCA, Africa |
| Unique Orders | 65,752 |
| Product Categories | 45+ categories across 7 departments |

 
---


 ## 📊 Summary of Key Numbers
 
| Metric | Value |
|---|---|
| Net Total Sales | $33.05M |
| Gross Sales (Before Discount) | $36.78M |
| Revenue Lost to Discounts | $3.73M |
| Total Profit | $3.97M |
| Total Loss Amount | ($3.88M) |
| Profit Margin | 12.00% |
| Total Unique Orders | 65,752 |
| Peak Year | 2015 ($11.09M) |
| Top Market | Europe ($9.77M) |
| Top Department | Fan Shop ($15.38M) |
| Top Category | Fishing ($6.23M) |
| On Time Delivery Rate | 40.88% |
| Late Delivery Rate | 54.83% |
| Worst Shipping Mode | First Class (95.32% late) |
| Best Shipping Mode | Standard Class (38.07% late) |
| Cancelled Orders | 1,367 |
| Suspected Fraud Orders | 1,488 |
| Total At Risk Orders | 2,855 |
| Total At Risk Revenue | $1.41M |
| High Risk Payment Type | TRANSFER (100%) |
 
---


## 🔑 Conclusion
 
The DataCo Supply Chain Performance Review reveals a business that is **growing in volume but shrinking in quality**. Sales are declining year on year since 2015, losses are growing proportionally with orders, more than half of all deliveries arrive late, and a hidden fraud pattern tied exclusively to Transfer payments is putting $1.41M in revenue at risk.
 
The most important insight from this analysis is not any single metric — it is the **story that connects them all**: DataCo is applying blanket discounts that eat into margins, shipping products through modes that consistently fail customers, and processing fraudulent orders through a payment channel that could be screened with a simple rule.
 
These are not unsolvable problems. They are data-driven opportunities waiting for action — and that is exactly what this dashboard was built to surface.
 
---
 
*Built with 💪 by Hammed Adeoye | Data Analyst*

*Connect with me: hammedadeoye2000@gmail.com*

*LinkedIn : https://www.linkedin.com/in/hammed-adeoye-maami/*
