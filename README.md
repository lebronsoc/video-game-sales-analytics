# Video Game Sales Analytics (1971–2024)

An end-to-end data analysis project exploring 50+ years of global video game
sales trends, platform dominance shifts, genre evolution, and a forward-looking
forecast through 2027.
Built entirely on iPad Air using cloud-based tools.

## Business Questions
- How have global video game sales trended across five decades?
- Which genres and platforms have risen or fallen over time?
- What regional markets (NA, Japan, EU) dominate and how has that shifted?
- Which publishers have consistently outperformed the market?
- What do historical patterns predict for the market through 2027?

## Status
🚧 In progress — includes 2027 sales forecast using Excel FORECAST.ETS

## Tools
| Layer | Tool |
|---|---|
| Data cleaning & forecasting | Excel (iPad) |
| SQL analysis | PostgreSQL via Supabase |
| Dashboards & visualization | Looker Studio |
| Version control & portfolio | GitHub |

## Dataset
Video Game Sales 1971–2024 via Maven Analytics (free)
64,016 titles across platforms, genres, publishers, and regional sales figures.
Includes: NA, Japan, EU, Africa, and global sales, critic scores, and release years.

## Key Insights
_Will be filled in on project completion_

## Live Dashboard
_Link will be added once dashboards are complete_

## Project Structure

    video-game-sales-analytics/
    ├── data/
    │   ├── raw/          ← original Maven Analytics CSV
    │   └── clean/        ← cleaned CSV exported from Excel
    ├── sql/
    │   ├── 01_schema.sql
    │   ├── 02_cleaning_queries.sql
    │   └── 03_analysis_queries.sql
    ├── excel/
    │   └── screenshots/  ← formulas, pivot tables, forecast sheet
    └── dashboards/
        ├── screenshots/  ← Looker Studio dashboard exports
        └── LINKS.md      ← live share links

## How to Reproduce
1. Download raw CSV from `data/raw/` (or directly from Maven Analytics)
2. Apply Excel cleaning steps — see `excel/screenshots/` for each stage
3. Run `sql/` scripts in order against any PostgreSQL database
4. Connect Looker Studio to your data source and recreate dashboards

## Macro Context
Channel-level sales projections are directionally validated against
publicly reported gaming industry revenue figures. The global video
game market was valued at approximately $184 billion in 2023 and is
projected to grow consistently through 2027.

## Limitations
- Sales figures represent physical and digital reported units — not all
  digital sales are captured in this dataset
- Data reflects titles with documented sales records — indie and smaller
  releases may be underrepresented
- 2027 forecast is a statistical projection based on historical trends,
  not a guarantee — treat as directional, not precise

> 💡 This entire project was completed on iPad Air using only cloud-based tools —
> no laptop required at any stage.
