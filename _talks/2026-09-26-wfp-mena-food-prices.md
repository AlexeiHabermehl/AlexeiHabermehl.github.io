---
title: "Predicting Food Price Spikes in MENA Markets"
collection: talks
type: "Team report"
permalink: /dataanalytics/wfp-mena-food-prices
venue: "ITEC-621, American University"
date: 2026-09-26
location: "Washington, DC"
excerpt: "Predictive models of local food prices in Middle East and North Africa (MENA) markets, using the World Food Programme's (WFP) Global Food Prices data, to inform subsidy timing and resource allocation."
---

Built predictive models of local market prices for essential food commodities (e.g., wheat, rice) in MENA countries, to serve as an early warning for price spikes and help time subsidies and allocate resources.

**Data:** the WFP's Global Food Prices dataset — monthly local market prices in USD for 400+ commodities across 98 countries, 1990–2026.

**Methods:** descriptive time-series analysis and OLS, then candidate models including a 3-month lagged model, a region × commodity-category interaction model, a regression tree, and random forests, compared on RMSE.

**Key findings:**
- Lagged global prices are significantly correlated with local MENA market prices.
- Commodity group has the greatest predictive value.
- The lagged interaction model had the lowest RMSE (~3.749).

**Team:** Mohamed Khaled Attia, Alexei Habermehl

[View the report source (Quarto)](/files/FinalProject621.qmd)
