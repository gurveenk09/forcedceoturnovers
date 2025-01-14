# Executive Summary
This project explores an algorithm designed to identify companies with a high likelihood of experiencing forced CEO turnover within the next year. 
The analysis spans 31,114 firms from 1993 to 2017, during which 4,420 CEO turnovers occurred—21% (887) were forced, and 79% (3,533) were voluntary.

# Methodology
Python for the exploratory data analysis, predictive modelling using Logistic Regression, LightGBM and RUSBoost

# Key Findings:
Traditional classification models, such as Logistic Regression, proved inadequate for predicting forced CEO turnovers.
The RUSBoost model emerged as the most effective approach, evaluated using the ROC AUC metric.
Influential predictive factors include:
1. CEO tenure
2. Idiosyncratic stock return
3. Company risk metrics

# Limitations:
**Geographical Data:** The absence of firm location data hinders data accuracy verification.
**Analyst Opinions:** The exclusion of analyst opinions and firm downgrades limits comprehensive context analysis.

# Recommendations:
To improve the predictive accuracy of forced CEO turnover models:

1. Integrate geographical data for enhanced accuracy validation.
2. Include analyst opinions or firm downgrades to capture external influences contributing to CEO turnover.
3. These enhancements would provide deeper insights and more effective predictive capabilities for identifying firms likely to experience forced executive departures.
