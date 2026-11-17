# EV Parts Research

A research project investigating electric vehicle spare-parts sourcing, market evidence, data quality, and import prioritization for the Ethiopian market.

## Project Overview

The project evaluates selected EV spare-part categories to identify which parts may offer promising import opportunities in Ethiopia. It combines international parts and supplier references with available Ethiopian market evidence.

The analysis uses collected evidence, data cleaning, compatibility assessment, and a weighted multi-criteria scoring model to rank spare-part categories.

## Vehicles Covered

Four electric vehicle models were selected:

- BYD Seagull
- BYD Yuan Up
- Changan BenBen E-Star
- Toyota bZ4X

## Spare-Part Categories

The research covers ten categories:

1. Brake pads
2. Brake discs
3. Cabin air filters
4. Wiper blades
5. Headlights
6. Tail lights
7. Side mirrors
8. Bumpers
9. Fenders/body panels
10. Shock absorbers

## Research Methodology

The research was conducted in two phases:

- **Phase 1:** Initial collection of publicly available online evidence.
- **Phase 2:** Supplementary research to improve evidence coverage, particularly for models with limited initial information.

The collected data was then inspected, cleaned, standardized, and assessed for missing values, duplicates, and compatibility evidence.

Original raw values were preserved alongside cleaned and derived fields to maintain traceability.

## Prioritization Framework

A weighted scoring model was developed using five evaluation criteria:

| Criterion | Weight |
|---|---:|
| Market Relevance | 35% |
| Compatibility Confidence | 25% |
| Local Availability Gap | 20% |
| Sourcing Practicality | 15% |
| Evidence Confidence | 5% |

The model produces comparative scores for the ten spare-part categories and supports the selection of five priority recommendations.

## Repository Contents

- **Analysis notebook:** Complete data-processing, analysis, scoring, and visualization workflow.
- **Raw dataset:** Original collected research observations.
- **Evidence log:** Source information and supporting evidence for collected records.
- **Coverage matrix:** Evidence coverage across vehicle and spare-part combinations.
- **Research notes:** Collection methods, source details, and research limitations.

The raw research files are available in the repository's GitHub Release.

## Reproducibility

The analysis notebook retrieves the required research files from the GitHub Release and runs the processing and analysis workflow.

To reproduce the results:

1. Open the final analysis notebook in Google Colab.
2. Run all cells from beginning to end.
3. Allow the notebook to retrieve the research files and complete the analysis.
4. Review the generated tables, visualizations, rankings, and recommendations.

## Limitations

The research relies on publicly available online information. International parts listings do not necessarily confirm Ethiopian availability, and supplier listings do not always establish exact vehicle compatibility or current stock.

Price information and other unavailable values are treated cautiously rather than assumed. The findings should therefore be interpreted as evidence-based import-prioritization estimates, not confirmed market demand or landed-cost calculations.

## Author

**Mekdes Kiros**

Individual Research Project
