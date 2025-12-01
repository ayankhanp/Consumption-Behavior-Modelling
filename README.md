📊 Household Demand Analytics
A business analytics case study exploring household-level consumption behavior and demand drivers across regions
This project analyzes how demographic and economic factors such as income, age, area characteristics, and promotional exposure influence household purchasing intensity for a staple product.
🎯 Project Overview
Households differ in their purchasing behavior due to income levels, age demographics, and regional characteristics. This repository applies consumer behavior analytics, panel data exploration, and demand modelling techniques to uncover:
What drives household purchase intensity?
How does income influence consumption patterns?
Which areas exhibit higher demand concentration?
Do promotions and exposure variables materially affect purchases?
The dataset contains 40,000 household-period observations, making it suitable for predictive analytics, market segmentation, and strategic demand insights.
🧠 Key Business Questions
✔️ Which household characteristics explain higher purchase volumes?
✔️ Does income significantly influence consumption intensity?
✔️ Which geographical clusters show demand concentration?
✔️ Can promotional exposure increase product uptake?
🗂️ Repository Structure
household-demand-analytics/
├─ notebooks/                     # Jupyter/Colab analysis workflows
│  ├─ 01-data-exploration.ipynb
│  └─ 02-demand-modelling.ipynb
├─ data/                          # Sample cleaned dataset or data source link
├─ src/                           # Python modules for preprocessing and metrics
├─ results/                       # Charts, insights, exports
├─ docs/                          # Additional methodology or PDF reports
└─ README.md
📁 Dataset Description
The dataset represents panel data of repeated household observations across time.
Feature	Description
HHID	Household identifier
TIME	Time period index for panel observations
PASTA	Quantity purchased (dependent variable)
EXPOS	Exposure to promotion / advertisement
AGE	Age of household head
INCOME	Household monthly income
AREA	Region/cluster segment
🔍 Analytical Methods Applied
Technique	Purpose
Exploratory Data Analysis	Identify purchase patterns and segmentation
Regression Modelling	Quantify effect of income, exposure, and demographics
Household-level Aggregation	Identify high-demand consumer clusters
Panel Analytics	Capture time-varying household behavior
Visualization & Diagnostics	Business storytelling through insights
📌 Preliminary Insights
🟢 Higher-income households exhibit significantly higher purchase intensity.
🟢 Certain areas/clusters demonstrate disproportionately high demand.
🟢 Promotional exposure (EXPOS) shows actionable uplift potential.
🟢 A small fraction of households contribute major demand volume, indicating concentration risk and cross-selling potential.
🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/<your-user>/household-demand-analytics.git
cd household-demand-analytics
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run notebooks
Open notebooks via Jupyter or Colab to reproduce results and visualizations.
📈 Business Application Potential
This analytics pipeline can support:
Market sizing and regional strategy
Consumer segmentation models
Promotional ROI analysis
Retail demand forecasting
Household-level personalization use cases
It demonstrates the end-to-end capabilities expected in business analytics roles across:
📌 Consulting firms
📌 Retail strategy teams
📌 CPG/FMCG demand analytics units
📌 Data-driven GTM decisioning roles
📜 License
MIT License — open for portfolio demonstration and extension.
🤝 Contributions
Issues and enhancements are welcome. Feel free to fork and extend the demand models.
🏁 Summary
This repository combines structured business analytics, consumer demand modelling, and data-driven storytelling to demonstrate analytical maturity—ideal for consulting, strategy, and data roles where insights must lead to decisions.
