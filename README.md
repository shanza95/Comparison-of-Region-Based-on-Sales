# Regional Sales Comparison

## Problem Statement
The director of a leading organization wants to compare the sales between two regions. He has asked each region operators to record the sales data to compare by region. The upper management wants to visualize the sales data using a dashboard to understand the performance between them and suggest the necessary improvements.

## Insights
- The relevant dataset can be accessed [here](Regional%20Sales%20Analysis-%20Dataset).
- To explore the comparison between two region's sales through an interactive dashboard, refer to the link provided [here](https://public.tableau.com/app/profile/shanza.saleem/viz/SalesComparisonbyRegion_17443116394220/Dashboard).

## Project Overview
This project analyzes sales performance across Primary and Secondary regions to identify trends, patterns, and key business insights. It includes metrics on customer orders, product performance, and sub-category trends, supported by interactive visualizations. It enables stakeholders to identify high-performing markets, assess regional demand, and make data-driven decisions for resource allocation, marketing strategies, and sales optimization.

##  Regional KPI Comparison

| KPI                          | Central              | South                | East                 | West                 |
|------------------------------|----------------------|----------------------|----------------------|----------------------|
| **First Order Date**         | 03/01/2014           | 06/01/2014           | 05/01/2014           | 06/01/2014           |
| **Total Sales**              | $501,240             | $391,722             | $678,781             | $725,458             |
| **Avg. Sales per Order**     | $426.59              | $476.55              | $484.50              | $450.32              |
| **Number of Customers**      | 629                  | 512                  | 674                  | 686                  |
| **Number of Orders**         | 1,175                | 822                  | 1,401                | 1,611                |
| **Products in Sale**         | 1,310                | 1,057                | 1,422                | 1,509                |

**Findings**

- Based on the KPIs analyzed across regions, the *Region- West* is the top performer overall, leading in total sales, number of orders, number of customers, and product count. 
- *Region- East* follows closely, showing strong sales and healthy order volume, making it a solid secondary performer.
- *Region- Central* performs better than *Region- South* in most KPIs, especially in total sales and customer count.
- *Region- South* is the lowest- performing region, with the lowest total sales, fewest customers, and fewest orders.

1. **Order Efficiency**: East and South have higher avg. sales per order, indicating stronger purchasing power compared to West and Central.
2. **Product Diversity**: West leads in number of products sold, suggesting broader product adoption or better inventory distribution.
3. **Growth Opportunities**: Improving sales in South could significantly riase total performance, as it lags behind in all major KPIs.

## Visualizations

### **1. Sales by Sub-Category (Bar Chart)**
   - highlights top-performing sub-categories
   - useful for identifying product focus areas
   - shows contrast between primary vs. secondary regions

| Region       | 🏆 Top 3 Sub-Categories (Highest Sales)                                | ⚠️ Bottom 3 Sub-Categories (Lowest Sales)              |
|-------------|-------------------------------------------------------------------------|---------------------------------------------------------|
| **Central** | 1. Chairs ($85,231) <br> 2. Phones ($72,403) <br> 3. Binders ($56,923) | 1. Fasteners ($778) <br> 2. Labels ($2,451) <br> 3. Envelops ($4,637) |
| **East**    | 1. Phones ($100,615) <br> 2. Chairs ($96,261) <br> 3. Storage ($71,613) | 1. Fasteners ($820) <br> 2. Labels ($2,603)<br> 3. Envelopes ($4,376)|
| **South**   | 1. Phones ($58,304) <br> 2. Machines ($53,891) <br> 3. Chairs ($45,176) | 1. Fasteners ($503) <br> 2. Labels ($2,353) <br> 3. Envelopes ($3,346) |
| **West**    | 1. Chairs ($101,781) <br> 2. Phones ($98,684) <br> 3. Tables ($84,755) | 1. Fasteners ($923) <br> 2. Envelopes ($4,118) <br> 3. Labels ($5,079) |

