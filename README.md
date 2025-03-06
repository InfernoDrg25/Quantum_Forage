# Quantum_Forage

## Customer Analytics - Chips Purchase Behavior
This project analyzes customer purchasing behavior for chip products based on transaction data. The goal is to generate insights into customer segments, brand preferences, and pack size trends to support business decision-making.

### Dataset
The dataset consists of transactional data with key attributes such as:
- LYLTY_CARD_NBR: Customer loyalty card number
- TOT_SALES: Total sales per transaction
- BRAND: Brand of the chip product
- LIFESTAGE: Customer segment based on demographic data
- PACK_SIZE: Size of the chip pack (in grams)

### Key Analysis
> Total Spend per Brand by Customer Segment
1. Examined customer spending on different chip brands.
2. Segmented total spend by customer Lifestage.
3. Used ggplot2 in R to create a stacked bar chart visualizing brand spending trends.
> Total Spend by Pack Size
1. Analyzed customer spending based on different pack sizes.
2. Identified the most popular pack sizes in terms of total revenue.
3. Used a bar chart to visualize spending distribution by Pack Size.

### Insights & Findings
- Brand Preferences: Kettle chips had the highest total spend across all customer segments, followed by Smiths and Doritos.
- Customer Segment Trends: Older singles/couples and retirees were among the highest spenders on chips.
- Pack Size Popularity: The most purchased pack sizes were 175g, 150g, and 134g, suggesting customer preference for mid-sized packs.

### Tools & Technologies Used
- R (dplyr, ggplot2)
- Data Visualization (ggplot2)
- Data Wrangling (dplyr)

## Trial Uplift Analysis
This repository contains an analysis of trial uplift over time, based on percentage differences observed from July 2018 to June 2019. The analysis focuses on identifying trends, key insights, and potential factors influencing performance.

### Dataset
The data used in this analysis includes monthly percentage differences in trial uplift. Key observations include:
- Significant peaks in September 2018 and February 2019.
- Sharp declines after major spikes, particularly in March 2019.
- A gradual recovery trend from April 2019 onwards.

### Key Findings
1. High Volatility: The uplift percentage fluctuates significantly, indicating the influence of external factors such as marketing campaigns or seasonal trends.
2. Major Spikes: September 2018 and February 2019 showed the highest uplift, suggesting potential promotional events or market influences.
3. Post-Spike Declines: Sharp decreases were observed following peak months, requiring further investigation into sustainability strategies.
4. Recovery Trends: After April 2019, there was a moderate but steady increase, indicating a possible stabilization phase.

### Future Improvements
1. Investigate external factors influencing uplift (e.g., promotions, market changes).
2. Analyze seasonality trends to determine recurring patterns.
3. Apply predictive modeling to forecast future trial uplift trends.

