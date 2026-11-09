# A/B test: validity check and results

**Notebook:** [ab_test_analysis.ipynb](./ab_test_analysis.ipynb)

## Task
Evaluate an A/B test of an improved recommender system in an online store: first check whether the test was run according to its specification, then evaluate the results.

## What I did
- Checked four datasets (events, new users, test participants, marketing campaigns) for missing values, duplicates and data types.
- Verified every condition of the specification: recruitment dates, region, share of EU users (15%), expected sample size (6,000), a 14-day observation window, and the absence of concurrent tests and marketing campaigns.
- Documented each deviation: 75/25 split between groups instead of 50/50; 3,481 participants instead of 6,000; 1,602 users enrolled in a concurrent test; an incomplete observation window for late registrations; test dates overlapping the holiday sales.
- Built event funnels for both groups and compared conversion at each step with a z-test for proportions.

## Result
The expected 10% improvement was not observed; conversion fell at every funnel step and none of the differences were statistically significant (p > 0.05). Because of the deviations above, the test is judged unreliable and a repeat is recommended, with a checklist of conditions to fix.

## Tools
Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, Plotly