Overall, *Chairs* and *Phones* consistently dominate sales across all regions, often taking the #1 and #2 positions. The **West region** leads the strongest, with *Chairs* and *Phones* both exceeding $95K+ in total sales.
Similarly, *Fasteners* are the lowest-performing category in every region, usually generating less than $1,000 in sales. Other categories like *Labels*, *Envelopes*, *Art*, and *Supplies* also cluster at the bottom consistently, suggesting low demand or small-ticket consumables.

In contrast, mid-range categories such as *Tables*, *Machines*, *Storage*, and *Binders* show moderate but stable performance, especially in the **West** and **South** regions.

**Strange Observation: Appliances ($0 min sales)**

Reported:

- Min sales: $0
- Max sale: $2,405
- Total sales: $33,956

This usually indicates a data-quality issue, such as:
- Appliances exist in the dataset but their sales values were filtered out or mis-coded.
- Their transaction amounts exist, but the total sales measure is blank or incorrectly aggregated.
- There may be returns or negative adjustments offsetting the full sales amount.

### **2. Monthly Sales per Sub-Category (Line Graph)**
   -    shows month-over-month sales performance
   -    helps identify seasonality and demand patterns
   -    enable comparison of subcategories across time

**West Region**

| Rank | Month & Year   | Sub-Category | Total Sales |
| ---- | -------------- | ------------ | ----------- |
| 1    | **March 2017** | Copiers      | **$14,960**  |
| 2    | December 2016  | Tables       | $9,783       |
| 3    | July 2014      | Supplies     | $8,244       |
| 4    | November 2017  | Tables       | $7,368       |
| 5    | April 2017     | Machines     | $7,350       |
| 6    | November 2014  | Phones       | $7,315       |

**Central Region**
| Rank | Month & Year     | Sub-Category | Total Sales |
| ---- | ---------------- | ------------ | ----------- |
| 1    | **October 2016** | Copiers      | **$17,500**  |
| 2    | September 2014   | Machines     | $14,300      |
| 3    | September 2014   | Binders      | $10,261      |
| 4    | December 2016    | Binders      | $10,194      |

**East Region**
| Rank | Month & Year      | Sub-Category | Total Sales |
| ---- | ----------------- | ------------ | ----------- |
| 1    | **November 2017** | Copiers      | **$11,400**  |
| 2    | November 2014     | Phones       | $11,248      |
| 3    | October 2017      | Copiers      | $11,200      |
| 4    | September 2015    | Bookcases    | $9,724       |
| 5    | May 2016          | Copiers      | $9,240       |

**South Region**
| Rank | Month & Year   | Sub-Category | Total Sales |
| ---- | -------------- | ------------ | ----------- |
| 1    | **March 2014** | Machines     | **$23,460**  |
| 2    | November 2017  | Machines     | $8,000       |
| 3    | March 2015     | Binders      | $6,427       |
| 4    | October 2017   | Tables       | $6,206       |

**Seasonality Patterns:**
- **March** -- Highest overall impact
  March consistently produces major record-breaking spikes, including the singles highest sales month in all regions. 
- **November** appears repeatedly (West, East, South) likely reflecting pre-year-end business spending.
  Corporate and government entities often use remaining budgets -> results in solid sales spikes.
- **September** and *October*, strong but limited in two regions (Central, East), consistently deliver high Copiers and Furniture (Tables) spending, likely tied to Q4 planning.
- **December** is active, but fewer top peaks compared to November. It still reflects end-of-year purchasing, especially Office Supplies (Tables, Binders).
- **July**: In this month, only one region (West), one year (2014) shows a notable spike. This is likely a local/one-time seasonal bump - not a strong cross-regional pattern.
- **April** and **May** spikes seem situational, and not strategic as no multi-region pattern happened.

**Conclusion/ Takeaway for Business Planning:**

Q1 (March)

— Expect the highest volume, especially for Machines and Copiers.
— Critical time for stock & promotions.

Q4 (October–November)

— Strong multi-region buying behavior.
— Ideal for pushing office equipment and tech refresh cycles.

Q3 (September)

— Smaller but predictable procurement wave.

## Tools & Technologies
  - Tableau for visualization
  - Excel/CSV as source data
  - GitHub for version control 
