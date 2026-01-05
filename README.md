# Global-Water-Access-Analysis
Global Water Access: Data Transformation &amp; Statistical Analysis

A, Project Overview: A demographic and infrastructure study based on the 2020 WHO/UNICEF JMP Dataset. 

Tools and Technologies
- Google Sheets: Primary Engine for data cleaning, transformation and visualization.
- Descriptive Analysis: Used IQR, Standard Deviation, and Quartiles for dispersion analysis.

B, The Data Process (The "Truthful" Workflow)
- Data Cleaning and Schema Alignment: The raw CSV file contained structural errors (delimeter collisions) that misaligned data for several countries. I performed manual data cleansing to realign these records, ensuring the intergrity of the downstream analysis.
- Feature Engineering: *Population Normalization: Converted raw counts into millions for standardized comparison.
- Demographic Derivation: Calculated Rural population shares (100 - Urban%)
- Data Validation: Applied logic constraints to ensure water access percentages remained within a statistically valid 0 - 100% range.
