# EDA-Student-Performance
### 1. Introduction

This project performs an Exploratory Data Analysis (EDA) on a dataset of student performance. The analysis aims to uncover insights and trends in student performance based on various attributes such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course completion. Additionally, the project includes hypothesis testing to determine the impact of the test preparation course on student performance.

![image](https://github.com/user-attachments/assets/5437fab9-5e7d-402d-ba48-b58b03985b69)

### 2. Objectives

The primary objectives of this project are:
- To perform data cleaning and preparation.
- To explore the dataset and gain insights into student performance across various attributes.
- To perform univariate, bivariate, and multivariate analyses.
- To perform hypothesis testing to draw significant conclusions.
- To visualize the data to better understand the underlying patterns and trends.

### 3. Dataset Description

The dataset used in this project is `StudentsPerformance.csv`, which contains the following columns:
- `gender`: Sex of students (Male/Female)
- `race/ethnicity`: Ethnicity of students (Group A, B, C, D, E)
- `parental level of education`: Parents' final education (bachelor's degree, some college, etc.)
- `lunch`: Type of lunch (standard or free/reduced)
- `test preparation course`: Whether or not the student completed a test preparation course (none or completed)
- `math score`, `reading score`, `writing score`: Scores of students in different subjects

### 4. Methodology

The project follows a structured approach to explore and analyze the dataset:

#### a. Data Cleaning
- Handling missing values.
- Ensuring consistency in data types.
- Removing duplicates.
- Handling Outliers

#### b. Data Exploration
The data exploration phase involves multiple types of analysis to gain comprehensive insights into the dataset:

##### i. Univariate Analysis
- Analyzing individual columns to understand their distribution and identify any outliers.
- Example: Distribution of `math score`, `reading score`, `writing score`.

##### ii. Bivariate Analysis
- Exploring the relationships between two variables.
- Example: Gender impact on student performance across different subjects etc.

##### iii. Multivariate Analysis
- Examining the interactions between multiple variables.
- Example: Impact of parental education and lunch type on student performance etc.

#### c. Hypothesis Testing
- Performing statistical tests to draw significant conclusions from the data.
  - Example Hypothesis: There is no significant difference in the average scores of students who completed the test preparation course and those who did not.

#### d. Visualization
- Creating visualizations to represent the data insights.
  - Bar plots, pie charts, line graphs, and scatter plots are used to illustrate key findings.

### 5. Insights

Some of the key insights derived from the analysis include:

#### Univariate Analysis
- **Math Scores**: Distribution of math scores shows a slight right skew, indicating most students score above average.
- **Reading Scores**: Distribution of reading scores is more symmetrical, with a slight left skew.
- **Writing Scores**: Distribution of writing scores is similar to reading scores, indicating consistency in language-related subjects.

#### Bivariate Analysis
- **Gender Impact**: Female students generally achieve higher scores in reading and writing compared to male students, while male students have slightly higher average math scores.
- **Race/Ethnicity Impact**: Group E consistently scores the highest across all subjects, while Group A scores the lowest.
- **Lunch Type Impact**: Students receiving standard lunch tend to perform better across all subjects compared to those receiving free/reduced lunch.

#### Multivariate Analysis
- **Parental Education**: Students whose parents have higher education levels tend to perform better across all subjects.
- **Test Preparation Course**: Students who completed the test preparation course score higher on average across all subjects compared to those who did not.

### 6. Hypothesis Testing

#### Example Hypothesis
- **Null Hypothesis (H₀)**: There is no significant difference in the average scores of students who completed the test preparation course and those who did not.
- **Alternative Hypothesis (H₁)**: There is a significant difference in the average scores of students who completed the test preparation course and those who did not.

#### Conclusion
Since the Z-score exceeds the critical Z value and the p-value is less than the significance level, we reject the null hypothesis. This means that there is sufficient evidence to conclude that students who completed the test preparation course have significantly higher average scores compared to those who did not complete the course.

### 7. Conclusion

The project provides valuable insights into the factors influencing student performance. The findings can help educators and policymakers design targeted interventions to improve student outcomes.

### 8. Future Work

Potential areas for future work include:
- Expanding the dataset to include more recent data.
- Analyzing the impact of external factors such as socioeconomic status and school resources on student performance.
- Exploring the relationship between extracurricular activities and academic performance.

## Project Structure

The repository contains the following files:
- `EDA_Student_Performance.ipynb`: Jupyter notebook containing the entire exploratory data analysis.
- `StudentsPerformance.csv`: Dataset file (ensure it is placed in the specified directory).
- `README.md`: Project documentation file.

## Setup Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/your-username/EDA_Student_Performance.git](https://github.com/your-username/EDA_Student_Performance.git](https://github.com/Jayita11/EDA-Student-Exam-Performance)
