# League of Legends Champion Analytics

Power BI report analyzing champion data across patches.

## Tech stack
- **PostgreSQL** — relational database with 10+ tables
- **Python / Jupyter** — ETL pipeline for loading patch data
- **Power BI** — 6-page interactive report
- **DAX** — custom measures for time intelligence and rankings

## Report pages
1. Champion release history — roster growth over time
2. Base stats comparison — HP, damage, speed, range across patches
3. Roles and positions — meta distribution
4. Difficulty ratings — heatmap and scatter analysis
5. Champion card — full profile for a selected champion

## Database schema
![Schema](docs/schema.png)

## How to run
1. Install PostgreSQL and create a database
2. Run `database/schema.sql` to create tables and views
3. Run `database/setup.ipynb` to load initial data
4. For each new patch run `notebooks/insert_patch.ipynb`
5. Open `powerbi/report.pbix` and refresh data source

## Data source
Champion data scraped from the official League of Legends wiki.
