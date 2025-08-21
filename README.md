# women_child_dev
Analyzes government datasets to uncover trends in health, education, and budget utilization across Indian states. Built with Python and SQL, the project delivers clean data, insights, and visualizations to support policy impact and public welfare.
# Women & Child Development Analytics 🇮🇳

This project analyzes publicly available datasets from the Ministry of Women & Child Development (MoWCD), focusing on health, education, and budget indicators across Indian states. It aims to uncover trends, disparities, and underutilization of schemes to inform data-driven policy decisions.

---

## 🔍 Objectives
- Explore malnutrition, maternal/child mortality, and education enrollment trends
- Assess budget allocation vs. scheme utilization
- Identify states with critical gaps in health and education outcomes

---

## 📂 Datasets Used
- Anaemia prevalence among women and children
- Malnutrition by state and year
- Maternal & infant mortality rates (global and national)
- Education gross enrollment ratios
- Budget allocation and scheme underutilization
- Anganwadi honorarium and state-wise enrollment

---

## 🛠️ Tools & Techniques
- Python (Pandas, Matplotlib, Seaborn)
- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Correlation and trend analysis

---

## 📊 Key Insights
- States with high malnutrition often show low scheme utilization
- Budget allocation does not always correlate with improved outcomes
- Education enrollment disparities persist across regions

---

## 📁 Output Files
- `cleaned_combined_output.csv`: Unified dataset for analysis
- Visualizations (to be added)
- Summary report (in progress)

---

## 🚀 Next Steps
- Build an interactive dashboard (Power BI / Tableau)
- Integrate prompt-powered insights for policy simulation
- Document findings for public health stakeholders

---

## 🤝 Contributions
Open to collaboration on dashboarding, policy modeling, and regional deep-dives.
Analyze and visualize key indicators from government datasets related to women and child development in India. Focus areas include malnutrition, maternal and infant mortality, education enrollment, budget allocation, and scheme utilization. Use Python and data visualization tools to uncover trends, disparities, and policy gaps. Generate insights that can inform public health interventions and resource planning.

Inputs:
- CSV files covering health, education, budget, and scheme data across states and years

Tasks:
- Clean and merge datasets for unified analysis
- Create visualizations (heatmaps, line charts, bar plots) to highlight trends and outliers
- Identify underutilized schemes and correlate with health/education outcomes
- Summarize findings in a dashboard or report

Outputs:
- Cleaned dataset
- Insightful visualizations
- Summary of key findings and recommendations
- "Given a Python + SQL codebase that analyzes government datasets on health, education, and budget usage across Indian states—with tools for data cleaning, visualization, and policy insight generation—design and implement an extension that:

1. Adds interactive dashboards (e.g., using Streamlit or Dash) to visualize key metrics such as literacy rates, maternal health indicators, budget allocation over time, and regional comparisons.
2. Incorporates predictive analytics (e.g., time-series or regression models) to forecast future trends in health outcomes and budget needs.
3. Includes a summary report generation feature that produces polished PDF or HTML policy briefs, complete with visualization snapshots and key insights.
4. Ensures modularity by separating data ingestion, preprocessing, analysis, visualization, and reporting stages for maintainability and reusability.

Provide:
- A high-level architecture outlining components and workflow.
- Sample code snippets (Python) for one or two key modules—such as setting up a Streamlit dashboard and fitting/predicting with a time-series model.
- Suggestions on interactive visualizations (like bar charts, choropleth maps, trend lines).
- "Adapt the existing pipeline to generate mobile-optimized health and budget summary cards, perhaps formatted for WhatsApp or mobile web."
- "Extend the project to allow users to upload latest government CSV/excel files, automatically process and integrate them into visual dashboards and insights summaries."
"Add geospatial analytics: create Indian map visualizations (choropleth) for key indicators over time (e.g., maternal health). Also include clustering of states based on similar trends."
data_ingest.py: handles loading and cleaning

analysis.py: computes trends or forecasts

dashboard.py: serves visuals via Streamlit/Dash

report.py: generates PDF or HTML summaries

"

- 

---

📌 *This project is part of a portfolio focused on real-world analytics with social impact. Built and maintained by Gautam.*
