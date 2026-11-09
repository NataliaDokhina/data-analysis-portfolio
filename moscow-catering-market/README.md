# Moscow catering market: where to open a coffee shop

**Notebook:** [moscow_catering_market_analysis.ipynb](./moscow_catering_market_analysis.ipynb)

## Task
Describe the Moscow food-service market from open data and recommend a district and format for a new coffee shop (including price level and opening hours).

## What I did
- Cleaned the dataset (duplicates by name and address, missing values up to 94% in some columns, left as missing rather than imputed).
- Extracted street names with regular expressions and created a 24/7 flag from the opening-hours text.
- Compared venue categories by count, seating, chain membership, rating, district and street; built choropleth maps (Folium) of ratings, average bill and coffee-shop density by district.
- Detailed study of 1,413 coffee shops: location, 24/7 share, ratings and cappuccino price by district.

## Result
Coffee shops, including 24/7 ones, are concentrated in the Central district, where ratings and competition are highest. Recommended districts: Southern, South-Eastern and Eastern, where coffee shops are few; a 24/7 format is worth considering there. Price should follow the median cup price of the chosen district.

## Tools
Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Plotly, Folium, re, json

Dataset values (street and venue names) are in Russian, as in the open-data source.
