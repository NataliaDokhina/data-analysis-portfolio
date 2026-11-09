# Data analysis portfolio

Natalia Dokhina, MD. Physician (pediatric hematology/oncology) and certified Data Analyst.

Projects completed in the Data Analysis Professional program (Python, SQL, Tableau), 2023.
Stack: Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Plotly, Folium, Tableau, DataLens.

| # | Project | What I did | Tools |
|---|---------|-----------|-------|
| 1 | [A/B test validity and results](./ab-test-analysis) | Checked the test against its specification (group balance, sample size, overlapping tests, observation window, concurrent marketing), built event funnels, and compared conversion between groups with a z-test for proportions | pandas, NumPy, SciPy, Matplotlib, Seaborn, Plotly |
| 2 | [Mobile app user behavior](./mobile-app-user-behavior) | Session identification from an event log, Sankey diagram of user paths, event funnels for the main scenarios, hypothesis tests on conversion; Tableau Public dashboard (in Russian) | pandas, Plotly, Matplotlib, Tableau |
| 3 | [Video game success factors](./video-game-success-factors) | Cleaned sales data, defined the relevant period, compared platforms and genres by region, correlation of reviews with sales, t-tests on user ratings | pandas, Seaborn, Matplotlib, SciPy |
| 4 | [Moscow catering market](./moscow-catering-market) | Cleaned open data on 8,000+ venues, extracted street names with regular expressions, choropleth maps by district, recommended a district and format for a new coffee shop | pandas, Plotly, Folium, Seaborn |
| 5 | [Medical dashboard](./medical-dashboard) | Dashboard of population morbidity and mortality by region, built from tabular public-health data | DataLens |

Each folder contains a Jupyter notebook with the full workflow (data preprocessing, exploratory analysis, hypothesis testing, conclusions) and a README with the summary.

**A note on language.** The notebooks were written in Russian during the program and translated into English in November 2026. Code, markdown and chart labels are in English; a few figures rendered before translation still show Russian axis labels, and dataset values (street and venue names from the Moscow open-data source) remain in the original language.

New projects on clinical research data quality and lifestyle factors in oncology (HINTS, NHANES, Project Data Sphere) are in progress and will be published here.
