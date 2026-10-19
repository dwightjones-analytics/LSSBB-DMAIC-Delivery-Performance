# Improving Process Cycle Efficiency and On-Time Delivery Performance Using DMAIC

## Lean Six Sigma Black Belt Candidate Capstone | Supply Chain Analytics

### Project Overview

This project applies the Lean Six Sigma DMAIC methodology to evaluate historical delivery performance using the publicly available DataCo Smart Supply Chain dataset.

The case study demonstrates data preparation, KPI measurement, Pareto analysis, root-cause hypothesis development, improvement scenario modeling, and process control planning.

**Project Type:** Independent DMAIC analytical case study  
**Tools:** Microsoft Excel, Power Query, PivotTables, Microsoft Word  
**Methodology:** Define, Measure, Analyze, Improve, Control (DMAIC)  
**Status:** Completed analytical case study; proposed improvements not implemented

## Key Performance Indicators

| Metric | Historical Result |
|---|---:|
| Original dataset records | 180,519 |
| Unique orders | 65,752 |
| Canceled orders | 2,855 |
| Eligible orders | 62,897 |
| Late deliveries | 36,048 |
| On-time or early deliveries | 26,849 |
| Late delivery rate | 57.31% |
| On-time delivery rate | 42.69% |

## DMAIC Methodology

### Define
Developed the project charter, problem statement, objectives, and SIPOC framework.

### Measure
Prepared the historical dataset using Power Query, removed duplicate Order IDs for order-level analysis, and calculated baseline delivery-performance KPIs.

### Analyze
Used PivotTables and Pareto analysis to evaluate late deliveries by shipping mode. Developed an Ishikawa diagram and 5 Whys analysis to investigate potential causes.

### Improve
Modeled three hypothetical late-delivery improvement targets:

| Scenario | Target Late Rate | Projected Late Orders Avoided |
|---|---:|---:|
| Moderate | 50% | 4,599 |
| Target | 45% | 7,744 |
| Stretch | 40% | 10,889 |

### Control
Developed a proposed control plan incorporating performance targets, monitoring frequency, responsible roles, and corrective actions.

## Key Findings

- Standard Class accounted for 41.60% of all late deliveries.
- First Class exhibited a 100% late-delivery rate under the dataset's delivery-status classification.
- The baseline late-delivery rate was 57.31%.
- A hypothetical reduction to 45% would correspond to approximately 7,744 fewer late orders at the same eligible order volume.

## Project Deliverables

- **DMAIC Report:** `report/LSSBB_DMAIC_Capstone_Report.pdf`
- **Excel Analysis:** `analysis/LSSBB_DMAIC_Analysis.xlsx`
- **Source Dataset:** DataCo Smart Supply Chain, available through Kaggle.

## Limitations

This project is an independent historical-data case study. Root-cause hypotheses have not been operationally verified, and proposed improvements have not been implemented or tested.

The dataset does not provide sufficient validated value-added processing-time measurements to calculate true Process Cycle Efficiency. Accordingly, the project evaluates delivery reliability and shipping-duration performance rather than claiming a verified improvement in Process Cycle Efficiency.

No realized financial savings or sustained operational performance gains are claimed.

## Data Source

DataCo Smart Supply Chain for Big Data Analysis  
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Professional Development

Prepared as a Lean Six Sigma Black Belt candidate portfolio project. Lean Six Sigma Green Belt certification completed; Black Belt certification not yet earned.