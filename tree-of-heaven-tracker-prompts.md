# Tree of Heaven Tracker — Project Prompt Log

A record of the requests used to build the Tree of Heaven Tracker web app for the FIRST LEGO League challenge project.

## 1. Initial Request
Build a website to track the Tree of Heaven (invasive species) for a FIRST LEGO League Challenge project, answering:
- Where are we going to measure it?
- Why are we measuring it?
- What am I going to do with the measurements?
- What am I measuring?
- Track it for two years and provide updates.

## 2. Multi-State, Multi-Year Expansion
Expand tracking to all Tree of Heaven sightings across multiple U.S. states, to find out where it is growing the most and build a removal plan. Track data for a period of five years. Data entry done manually by the parent.

## 3. Treatment Plan Concept
Proposed team solution: a drone equipped with AI-based tracking that flies to Tree of Heaven trees and drops a mixture combining a visual growth-tracking marker with a targeted fungus-based treatment, aimed at killing the tree by disrupting its internal water transport. If it isn't working, apply more; if it is working, continue.

## 4. Sample Data Generation
Add realistic sample data: height measurements for Tree of Heaven across all U.S. states, spanning the past five years, with enough detail (state, location, height, diameter, count, treatment status, notes) for charts to be meaningful.

## 5. Date Range Corrections
- First correction: growth-over-time chart was showing an incorrect year ("2015") — needed to reflect the last five years.
- Second correction: dates should run **backward** from the present (September 2026) to five years prior (September 2021) — not forward into the future.

## 6. Five-Year Treatment Forecast
Given the drone + fungicide treatment plan, forecast the next five years: how many trees would potentially be treated/killed across the top affected states, as an investment/impact projection — chart-based output, no data table.

## 7. Bug Fix — Buttons Unresponsive
All buttons on the page stopped working after adding the forecast section (later traced to and fixed as a JavaScript syntax error from a malformed escaped string).

## 8. Chart Readability Improvements
- Add numeric value labels and y-axis numbers to the "Average Height Over Time" and "Total Tree Count Over Time" charts (previously showed only trend lines with no readable numbers).
- Add numeric labels to the 5-Year Treatment Forecast chart.
- Add numeric labels to the Treatment Status Breakdown chart (monitored / treated / cleared counts).

## 9. Sharing with a Non-Claude User
Requested a way to share the finished HTML app with the daughter's teacher, who does not use Claude.

## 10. Layout Reorganization
Move the "5-Year Treatment Forecast" section to appear below the treated-trees chart; replace its table output with a graph showing trees treated per year, matching the app's other chart styling.

## 11. Most Affected States — Top 10 View
The full state list was hard to read. Changed to show only the **top 10 states** in a bar chart with tree counts labeled directly on the chart, moving all other states into a searchable dropdown.

## 12. Collapsible, Searchable History
Make the full log/history section collapsible (hidden by default, since listing every entry was too long) and searchable, so specific entries can be found without scrolling through everything.

## 13. Download & GitHub Publishing
- Download the finished HTML file.
- Push the file to the public GitHub repository: `https://github.com/sppradeep1983/legochallenger-treeofheaven`.

---

**Live app (Claude Artifact):** https://claude.ai/artifact/Dr51u1oq7pCVXBBJLhhSZH
**Downloaded file:** `tree-of-heaven-tracker.html`
