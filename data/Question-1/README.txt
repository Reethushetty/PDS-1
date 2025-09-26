Grip Strength and Frailty Study – Female Participants
Data Information

Data include hand grip strength from dynamometer and participant characteristic data.

Variables

Height: Participant height in inches

Weight: Participant weight in pounds

Age: Participant age in years

Grip Strength: Hand grip strength in kilograms

Frailty: Qualitative measurement of frailty (Y = frail, N = not frail)

Study Overview

This study explores the relationship between grip strength and frailty among female participants. Exploratory data analysis (EDA), visualization, and predictive modeling are applied within this research to identify frailty determinants.

Exploratory Data Analysis (EDA)
Summary Statistics

Summary statistics of all numerical variables (mean, standard deviation, and distribution) were calculated to identify participant information.

Correlation Analysis

A correlation matrix was calculated in order to verify correlations between numerical variables. Key findings

Grip Strength and Frailty: Increased grip strength corresponds to reduced frailty scores.

Age and Grip Strength: Female grip strength decreases with age.

Visualizations

Correlation Heatmap: Displays strength of numeric variable relationships.

Scatter Plot: Plots age vs. grip strength, and displays frailty status as color.

Box Plot: Compares non-frail vs. frail group grip strength, and indicates frail participants have weaker grip strength.

Predictive Modeling – Logistic Regression
Model Overview

Logistic regression model was employed for prediction of frailty based on grip strength and age.

Model Evaluation

Accuracy: 80% on test set, indicating good fit of prediction.

Confusion Matrix: Provides true positives, true negatives, false positives, and false negatives.

Classification Report: Provides precision, recall, and F1-score for frail and non-frail classes:

Frail Class Precision: 67% (ratio of frail cases correctly predicted)

Frail Class Recall: 100% (ratio of actual frail cases correctly predicted)
Overview

Dataset
- The dataset `raw_data.csv` contains measurements for 10 female participants:
  - Height (inches)
  - Weight (pounds)
  - Age (years)
  - Grip strength (kg)
  - Frailty (Y/N)

Workflow

1. Ingest
- The raw CSV file is read into a pandas DataFrame.
- Column names are cleaned for consistency.

2. Process
- Unit conversion: Height → meters, Weight → kilograms.
- Feature engineering:
  - BMI calculation
  - Age categorization into groups: <30, 30–45,46–60,>60
  - Encoding categorical variables**:
  - Frailty → binary (0 = N, 1 = Y)
  - AgeGroup → one-hot encoding

3. Analyze
- Summary statistics: mean, median, standard deviation of numeric columns.
- Correlation: Grip strength vs Frailty.
- Visualization:
  - BMI distribution
  - Grip strength vs Frailty (boxplot)
  - AgeGroup distribution (countplot)
  - Correlation heatmap

 Files & Folders

data/raw_data.csv` → Original dataset
processed_data.csv → Dataset after processing (unit conversion, BMI, encoding)
reports/summary_statistics.csv → Summary statistics of numeric features
results/
→ Folder containing all generated plots:
  - BMI_distribution.png
  - Grip_vs_Frailty.png
  - AgeGroup_counts.png
  - correlation_heatmap.png

How to Run

1. Upload raw_data.csv when prompted.
2. Run all cells to generate:
   - Processed dataset
   - Summary statistics
   

