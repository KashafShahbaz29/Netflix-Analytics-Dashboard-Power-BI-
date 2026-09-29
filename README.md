# Netflix Analytics Dashboard (Power BI)

A 2-page Power BI dashboard exploring Netflix's content catalog and viewership — what's been added over time, what's performing best, and how availability and engagement break down by content type and period.

## Key Metrics

| Metric | Value |
|---|---|
| Total Titles | 50,025 |
| Total Movies | 26,575 |
| Total Shows | 23,450 |
| Total Views | 71bn |
| Total Hours Viewed | 287bn |

## What's in the report

**Overview page**
- Content Added Over Time (2010–2025)
- Content Type Distribution (Movie vs Show)
- Content Type by Views
- Top 5 Shows and Top 5 Movies by Views
- Views by Period (H1 2025 → H1 2026)
- Filters: Release Year, Content Type, Available Globally, Period

**Deep Dive page**
- Top 10 Titles by Views and by Hours Viewed
- Available Globally? split (Yes/No)
- Titles Added by Year (2010–2025)
- Movies vs Shows Views by Period
- Key Insights panel (auto-summarized takeaways: movies outperform shows in views, 70% of catalog available globally, content growth peaked 2023–2024, etc.)

## Tools Used

- Power BI Desktop
- DAX (measures for views, hours viewed, period aggregation, top-N rankings)
- Power Query (data shaping, release year parsing)

## Dataset

Title-level Netflix catalog data (movies and shows) with release year, content type, global availability flag, and period-level view/hours-viewed metrics for H1 2025, H2 2025 and H1 2026.

## Files

- `Netflix_Analytics.pbix` — the Power BI report file
- `screenshots/` — dashboard screenshots used in this README and in the portfolio

## How to use

1. Clone this repo
2. Open `Netflix_Analytics.pbix` in Power BI Desktop
3. Refresh the data source if prompted
