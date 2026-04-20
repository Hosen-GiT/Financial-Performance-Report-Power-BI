 Project Overview
This project presents an interactive Power BI dashboard built to analyse financial performance across countries, products, and customer segments. Using the Microsoft Financial Sample dataset of 700 transactions spanning 2013–2014, the report visualises key metrics including net sales, profit, discounts, and cost of goods sold (COGS) in a clean single-page layout.
The goal is to provide a clear, interactive view of where revenue is being generated, which products and segments are most profitable, and how performance varies across geographies.

 Objectives

Visualise overall financial performance across a 16-month period
Identify top-performing countries, products, and customer segments by profit
Analyse sales distribution across different product lines and business segments
Enable interactive filtering to explore data from different perspectives
Present financial KPIs in a clean, executive-ready dashboard format


 Dataset Overview
FieldDetailsSourceMicrosoft Financial Sample (Financial_Sample.xlsx)Records700 transactionsPeriodSeptember 2013 – December 2014CountriesCanada, France, Germany, Mexico, United States of AmericaProductsAmarilla, Carretera, Montana, Paseo, VTT, VeloSegmentsGovernment, Enterprise, Midmarket, Small Business, Channel PartnersDiscount BandsNone, Low, Medium, High
Key Metrics
MetricValueTotal Gross Sales$127,931,598Total Discounts$9,205,248Total Net Sales$118,726,350Total COGS$101,832,648Total Profit$16,893,702Total Units Sold1,125,806

 Dashboard Visuals
VisualDescriptionLine ChartProfit trend over time — shows growth from 2013 to 2014Azure MapGeographic profit distribution across 5 countriesClustered Column ChartNet sales broken down by product and customer segmentSlicerInteractive filter for dynamic exploration of the report

 Key Insights

Profit Growth: Total profit grew significantly from $3.87M in 2013 to $13.01M in 2014 — a growth of over 235%
Top Countries by Profit: France ($3.78M), Germany ($3.68M), and Canada ($3.53M) are the strongest performing markets
Top Products by Profit: Paseo ($4.79M), VTT ($3.03M), and Amarilla ($2.81M) lead all product lines
Top Segment by Profit: Government segment dominates with $11.38M — representing 67% of total profit
Discount Impact: $9.2M in discounts were applied across all transactions — a significant cost worth monitoring against retention value
Underperforming Segments: Enterprise and Midmarket segments show relatively low profit contribution compared to their sales volume


 Recommendations

Invest in the Government segment — it drives the majority of profit and should be the primary retention focus
Expand in top markets — France, Germany, and Canada consistently outperform; targeted campaigns could further grow these regions
Promote Paseo and VTT — the two highest-profit products should be prioritised in marketing and upsell strategies
Review discount strategy — $9.2M in discounts is substantial; analyse whether discounts are driving enough volume to justify the cost
Investigate Mexico and the USA — these markets show lower profit contribution and may benefit from localised strategies
Grow Small Business and Channel Partner segments — both show potential but remain well below Government segment performance


🛠️ Tech Stack

Tool: Power BI Desktop
Theme: New Executive
Visuals: Line Chart, Azure Map, Clustered Column Chart, Slicer
Data Source: Microsoft Excel (.xlsx)
Environment: Power BI Desktop (free)


 How to Use

Download or clone this repository

bash   git clone https://github.com/Hosen-GIT/financial-performance-report.git

Open Financial_Performance_Report_Power_BI.pbix in Power BI Desktop
If prompted, update the data source path:
Home → Transform Data → Data Source Settings → point to Financial_Sample.xlsx
Click Refresh to reload the data
Use the slicer on the dashboard to filter and explore


 Author
Akter Hosen
M.Sc. Applied Mathematics for Network and Data Sciences
Hochschule Mittweida, Germany
