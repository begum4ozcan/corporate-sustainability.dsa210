# Corporate Environmental Impact Analysis for DSA210
**Term:** Fall 2025–2026  
**Name:** Begüm Özcan  

---

## Project Proposal
- **Motivation:** This project aims to analyze how company features-such as size , industry, and country development level-influence corporate environmental impact, focusing especially on Turkish firms compared to global peers. My main goal is to understand how the differences in corporate sustainability happen and whether firms from developing economies show specific environmental patterns.
- **Goals:** Through this process, I am planning to explore key relations between factors, visualize patterns, and later develop a machine learning model to predict environmental impact based on company features.

---

## Data Source & Enrichment Plans
- **Main dataset:** [Open Access Dataset of Corporate Environmental Impacts](https://corporate-sustainability.org/an-open-access-dataset-of-corporate-environmental-impacts/) (≈13,000 firm-year observations, 2010-2018). This is a project that includes indicators such s greenhouse gas emmisions, water and energy consumption and environmental intensity ratios of many companies from multiple industries and countries worldwide.
- **Enrichment plan:** I am planning to collect and enhance the analysis by merging the dataset with country-level socioeconomic data from:
  - World Bank Open Data: GDP per capita, population, and economic development indicators.
  - UN Data / Human Development Reports: HDI(human development index)
  - I will try to filter subsets of Turkish firms for detailed comparison.
---

## Data Collection and Preparation Plan
1. **Download Datasets:**
   - Obtain corporate environmental impact dataset.
   - Retrieve country-level GDP and HDI data via the sources mentioned in the enrichment plan. 
2. **Data Integration:**
   - Match company data with country indicators using "country" field.
   - Add derived features (e.e., GDP group classification: high, middle, low income)  
3. **Data Cleaning:**
   -  Handle missing values (through imputation or removal)
   -  Convert text-based fields into categorical or numeric variables.
   -  Standarrdize company-level metrics for consistent comparisons
4. **Exploratory Data Analysis:**
   - Generate statistics, correlations, and visual comparisons betweem Turkey and other regions
   - Formulate intial hypotheses aboutindustry and regional effects.   
5. **Next Steps:**
   - Use this cleaned dataset for hypothesis testing and machine learning tasks in later stages.

---
## Tools
- Python
- GitHub
- `requirements.txt` for dependencies



