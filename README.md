# MAIB-Maritime-Incident-Analysis

This project analyzes a cleaned MAIB-style maritime incident dataset using Python and Jupyter notebooks.  
The goal is to explore reporting patterns, incident severity, event types, geography, environmental conditions, SAR involvement, and narrative trends across incidents.

## Project objective

The analysis is divided into six parts to build a structured exploratory data analysis portfolio project suitable for GitHub and job applications.

## Dataset

- Source: MAIB / maritime incident occurrence dataset 'occurences.csv'
- File used: `occurrences_cleaned.csv`
- Total records analyzed: 8,599
- Date coverage: 2018 to 2025

## Tools used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Repository structure

```text
maib-maritime-incidents-analysis/
├── README.md
├── .gitignore
├── requirements.txt
├── occurrences_cleaned.csv
├── notebooks/
│   ├── Part-1-Overview.ipynb
│   ├── Part-2-Severity-and-Incident-Types.ipynb
│   ├── Part-3-Location-and-Geography.ipynb
│   ├── Part-4-Environment-and-Conditions.ipynb
│   ├── Part-5-SAR-and-Operational-Patterns.ipynb
│   └── Part-6-Narrative-Patterns-and-Case-Examples.ipynb
└── images/
```

## Notebook guide

### Part 1 — Overview
Covers dataset shape, columns, missing values, date range, and yearly incident counts.

### Part 2 — Severity and incident types
Explores severity distribution, broad event categories, and how severity varies across event types.

### Part 3 — Location and geography
Examines reporting states, accident locations, ports, and geographic patterns in the incidents.

### Part 4 — Environment and conditions
Analyzes natural light, sea state, visibility, weather, and wind-related distributions.

### Part 5 — SAR and operational patterns
Looks at search-and-rescue involvement and related operational trends.

### Part 6 — Narrative patterns and case examples
Studies short and full descriptions, text lengths, common terms, and example incidents by severity and event category.

## Key findings

- The dataset contains 8,599 reported incidents across 2018–2025.
- Reporting volume becomes substantial from 2020 onward.
- A large share of environmental fields contain unknown or missing values, which is itself an important data-quality finding.
- Severity, main event type, and SAR involvement show useful operational patterns for further investigation.
- Narrative fields are rich enough to support text-based pattern exploration and case examples.

## How to run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
4. Run the notebooks in order from Part 1 to Part 6.

## Future work

- Build an interactive dashboard
- Add maps and richer visual summaries
- Export cleaned visuals for presentation use
