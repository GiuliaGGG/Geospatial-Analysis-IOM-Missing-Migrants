# Migration Routes, Missing Migrants & Conflict Analysis

**Authors:** Lino Zurmuehl, Giulia Petrilli  
**Language:** R  
**Type:** Geospatial data analysis & visualization project

---

## Overview

This project investigates the relationship between **migration routes, migrant deaths/disappearances, and conflict intensity** across Africa, Europe, and the Mediterranean region.

The analysis produces maps to visualize:

- Migration flows
- Death counts per route
- Conflict intensity by country
- Combined migration–conflict overlays
- Route-level comparisons

The goal is to explore whether **migration routes passing through conflict-affected regions are associated with higher mortality risks**.

---

### Migration Flow Map
- Countries classified as origin, transit, or destination
- Directional arrows illustrate flows
- Major migration corridors highlighted

Output:
![Migration flow map](plots/violence_heatmap_with_bubbles.png)

---

## Key Questions

- Which migration routes show the highest number of deaths?
- Do routes crossing high-conflict regions exhibit greater risks?
- How do origin, transit, and destination countries differ in conflict intensity?
- Is there a relationship between violence levels and migrant mortality?

---

## Data Sources

| Source | Description |
|--------|-------------|
| Missing Migrants Project (IOM) | Deaths and disappearances during migration |
| ACLED | Armed conflict & violent incident records |
| World Bank | Population data for normalization |
| GISCO | Country boundary shapefiles |

