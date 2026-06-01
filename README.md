# Missing Value Detection & Treatment Analysis 🔍

## Objective
Demonstrate a systematic approach to detecting, visualizing, and resolving missing values in a retail dataset — a critical step before any analytical or modeling work.

## Dataset
Raw retail transaction dataset with intentional and real-world missing values across multiple columns.

## Methods
- Detected missing values across all columns using summary diagnostics
- Visualized missingness patterns before cleaning (heatmaps, bar charts)
- Applied appropriate imputation and removal strategies based on column type
- Re-visualized the dataset after cleaning to confirm resolution
- Documented the impact of cleaning on dataset completeness

## Key Finding
Missing data was non-random in several columns, requiring targeted treatment rather than blanket removal. After cleaning, dataset completeness improved significantly with minimal data loss.

## Tools & Technologies
- **Language:** R
- **Libraries:** dplyr, ggplot2, naniar (or VIM)
- **Analysis type:** Data quality / cleaning pipeline
