# League of Legends Champion Analytics

Power BI report analyzing champion statistics and release history 
across patches, built on a custom PostgreSQL database with a 
Python ETL pipeline.

## Tech stack
- **PostgreSQL** — relational database with 10+ tables and views
- **Python / Jupyter** — ETL pipeline for loading patch data
- **Power BI / DAX** — 5-page interactive report with custom measures

## Report pages
Preview available in the docs folder.
1. Champion release history — roster growth over time
2. Base stats comparison — HP, damage, speed, range across patches
3. Roles and positions — meta distribution
4. Difficulty ratings — heatmap and scatter analysis
5. Champion card — full profile for a selected champion

## Database schema
![Schema](docs/schema.png)

## Data source
Champion statistics scraped from the League of Legends Wiki,
available via Kaggle:
https://www.kaggle.com/code/laurenainsleyhaines/25-11-league-of-legends-champion-data-exracter
