# COVID-19 ECDC Dataset Analysis


## Introduction
This project analyzes the early global spread of COVID-19 using the European Centre for Disease Prevention and Control (ECDC) dataset. The dataset contains daily reported COVID-19 cases and deaths from December 2019 to 2020, across multiple countries and territories. The goal is to explore temporal trends, compare country-level impacts, evaluate population-adjusted metrics, and study the relationship between cases and deaths.


## Dataset Description
| Column | Description |
|--------|-------------|
| `dateRep` | Date of the reported data |
| `day` | Day of the report (1–31) |
| `month` | Month of the report (1–12) |
| `year` | Year of the report |
| `cases` | Number of new confirmed cases |
| `deaths` | Number of new deaths |
| `countriesAndTerritories` | Country or territory name |
| `geoId` | Geographical identifier (code) |
| `countryterritoryCode` | Country/territory code |
| `popData2019` | Population data for 2019 |

- **Rows:** 9,513  
- **Columns:** 10  
- **Data Types:** `float=1`, `int64=5`, `object=4`  


## Objectives
1. Analyze temporal trends in COVID-19 cases and deaths.  
2. Compare country-wise COVID-19 impact.  
3. Evaluate population-adjusted indicators (cases/deaths per 100,000).  
4. Study the relationship between cases and deaths, including lag effects.  


## Key Insights
- COVID-19 remained low in early 2020, with a major surge from March to early April.  
- The United States and several European countries (Spain, Italy, UK, France, and Germany) had the highest total cases.  
- Small-population territories (San Marino, Andorra, Holy See) show the highest per-capita cases/deaths.  
- Daily cases and deaths are strongly correlated, with a clearer pattern using a 7-day lag.  
- Population size alone does not explain case totals; policy and interventions were crucial.  


## Recommendations
- Implement **early detection and testing** to prevent exponential spread.  
- Apply **timely interventions** (social distancing, travel restrictions, lockdowns).  
- **Strengthen healthcare capacity** to manage surges.  
- Use **population-aware strategies** and monitor per-capita metrics for resource allocation.  
- Make **data-driven policy decisions** based on case-death trends and lag effects.  


## Conclusion
The early COVID-19 pandemic escalated rapidly from minimal cases in January 2020 to a global crisis by April 2020. The impact varied widely across countries, with the U.S. and Europe hardest hit. Small-population territories show high per-capita rates, highlighting the importance of population-aware analysis. Strong correlations between cases and deaths underscore the value of early interventions and data-driven policy decisions. Preparedness, timely response, and continuous monitoring remain crucial for managing ongoing or future pandemics.


