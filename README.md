🌍 Tamil Nadu Tourism Analysis — Power BI Dashboard
An interactive Power BI dashboard analyzing tourist trends, visitor behaviour, destination performance, and revenue for Tamil Nadu across 2022–2025.

📌 Project Overview
Tamil Nadu welcomes millions of domestic and international visitors every year, but raw tourism data — arrivals, spending, destinations, seasonality — is hard to read at a glance. This project consolidates that data into a single Power BI report so trends, destination performance, and visitor behaviour can be understood in seconds instead of spreadsheets.
Guiding questions
-> Is tourism growing year over year?
-> Which destinations perform best, and why?
-> Who is the typical visitor, and what do they do?
-> When and how is revenue actually earned?

📊 Dataset
Source: Tourism_Data table (~2,500 tourist records)
Time range: 2022 – 2025
Fields include: Tourist ID, Destination, Tourist Type (Domestic/International), Age Group, Gender, Travel Purpose, Transport Mode, Accommodation, Season, Month, Stay Days, Satisfaction Rating, and a spending breakdown (Hotel, Food, Transport, Activity, Shopping)
Replace this section with your actual data source (e.g. Kaggle dataset link, government open-data portal, or synthetic/sample data) and a short data-dictionary if you have one.

🧮 Key DAX Measures
16 measures power every visual in the report, grouped as:
. Group
. Measures
. Core KPIs
. Total Tourists, Total Revenue, Average Spending, Average Stay, Average Satisfaction
. Visitor Segmentation
. Domestic Tourists, International Tourists, Domestic %, International %
. Category Revenue
. Hotel Revenue, Food Revenue, Transport Revenue, Activity Revenue, Shopping Revenue
. Derived Metrics
. Revenue per Tourist, Average Spend per Day


🖥️ Dashboard Pages
1. Tourism Overview
Landing page with 6 KPI cards, a tourist-arrivals trend line, a revenue-vs-volume combo chart, a domestic vs. international donut, and a top-10-destinations map/bar chart. Filterable by Year, Season, Tourist Type and Destination.

<img width="1283" height="732" alt="Screenshot 2026-09-21 031304" src="https://github.com/user-attachments/assets/42595980-2a0f-441a-a75d-9e67b4aa3859" />

2. Destination Performance
Ranks every destination by tourists, revenue, satisfaction and average stay, plus a detail matrix with exact figures per destination.

<img width="1292" height="741" alt="Screenshot 2026-09-21 031339" src="https://github.com/user-attachments/assets/c7c50e86-6118-4810-b502-2549e5119d89" />

3. Tourist Behaviour
Breaks visitors down by age group, gender, travel purpose, transport mode and accommodation type, and compares spending and satisfaction across segments.

<img width="1285" height="740" alt="Screenshot 2026-09-21 031414" src="https://github.com/user-attachments/assets/09ae05de-0558-40ae-a32b-939faba1b840" />

4. Revenue & Seasonal Analysis
Monthly and seasonal revenue/arrival trends, a spending-category breakdown, annual revenue growth, and domestic vs. international revenue comparison.

<img width="1301" height="751" alt="Screenshot 2026-09-21 031446" src="https://github.com/user-attachments/assets/3d135125-3799-4bcb-a102-86de2c0621d7" />


💡 Key Insights
-> Steady growth, then a plateau — arrivals and revenue rose from 2022–2024, easing slightly in 2025.
-> Chennai anchors the map — leads every destination on both arrivals and revenue.
-> Leisure & heritage drive travel — together they account for the majority of trips.
-> International visitors spend more — higher per-person spending despite domestic tourists being the larger group.
-> Peak season carries the year — contributes the bulk of annual tourists and revenue.

🛠️ Tools Used
- Power BI Desktop — report & visuals
- Power Query — data cleaning & load
- DAX — 16 custom measures
- Interactive slicers across all 4 pages

📁 Repository Structure
Code
🚀 How to Use
Clone the repo: git clone https://github.com/<your-username>/tamil-nadu-tourism-analysis.git
Open Tamil_Nadu_Tourism_Analysis.pbix in Power BI Desktop.
Use the slicers on each page (Year, Season, Destination, Tourist Type, etc.) to explore the data interactively.


🙋 Author
Anitha R
https://www.linkedin.com/in/anitha0522 
·aniabhiravi2209@gmail.com
