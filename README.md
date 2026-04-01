# Impact of War on Global Economic Indicators

## Project Overview

This project analyzes how global conflicts influence key economic indicators such as gold prices, crude oil prices, wheat prices, and inflation. The goal is to understand whether wars have a measurable economic impact and how that impact manifests over time.

Instead of focusing on prediction, this project emphasizes data analysis, trend discovery, and real-world insights.

---

## Problem Statement

Global conflicts are often believed to disrupt economies, but the extent and nature of their impact are not always clear.

This project aims to answer:

* Do conflicts affect global commodity prices?
* Is inflation directly influenced by war events?
* Which regions and countries are most affected by conflicts?
* Are modern conflicts different in nature compared to the past?

---

## Dataset Description

The dataset is a combination of:

* Conflict data (UCDP datasets)
* Commodity prices (gold, crude oil, wheat, sugar)
* Inflation data

### Key Features

* `year`
* `location`
* `conflict_count`
* `intensity_level`
* `type_of_conflict`
* `gold_price`
* `crude_oil_price`
* `wheat_price`
* `sugar_price`
* `inflation rate`

---

## Data Cleaning and Preparation

* Removed columns with high missing values
* Standardized date formats and converted to year level
* Handled categorical variables (location cleaning)
* Removed duplicate and irrelevant columns
* Created aggregated features such as `conflict_count`

---

## Exploratory Data Analysis

### 1. Conflict Trends Over Time

* Conflicts have increased steadily since the 1970s
* Peaks observed around the 1990s and post-2010

### 2. Top Conflict Countries

* Conflicts are concentrated in specific regions
* Countries like Myanmar, India, and Ethiopia show repeated conflict activity

### 3. Type of Conflict

* Most conflicts are internal rather than between nations
* Indicates a shift toward civil and regional instability

### 4. Commodity Price Analysis

* Gold prices show clear spikes during major war events
* Oil prices are affected, but inconsistently depending on region
* Wheat and other commodities follow broader economic trends

### 5. Distribution Analysis

* Commodity prices show skewed distributions with outliers
* Gold and oil exhibit strong upward trends over time


### 6. Correlation Analysis

* Strong correlation between commodities (oil, wheat, gold)
* Weak correlation between conflict variables and inflation
* Suggests indirect impact rather than direct causation

---

## Key Insights

* Conflicts are not randomly distributed; they are geographically concentrated
* Modern conflicts are primarily internal (civil conflicts)
* Gold acts as a safe-haven asset during times of war
* Oil prices are influenced by conflict location (especially Middle East)
* Inflation is not directly driven by conflicts
* Economic impact of war is indirect and occurs through commodity channels

---

## Conclusion

The analysis shows that while wars do impact economic indicators, the relationship is complex and indirect. Commodities like gold and oil react more visibly to conflicts, whereas inflation depends on broader macroeconomic factors.

This highlights the importance of understanding indirect economic pathways rather than assuming direct cause-effect relationships.

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Future Improvements

* Incorporate GDP and population data for deeper insights
* Perform country-specific analysis instead of global aggregation
* Build a composite "Crisis Index"
* Extend analysis with time-series modeling

---

## Author

Ayan Mansuri

---

## Note

This project focuses on analytical insights rather than predictive modeling. The objective is to understand patterns and relationships in real-world data.
