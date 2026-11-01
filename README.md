# 30-Day Social Media Marketing Plan

A ready-to-use 30-day content plan across Instagram, LinkedIn, TikTok, Facebook and X, built around four weekly themes:

1. **Foundation & Awareness** (Days 1-7)
2. **Engagement & Education** (Days 8-14)
3. **Social Proof & Conversion** (Days 15-21)
4. **Community & Scale** (Days 22-30)

## Structure

```
plan/30-day-plan.md          Day-by-day plan grouped by week
plan/strategy.md             Goals, audience, pillars, posting cadence
templates/post-templates.md  Caption/hook templates for each format
data/content_calendar.csv    Importable calendar with status tracking
data/kpi_tracker.csv         Weekly KPI tracker
scripts/generate_calendar.py Regenerates the calendar and plan from one source
```

## Usage

1. Fill in `plan/strategy.md` with your brand, audience and goals.
2. Edit the `DAYS` list in `scripts/generate_calendar.py` to fit your niche.
3. Run `python scripts/generate_calendar.py` to regenerate the plan and CSV.
4. Import the CSV into Google Sheets, Notion or your scheduler.
5. Log results weekly in `data/kpi_tracker.csv`.

## License

MIT
