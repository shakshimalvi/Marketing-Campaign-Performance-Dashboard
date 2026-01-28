# Marketing-Campaign-Performance-Dashboard
###Problem Statement
This project analyzes a dataset of 500 marketing campaigns across various channels (Facebook, Google Ads, Instagram, LinkedIn, Twitter), regions (East, North, South, West), and time periods (primarily 2025, with some in late 2024). The goal is to evaluate campaign performance metrics such as spend, impressions, clicks, conversions, revenue, and derived KPIs (e.g., CTR, CPC, CPA, ROAS, Profit, Conversion Rate). By cleaning the data, creating pivot tables, and building an interactive Excel dashboard, we derive actionable insights to optimize marketing strategies, improve ROI, and identify high-performing channels and regions.
The dataset is sourced from "Marketing_Campaign_Data_Cleaned.xlsx", which includes raw campaign data, pivot aggregations, and a dashboard sheet.

###Workflow

Data Collection: Obtained the raw marketing campaign dataset in Excel format.
Data Cleaning:
Handled inconsistencies (e.g., negative profit margins formatted as absolutes if needed).
Converted date fields from serial numbers to readable formats (e.g., YYYY-MM-DD).
Calculated derived metrics like CTR (Clicks/Impressions * 100), CPC (Spend/Clicks), CPA (Spend/Conversions), ROAS (Revenue/Spend), Profit (Revenue - Spend), and Conversion Rate (Conversions/Clicks * 100).
Ensured data integrity by checking for duplicates, missing values, and outliers.

Data Analysis:
Used PivotTables to aggregate data by channel, region, month, and year.
Computed totals and averages for key metrics (e.g., total impressions: 62,386,067; total conversions: 184,526).
Analyzed trends in ROAS, profit, and efficiency.

Dashboard Creation:
Built an interactive dashboard in Excel using slicers, charts (bar, line, pie), and tables to visualize KPIs.
Included filters for channels, regions, and time periods.
Visualized funnel metrics (impressions → clicks → conversions) and performance comparisons.

Insights and Recommendations: Derived from aggregations and visualizations.

###Dashboard Screenshots
<img width="869" height="556" alt="Screenshot 2026-01-28 191929" src="https://github.com/user-attachments/assets/4e26e08d-1102-423b-9cb6-6e3082d09895" />
<img width="793" height="558" alt="Screenshot 2026-01-28 191919" src="https://github.com/user-attachments/assets/65117549-09b4-46d8-b89b-b523fad8ac9a" />
<img width="698" height="587" alt="Screenshot 2026-01-28 191906" src="https://github.com/user-attachments/assets/548f768e-1a4a-4505-9449-c7f530f16b4e" />
<img width="765" height="585" alt="Screenshot 2026-01-28 191850" src="https://github.com/user-attachments/assets/7c08e347-a06d-425a-bde4-0c1fd61e19fd" />
<img width="779" height="500" alt="Screenshot 2026-01-28 191831" src="https://github.com/user-attachments/assets/ccf0a303-4bf4-4c95-820f-fa5509f9888d" />

###Insights

Overall Performance: Average ROAS is ~2.37, indicating campaigns generate $2.37 in revenue per $1 spent. Total profit across campaigns is $1,808,698, with Instagram leading in profitability ($686,863).
Channel Breakdown: Instagram excels with the highest average ROAS (2.53) and conversion rate (11.86%), while Twitter lags (ROAS: 2.09, CTR: 2.82%). Facebook and Google Ads show balanced performance.
Regional Trends: The South region has the strongest efficiency (ROAS: 2.57, Conversion Rate: 11.01%), driven by targeted audiences. West leads in volume (impressions: 17M+, clicks: 508K) but has room for conversion optimization.
Seasonal Patterns: January shows peak ROAS (2.83) and CTR (3.17%), possibly due to post-holiday boosts. December 2024 has lower efficiency (ROAS: 1.93), indicating seasonal dips.
Funnel Efficiency: Average CTR ~2.96%, Conversion Rate ~10.70%. High impressions (62M+) translate to strong engagement, but opportunities exist to reduce drop-offs.

###Recommendations

Channel Optimization: Shift budget towards Instagram and Facebook for higher returns. Audit and refine Twitter campaigns to improve CTR and ROAS, perhaps by better targeting or creative testing.
Regional Focus: Prioritize South for expansion due to superior efficiency. In West, invest in conversion-focused tactics (e.g., retargeting) to capitalize on high traffic.
Seasonal Strategies: Increase spending in Q1 (Jan-Mar) to leverage high ROAS. Prepare off-season campaigns for Q4 to mitigate dips.
General Improvements: Monitor CPA closely (aim < $20); use A/B testing for underperforming campaigns. Integrate real-time tracking tools for ongoing optimization.
Future Work: Incorporate advanced analytics (e.g., machine learning for prediction) or merge with customer data for deeper segmentation
