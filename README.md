# Golden Time Blind Spots

A geospatial analysis of ambulance coverage in South Korea, carried out during my research internship at Monash University in Melbourne.

## Question

Which areas fall outside a four-minute ambulance coverage threshold, and where might additional ambulance coverage be needed?

Four minutes was the threshold used for this project. The analysis focused on geographic coverage and population distribution.

## Data and Workflow

```text
Ambulance station locations + administrative areas
                     ↓
       Spatial processing in PostgreSQL
                     ↓
       Coverage analysis + population density
                     ↓
                  QGIS maps
```

**Tools:** PostgreSQL, spatial SQL, DBeaver, QGIS, Docker

## My Contribution

I led the coverage analysis, processed the geospatial data with SQL, and mapped the findings in QGIS. I incorporated population density to put the uncovered areas in context and make the results easier to interpret.

## Findings

The analysis classified about **45% of 18,801 small administrative areas** nationwide as outside the four-minute coverage threshold. The population-density maps highlighted areas near urban boundaries where additional ambulance coverage could be considered.

The 45% figure refers to administrative areas, not the share of the population or recorded ambulance calls.

## What I Learned

Working with spatial data at this scale made query efficiency matter. I learned to pay attention to how SQL queries were structured and to use maps to communicate findings that were difficult to understand from tables alone.

## Report and Scope

[Project report and analysis notes](https://internal-leaf-2e8.notion.site/Golden-Time-Blind-Spots-abfc0cfc07d8405597188082320528c1?pvs=4)

These are findings from the internship analysis under its coverage assumptions, rather than measured response times for individual emergencies. This repository links to the project report and includes the internship certificate; it does not contain the SQL workflow or source datasets.

## Certificate

<p align="center">
  <a href="./assets/monash-university-certificate.png">
    <img src="./assets/monash-university-certificate.png" width="720" alt="Monash University internship certificate" />
  </a>
</p>
