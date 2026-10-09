---
title: "What Drives Metrorail Fare Evasion? A Regression Analysis"
collection: talks
type: "Analytics memo"
permalink: /dataanalytics/wmata-fare-evasion
venue: "American University"
date: 2025-10-15
location: "Washington, DC"
excerpt: "Regression on WMATA's 2021–2024 Metrorail data to test whether ridership, day of week and holidays explain fare evasion."
---

WMATA faces large budget deficits, and fare evasion is one source of lost revenue. This memo uses WMATA's 2021–2024 data to test how much of daily fare evasion can be explained by ridership, day of the week and holidays.

**Data preparation:** kept Metrorail rides only, removed free-fare days as outliers, and dropped zero and negative values for fare evasion and entries.

**Model:** multiple linear regression. The outcome is non-tapped entries (riders detected skipping the fare). Predictors are average daily entries, average daily exits, day type (weekday/Saturday/Sunday dummies, with Saturday as the reference) and a holiday dummy.

**Key findings:**
- Higher ridership is associated with more fare evasion.
- Holding the other variables constant, weekdays have the highest fare evasion.
- The model explains about 20% of the variance (adjusted R² = 0.195), so most of the variation in fare evasion comes from factors outside this model.

[Read the memo (Word)](/files/Project_4_Habermehl.docx)
