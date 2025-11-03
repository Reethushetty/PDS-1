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

**V1: Gender split for Math vs Reading (boxplots)**

From the box plots, the performance of male and female students is indicated in terms of mathematics and reading scores. It is noticeable that the performance of female students is slightly higher in reading, with a small lead in mathematics scores by male students. It is noticeable that there is some overlapping of scores in the performance of the two groups of students, indicating that performance is not sharply divided. By looking at the data, there are some scores that act as outliers in the performance of this group of students.

**V2: Effect of test prep on Math scores (boxplots)**

It is evident from the box plots that the students who had test preparation scored higher in math. It is observed that the median of the scores of prepared students is higher than those of the students who did not get any preparation. Prepared students lack student scores that fall in the range of the lowest values. It is observed that the students who did not receive any preparation had scores spread across a wide range of values.

**V3: Lunch type vs average score (bar chart)**

A bar chart shows the performance of students depending on lunch offered. Standard lunch students’ performance is higher than that of free/reduced lunch students. This data implies that economic influences could be affecting student performance. Performance is equal across subjects. Free/reduced lunch students could be getting less support, hence having lower scores. Standard lunch students perform better in academics.

**V4: Math, Reading, Writing correlation (heatmap)**

From the heatmap, there appear to be positive correlations between math, reading, and writing skills. It is evident that reading skills are the most correlated with writing skills, indicating that students who perform well in one subject, particularly reading, are likely to perform well in writing as well. Math skills appear to be well correlated with both reading and writing skills, indicating that students who perform well in math are likely to perform well in both reading and writing as well. It is evident that the heatmap suggests that skills in one subject can help in improving performance in other subjects as well.

**V5: Math vs Reading by test prep (scatter with trend lines)**

There is a positive correlation between math scores and reading scores in the scatterplot. Students that received test preparation scored higher in math as well as reading, and are grouped closely together. Students who did not receive test preparation scored lower in a more scattered pattern. It is apparent that higher scores are attained when test preparation is done, which is characterized by the trendlines indicating that higher scores are attained. Math scores as well as reading scores are closely linked, with test preparation making a significant impact.


All plots exported as PNGs in the Result folder. From observations, it is seen that performance is influenced by gender, test prep, and lunch type, and subjects are highly correlated.
