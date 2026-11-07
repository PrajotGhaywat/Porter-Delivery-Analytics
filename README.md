# Porter Delivery Analytics – Operations & Business Data Analysis

## 1. Project Overview

This project involves an end-to-end analysis of Porter delivery operations using Microsoft Excel. The objective was to examine order patterns, delivery performance, market-level differences, partner availability, and order value to identify operational trends and generate actionable business insights.

The analysis was performed on approximately **197,428 records**, using Excel's data analysis capabilities, Power Query, Pivot Tables, charts, and statistical techniques.

## 2. Project Objectives

- Analyse order distribution across different markets.
- Evaluate delivery duration across weekdays, weekends, and peak hours.
- Examine delivery partner availability and workload.
- Investigate factors associated with delivery duration.
- Analyse order value and item pricing patterns.
- Apply correlation and regression analysis.
- Translate analytical findings into business recommendations.

## 3. Dataset Overview

| Attribute | Details |
|---|---|
| Dataset | Porter Delivery Operations |
| Total records | Approximately 197,429 |
| Markets | 6 |
| Analytical questions | 20 |
| Analysis tool | Microsoft Excel |
| Supporting tools | Power Query and Jamovi |

The project contains 20 analytical questions divided into three sections:

- Basic Analysis: 10 questions
- Medium Analysis – Part 1: 7 questions
- Medium Analysis – Part 2: 3 questions

## 4. Tools and Techniques

**Microsoft Excel**
- Advanced Excel formulas and functions
- Pivot Tables and Pivot Charts
- Data cleaning and transformation
- Correlation analysis
- Linear regression
- Descriptive statistics
- Data visualisation

**Power Query**
- Data transformation
- Data preparation
- Query-based data processing

**Statistical Analysis**
- Correlation and regression
- Standard deviation and variability analysis
- Comparative analysis
- Outlier investigation

## 5. Key Findings

### Delivery Performance
- Only **13.16% of orders** were delivered within 30 minutes.
- Sunday recorded the highest average delivery duration at approximately **52.72 minutes**.
- Wednesday recorded the lowest average delivery duration at approximately **44.47 minutes**.
- Average delivery duration across the dataset was approximately **48.47 minutes**.

### Order Distribution
- Weekend order volume was approximately **31.8% higher** than weekday order volume.
- Market 2 recorded the highest order volume among the six markets.

### Partner Availability
- Market 2 had the highest average available delivery partners at approximately 4.91.
- Market 1 had the lowest average availability at approximately 0.71 and the highest average delivery duration at approximately 55.21 minutes.
- The correlation between available partners and delivery duration was approximately **-0.029**, indicating an extremely weak negative linear relationship. This does not establish that increasing partner availability will necessarily reduce delivery duration.

### Order Value and Pricing
- The correlation between the number of items in an order and its subtotal was approximately **0.558**, indicating a moderate positive relationship.
- The correlation between the price range of items in an order and its subtotal was approximately **0.510**, also indicating a moderate positive relationship.

### Regression Analysis
A multiple regression analysis examined the relationship between total items, distinct items, and delivery duration.

- R-squared was approximately **0.00456%**.
- Total items was not statistically significant (p = 0.866).
- Number of distinct items was statistically significant (p = 0.039).

Despite the statistical significance of the overall model, its explanatory power was negligible. These variables therefore provide very little practical explanation of delivery duration.

## 6. Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. **Peak-period planning:** Review delivery partner allocation during periods of higher order demand, particularly weekends.
2. **Market-level optimisation:** Investigate why Market 1 has lower partner availability and longer average delivery durations.
3. **Delivery performance monitoring:** Monitor delivery duration by day, market, and peak hour to identify operational bottlenecks.
4. **Partner utilisation:** Evaluate the relationship between partner workload, availability, and delivery performance before changing allocation policies.
5. **Further investigation:** Examine additional variables such as restaurant preparation time, distance, traffic, and order complexity to better understand delivery duration.

## 7. Project Limitations

- Correlation does not establish causation.
- The available variables may not capture all factors influencing delivery duration.
- Extreme delivery-duration observations can influence averages and statistical analysis; these require investigation rather than arbitrary removal.
- Some records have missing market identifiers, which should be considered when interpreting market-level results.
- Customer IDs and order histories used in certain customer-level analyses were simulated and should not be treated as verified customer retention evidence.
- Findings are based on the available dataset and may not generalise to all delivery markets or periods.

## 8. Project Files

| File | Description |
|---|---|
| `Prajot_Porter_Project.xlsx` | Complete Excel workbook containing the original dataset, analysis, calculations, Pivot Tables, charts, and supporting worksheets. |
| `.gitattributes` | Git LFS configuration for large Excel files. |

## 9. Conclusion

This project demonstrates the application of Excel-based analytics to a large operational dataset. It combines data preparation, exploratory analysis, statistical techniques, data visualisation, and business interpretation.

The focus was not only on performing calculations but also on evaluating the practical significance of findings, recognising analytical limitations, and translating results into potential operational improvements.

---

**Tools:** Microsoft Excel | Power Query | Pivot Tables | Jamovi

**Project Category:** Data Analytics | Operations Analytics | Business Intelligence
