# make-clay-prospect-automation
**Portfolio project for SalesCaptain**
### What i built 
A complete no-code automation in Make.com that:
- Pulls enriched YC B2B prospect data from Google Sheets
- Uses iterator to process every row one by one
- Applies Clay-style formulas and variables:
    - 'clay_priority_score' (High/Medium/Low priority logic)
    - 'clay_enrichment_note' (timestamped enrichment)
    - 'clay_json_ready' (clean JSON object ready for Clay import)
-Writes the processed results into a dedicated "processed for clay" sheet

### Tools used
**Make.com** - Building data workflows and automations
**Google Sheets** - Data source integration
**Clay formulas & JSON scripting**  - Priority scoring, enrichment, and export ready JSON

### Results
Successfully processed 23+ YC B2B prospects with clean Clay-ready output(see screenshots)

**Related Project:**
[Project 1 - YC B2B prospect list scraper (Apify + serper)] (https://github.com/PatriciaStephanie5/yc-prospect-list-scraper)
