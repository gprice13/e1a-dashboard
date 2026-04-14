# E1a Solo Station — Program Dashboard

Program dashboard for the E1a Solo Station payment terminal, focused on SW/ESW/SQUID workstreams.

## 🔗 Live Dashboard
**GitHub Pages:** https://gprice13.github.io/e1a-dashboard/

## 📊 Data Source
[E1a Dashboard Data (Google Sheet)](https://docs.google.com/spreadsheets/d/1CS1v8ZKjElIqd4_OZvsDCoYdYB7DpGZ2FVAx_A-qcQQ/edit)

## Updating the Dashboard

### Workflow:
1. Edit the [Google Sheet](https://docs.google.com/spreadsheets/d/1CS1v8ZKjElIqd4_OZvsDCoYdYB7DpGZ2FVAx_A-qcQQ/edit) with new milestones, decisions, DRIs, etc.
2. Ask Goose: *"Sync the E1a dashboard from the sheet"*
3. Goose reads the sheet, updates `index.html`, and pushes to this repo
4. GitHub Pages auto-deploys within ~60 seconds

### Dashboard Tabs:
- **Status Hub** — Overview cards + quick links to all E1a docs
- **Timeline** — Gantt chart with all milestones across workstreams
- **DRI Directory** — Searchable team roster
- **Decisions** — Engineering decision tracker with status
- **Dependencies** — Cross-team dependency map

---
*Generated with 🪿 Goose AI*
