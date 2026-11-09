# Video game success factors by region

**Notebook:** [video_game_success_factors.ipynb](./video_game_success_factors.ipynb)

## Task
Find the factors associated with video game sales and identify promising platforms and genres for marketing campaigns in different regions.

## What I did
- Cleaned the dataset: lower-cased columns, handled missing values ('tbd' user scores converted to NaN, missing ratings filled with 'unknown'), converted types, added total sales.
- Analyzed release counts by year and platform life cycles; defined 2014-2016 as the relevant period.
- Compared platforms and genres by total and median sales; checked correlation of critic and user scores with sales.
- Built a user profile for North America, Europe and Japan (top platforms, genres, ESRB ratings).
- Tested two hypotheses on user ratings with Student's t-test.

## Result
Market leaders differ by region: PS4 and XOne in North America, PS3 in Europe, 3DS in Japan. Action and Shooter lead in North America and Europe; Role-Playing and Action in Japan. Critic scores relate to sales more than user scores. PS4 and XOne are the potentially profitable platforms.

## Tools
Python, pandas, NumPy, SciPy, Matplotlib, Seaborn, two-sided Student's t-test
