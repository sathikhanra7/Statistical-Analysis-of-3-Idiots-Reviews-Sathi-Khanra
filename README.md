
# Statistical Analysis of Audience Reviews of 3 Idiots

## Project Overview

This project presents a comprehensive statistical analysis of audience reviews for the Bollywood film *3 Idiots*. Using IMDb review data, the study applies descriptive statistics, sentiment analysis, and data visualization techniques to understand audience behavior, satisfaction levels, and rating patterns.

The objective is to transform raw audience reviews into meaningful insights through quantitative analysis and graphical interpretation.


## Objectives

- Analyze audience rating behavior using descriptive statistics.
- Measure central tendency using Mean, Median, and Mode.
- Evaluate rating variability through Range, Variance, and Standard Deviation.
- Study distribution characteristics using Skewness and Kurtosis.
- Perform sentiment classification based on rating intervals.
- Visualize audience perception using professional charts and graphs.
- Interpret audience behavior from a data analytics perspective.

---

## Dataset Information

**Source:** IMDb Audience Reviews

| Attribute | Description |
|------------|-------------|
| Username | Reviewer identifier |
| Rating | Numerical rating (1–10) |
| Review Title | Short review headline |
| Review Text | Complete audience review |

After preprocessing and cleaning, **1,043 valid reviews** were retained for analysis.

---

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Converted ratings to numeric format
- Removed missing values
- Eliminated duplicate reviews
- Validated rating scale boundaries
- Standardized review text
- Reset dataset indexing

---

## Statistical Measures Analyzed

### Central Tendency
- Mean
- Median
- Mode

### Dispersion Measures
- Range
- Variance
- Standard Deviation

### Distribution Characteristics
- Skewness
- Kurtosis

---

## Sentiment Analysis

Reviews were categorized into sentiment groups using rating values:

| Rating Range | Sentiment |
|-------------|-----------|
| 8–10 | Positive |
| 5–7 | Neutral |
| 1–4 | Negative |

---

## Key Findings

- Mean Rating: **8.67**
- Median Rating: **9**
- Mode Rating: **10**
- Standard Deviation: **2.07**
- Skewness: **-2.20**
- Kurtosis: **4.72**
- Majority of ratings fall within the **9–10** interval.

The analysis indicates strong audience satisfaction and a highly positive reception toward *3 Idiots*.

---

## Visualizations

The project includes:

- Histogram
- Central Tendency Comparison Plot
- Frequency Distribution Chart
- Pie Chart for Sentiment Composition
- Box Plot
- Density Plot
- Skewness Distribution Plot
- Word Cloud

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- WordCloud
- Jupyter Notebook

---

## Repository Structure

Statistical-Analysis-of-3-Idiots-Reviews-Sathi-Khanra/
│
├── Descriptive_Statistical_Analysis_of_Audience_Reviews.ipynb
├── 3_idiots_reviews.csv
├── presentation/
│   ├── Statistical_Analysis_3_Idiots.pdf
│   └── Statistical_Analysis_3_Idiots.pptx
├── images/
├── README.md



## Conclusion

The findings demonstrate that *3 Idiots* received overwhelmingly positive audience feedback. Statistical indicators and visual evidence reveal strong viewer satisfaction, high consensus, and sustained audience appreciation. This project highlights how data analytics can be applied to entertainment datasets to uncover meaningful behavioral insights.

---

## Author

**Sathi Khanra**  
B.Sc. Computer Science (AI & Machine Learning)


```
