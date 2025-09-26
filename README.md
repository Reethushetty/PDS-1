**Question-1**
Grip Strength and Frailty Study – Female Participants
Data Information
Data include hand grip strength from dynamometer and participant characteristic data.

**Variables**

Height: Participant height in inches
Weight: Participant weight in pounds
Age: Participant age in years
Grip Strength: Hand grip strength in kilograms
Frailty: Qualitative measurement of frailty (Y = frail, N = not frail)

**Study Overview**

This study explores the relationship between grip strength and frailty among female participants. Exploratory data analysis (EDA), visualization, and predictive modeling are applied within this research to identify frailty determinants.
Exploratory Data Analysis (EDA)
Summary Statistics
Summary statistics of all numerical variables (mean, standard deviation, and distribution) were calculated to identify participant information.

**Correlation Analysis**

A correlation matrix was calculated in order to verify correlations between numerical variables. Key findings
Grip Strength and Frailty: Increased grip strength corresponds to reduced frailty scores.
Age and Grip Strength: Female grip strength decreases with age.

**Visualizations**

Correlation Heatmap: Displays strength of numeric variable relationships.

Scatter Plot: Plots age vs. grip strength, and displays frailty status as color.

Box Plot: Compares non-frail vs. frail group grip strength, and indicates frail participants have weaker grip strength.

**Model Evaluation**

Accuracy: 80% on test set, indicating good fit of prediction.

Confusion Matrix: Provides true positives, true negatives, false positives, and false negatives.

Classification Report: Provides precision, recall, and F1-score for frail and non-frail classes:

Frail Class Precision: 67% (ratio of frail cases correctly predicted)

Frail Class Recall: 100% (ratio of actual frail cases correctly predicted)


**Question-2**
Student Performance Analysis

The project compares student performance in Math, Reading, and Writing with demographic variables such as gender, lunch type, and test preparation.

**Data Cleaning:**

Renamed column names to standard names and normalized scores to numeric type.

Filled missing values with group median and overall median.

Cleaned dataset saved as StudentsPerformance_cleaned.csv.

**Visualizations:**

V1: Gender split for Math vs Reading (boxplots)

V2: Effect of test prep on Math scores (boxplots)

V3: Lunch type vs average score (bar chart)

V4: Math, Reading, Writing correlation (heatmap)

V5: Math vs Reading by test prep (scatter with trend lines)

All plots exported as PNGs in the Result folder. From observations, it is seen that performance is influenced by gender, test prep, and lunch type, and subjects are highly correlated.
