Aviation Risk Analysis: What Makes an Aircraft Safe?

Welcome aboard! This project explores 60+ years of global aviation accident data to help a company make smart, **low-risk aircraft purchases**.  
Think of it as a full-stack data investigation  from dirty spreadsheets to dashboard-ready decisions.  



Business Context

The company wants in on the aviation industry (private + commercial), but has **zero insight** into safety risks.  
**My role?** Analyze decades of crash data and figure out:

- What types of aircraft are riskiest?
- Does weather matter?
- Are certain engine types or phases of flight more dangerous?



The Data

-  **Source:** Kaggle, originally from NTSB (National Transportation Safety Board)
-  **Size:** 88,889 rows, 1962–2023  
-  Includes: Aircraft types, damage, fatalities, weather, location, engines, flight purpose, and more



What I Did

Data Cleaning & Prep  
- Smart handling of **missing data** (no blind filling!)
- Categorical normalization (e.g. `Aircraft.damage`, `Weather.Condition`)
- Feature Engineering (e.g. `Total.Injuries`, `Is.Fatal`, `Damage.Level`, `Severity.Score`)

EDA & Visuals  
- **Univariate + Bivariate analysis**  
- **Geospatial heatmaps**  
- Trends over time, aircraft type, weather conditions & more

Dashboard (Tableau)  
- 10+ visuals answering real business questions  
- Interactive filters, maps, fatality rates, and insights
- Built for **non-technical execs**, with storytelling in mind



Key Business Recommendations

1. **Stick to 2-engine, factory-built aircraft** fewer fatal crashes reported  
2. **Avoid single-engine planes in poor visibility (IMC)**  
3. **Invest in aircraft with strong records during takeoff/landing — highest risk phases**



 Files

- `Final_Aviation_ds.ipynb`: Clean, organized Jupyter Notebook (PDF + .ipynb)
- `Severity of Impact.pdf`: Slide deck (for stakeholders)
- `tableau-dashboard-link`: [Coming soon ]



 About Me

> I turn messy data into decisions with storytelling, stats, and a little  flair ✨.  
> Let’s keep people safe while flying smart.





