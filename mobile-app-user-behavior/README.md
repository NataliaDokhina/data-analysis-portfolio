# Mobile app user behavior: paths to the target action

**Notebook:** [mobile_app_user_behavior.ipynb](./mobile_app_user_behavior.ipynb)

**Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/natalia.dokhina/viz/_16930704151410/Dashboard1) (labels in Russian; built during the program)

## Task
For a classifieds app, find how the target action (viewing a seller's contacts) relates to other user actions and which scenarios lead to it most often.

## What I did
- Cleaned the event log: unified two names of the same event (`show_contacts` / `contacts_show`), converted timestamps, identified sessions with a 30-minute inactivity threshold.
- Built a Sankey diagram of user paths and extracted the four most common scenarios leading to the target action.
- Built event funnels for each scenario and compared users who reached the target action with those who did not (session length, event mix).
- Tested two hypotheses on conversion with a z-test for proportions.

## Result
The strongest path is map ► recommended listing ► contacts (about 50% conversion at each step). Users who view photos convert better than users who only see recommended listings. Recommendation: review listing rules to encourage sellers to add photos.

## Tools
Python, pandas, NumPy, SciPy, Matplotlib, Plotly, Seaborn, Tableau
