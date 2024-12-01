# Aviation Risk Analysis Project
![alt text](image-1.png)

## Project Overview
This project focuses on analyzing aviation accident data to identify aircraft with the lowest operational risks. The analysis aims to support your company's expansion into the aviation industry by providing actionable insights about safe aircraft models, accident trends, and risk factors. By leveraging historical aviation accident data, we aim to guide data-driven decisions for purchasing and operating aircraft for both commercial and private enterprises.

## Business Problem
Your company is diversifying its portfolio by entering the aviation industry, with plans to purchase and operate airplanes. However, the company lacks critical knowledge about potential risks associated with different aircraft models and operational factors.
As part of this initiative, our primary responsibilities include:

- Stakeholder: Head of the new aviation division who will use the findings to guide purchasing decisions.

### Key Business Questions:
1. Which aircraft makes and models are associated with the lowest accident risks?
2. What are the historical trends in aviation accidents, and how have risks changed for specific aircraft models over time?
3. What operational factors influence accident risks, and how can these insights improve safety decisions?

The ultimate goal is to ensure the company makes informed, risk-averse choices when expanding into this industry.

## Data
The data used for this analysis is sourced from Kaggle's Aviation Accident Database [Dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses), which contains information provided by the National Transportation Safety Board (NTSB).

### Dataset Description:
- Timeframe: Covers aviation accidents and selected incidents from 1962 to 2023.
- Scope: Includes civil aviation accidents and incidents within the United States, its territories, possessions, and international waters.
- Content: Detailed records of aviation accidents, including factors such as aircraft make and model, accident causes, operational details, and severity of outcomes.

This comprehensive dataset allows us to perform in-depth analysis to identify patterns, assess risks, and generate actionable recommendations for safe aircraft acquisition and operations.

# Methods
This project employs a combination of descriptive and analytical methods to assess aviation accident trends and outcomes, providing actionable insights for risk assessment and resource allocation. The key methods include:

## Data Cleaning:

- Outlier Detection: Removed extreme values using Interquartile Range (IQR) thresholds (10th and 90th percentiles) to improve data reliability.
- Imputation: Addressed missing values to ensure consistency and maintain dataset completeness.
## Univariate Analysis:-
- Explored individual variables, such as fatality rates, injury counts, and weather conditions, to understand their distributions and identify significant patterns.
## Bivariate Analysis:
- Investigated relationships between key variables, such as accident frequency by weather conditions, injury severity by aircraft type, and survival rates across aircraft models.
## Trend Analysis:
- Analyzed accident trends, year-over-year changes, yearly fatality rates in accidents and outcomes to understand long-term patterns and assess safety improvements over time.

# Results
### Aircraft Make with Most Accidents:

    - Cessna leads with the highest number of accidents, accounting for over 25,000 incidents.
    - Piper and Beech follow but with significantly fewer accidents.
    - Other aircraft makes, such as Bell, Boeing, Mooney, and Grumman, report much lower accident counts, indicating the concentration of accidents in a few key makes.

![alt text](<Screenshot from 2024-11-30 20-25-10.png>)

### Injury Severity Index:
    - Piper, Beech, Bellanca, and Cessna show similar variability in injury severity, with ranges extending up to 14.
    - Robinson and Mooney exhibit higher median injury severity, highlighting frequent severe injuries for these makes.
    - Boeing has a notably lower median injury severity, suggesting better overall safety outcomes.
    - Outliers exist across all aircraft types, indicating occasional extreme cases of injury severity.

![alt text](<Screenshot from 2024-11-30 20-27-10.png>)

### Trends in Accidents:
    - Aviation accidents have significantly declined since the 1980s, likely due to advancements in safety measures, technology, and stricter regulations.
    - The trend stabilizes after 2010, with minor fluctuations around 2020, suggesting either diminishing returns on safety interventions or new challenges.
    - The steep decline during the 1980s and 1990s reflects major safety improvements driven by industry transformations.

![alt text](<Screenshot from 2024-11-30 20-25-59.png>)

# Summary of Conclusions
The analysis reveals critical insights into aviation safety trends and operational risks:

1. Aircraft Make and Model Risks: Certain aircraft makes, such as Cessna, show disproportionately higher accident counts, while others, like Boeing, demonstrate relatively safer operational profiles.
2. Injury and Damage Severity: Injury severity varies significantly by make, with some (e.g., Mooney and Robinson) exhibiting higher median severities, while others (e.g., Grumman and Boeing) have consistently lower values.
3. Trends Over Time: Accident rates have significantly declined since the 1980s, attributed to technological advancements and regulatory improvements, though progress has plateaued in recent years.

# Recommendations
1. Focus on Low-Risk Aircraft for Procurement
- Select aircraft models with lower accident frequencies, injury severities, and damage severity indices. Prioritize manufacturers like Boeing and Grumman, which show safer profiles based on historical data.

2. Implement Targeted Safety Programs
- Develop operational guidelines tailored to high-risk makes like Cessna and Piper, emphasizing training, maintenance, and risk mitigation strategies to address their specific vulnerabilities.

3. Leverage Historical Trends for Safety Improvements
Study safety measures implemented during the steep decline in accidents (1980s–1990s) and incorporate lessons learned to tackle emerging challenges and further reduce risks.

# Next Steps
1. In-Depth Analysis of High-Risk Makes
- Conduct a detailed analysis of high-risk aircraft makes (e.g., Cessna, Piper) to uncover underlying causes of accidents, such as design flaws, operational factors, or maintenance practices.

2. Investigate Regional Accident Patterns
- Analyze country-level data to understand how geographic factors and regulatory environments impact accident rates and safety outcomes.

3. Create a Risk-Based Decision Framework
- Develop a weighted risk assessment model combining accident frequency, injury severity, and damage severity indices to guide aircraft selection for both commercial and private operations.
4. Improve Data Collection Processes
- Address the high frequency of missing or "unknown" entries, especially in key variables by refining data collection protocols. Collaborate with data providers to ensure comprehensive and accurate reporting.


# For More Information
See the full analysis in the Jupyter Notebook or review this presentation.


