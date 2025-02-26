# DA-with-AI-assignment-1
# README - WVS Dataset

## 1. What is this dataset?
This dataset is a subset of the **World Values Survey (WVS)**, which collects global data on people's values, beliefs, and behaviors. It includes variables related to **trust in people (Q57)** and **happiness (Q46)**.

## 2. What is the source of this dataset?
The data comes from **Wave 7 (2017-2022) of the World Values Survey (WVS)**.

## 3. What does each row represent?
Each row represents an **individual survey respondent** from a participating country.

## 4. What does each column represent?
Each column represents a **survey question or demographic variable**. The most relevant variables in this subset include:

- **Q46** - Feeling of Happiness
- **Q57** - General Trust in People
- **Q48** - Freedom of Choice & Control
- **Q49** - Life Satisfaction
- **Q50** - Financial Satisfaction
- **Q52** - Feeling Unsafe from Crime at Home
- **Q58** - Trust in Family
- **Q60** - Trust in People You Know Personally

## 5. What is the relationship between Q57 (Trust in People) and Q46 (Happiness)?
The dataset allows for analyzing whether individuals with **higher trust in people (Q57)** tend to report **higher happiness levels (Q46)**. Factors like **financial satisfaction (Q50)** and **personal security (Q52)** may influence this relationship.

## 6. How was this data collected?
The data was collected through **face-to-face interviews and online surveys** across multiple countries during **2017-2022**.

## 7. Are there any missing values?
Yes, some responses may be missing or marked as **"Don’t know" (-1), "No answer" (-2), or "Not asked" (-4)**.

## 8. How can this dataset be used?
- **Statistical analysis**: Explore correlations between trust and happiness.
- **Comparative studies**: Examine trends across different countries.
- **Regression models**: Identify predictive factors for happiness.

## 9. File format
The dataset is provided as an **Excel (.xlsx) file**.

## 10. Contact
For further details, refer to the **World Values Survey official website**: [www.worldvaluessurvey.org](https://www.worldvaluessurvey.org).

## 1. Key Information on the Dataset
The dataset used is from the World Values Survey (WVS) Wave 7 (2017-2022), which includes responses from individuals across multiple countries on various socio-economic and cultural topics between 2017 and 2022. The survey is designed to provide insights into people's beliefs, values, economic conditions, and overall well-being.

- Source: World Values Survey (www.worldvaluessurvey.org)
- Years Covered: 2017-2022
- File Format: CSV
- Number of Respondents: 97,220
- Survey Method: Face-to-face and online interviews

### 2. Dataset Files
- `WVS_subset.csv` → Contains survey responses.
- `WVS_codebook.pdf` → Provides variable definitions and coding structure.

## Research Question
> How does financial satisfaction impact overall happiness?

To answer this question, we analyze self-reported happiness and financial satisfaction while accounting for additional socio-economic variables that may influence happiness.

### 3. Main Variables
This analysis primarily focuses on Q46 (Happiness) and Q50 (Financial Satisfaction) but includes additional variables for a more comprehensive understanding.

- Q46 - Happiness: Measures subjective happiness (Scale: 1 = Very happy, 4 = Not at all happy).
- Q50 - Financial Satisfaction: Measures financial well-being (Scale: 1 = Completely dissatisfied, 10 = Completely satisfied).

### Additional Control Variables
To improve the accuracy of our analysis, we include variables such as:
- Q49 - Life Satisfaction (1-10 scale)
- Q47 - Subjective Health (1-5 scale)
- Q48 - Freedom of Choice and Control (1-10 scale)
- Q260 - Age (Numeric)
- Q261 - Gender (1 = Male, 2 = Female)
- Q262 - Marital Status (1-5 categories)
- Q263 - Education Level (1-8 scale)
- Q264 - Employment Status (1-6 categories)
- Q265 - Household Income (1-10 scale)

## 4. Descriptive Statistics
To understand the dataset, we computed descriptive statistics for the five most important variables.

| Variable | Count | Mean | Std Dev | Min | 25% | Median | 75% | Max |
|----------|--------|------|---------|-----|-----|--------|-----|-----|
| Q46 - Happiness | 97,220 | 1.83 | 0.78 | -5 | 1 | 2 | 2 | 4 |
| Q50 - Financial Satisfaction | 97,220 | 6.16 | 2.51 | -5 | 5 | 6 | 8 | 10 |
| Q49 - Life Satisfaction | 97,220 | 7.01 | 2.34 | -5 | 6 | 7 | 9 | 10 |
| Q47 - Health Status | 97,220 | 2.18 | 0.92 | -5 | 2 | 2 | 3 | 5 |
| Q48 - Freedom of Choice | 97,220 | 7.13 | 2.41 | -5 | 6 | 7 | 9 | 10 |
