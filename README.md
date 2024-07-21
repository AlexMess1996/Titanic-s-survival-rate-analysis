# Titanic Survival Analysis

## Project Overview

This project explores the survival rates of passengers on the Titanic based on key variables such as gender, age, socio-economic status (ticket class), and fare. The analysis employs statistical methods and visualizations to uncover patterns and relationships among these variables.

## Motivation

The tragic sinking of the Titanic is a well-documented historical event. By analyzing the survival data, we aim to gain insights into the factors that influenced passenger survival. This analysis can help in understanding human behavior in crisis situations and can offer lessons for improving emergency response strategies.

## Dataset

The dataset used in this analysis is sourced from Kaggle and contains information about Titanic passengers, including their survival status, gender, age, ticket class, and fare.

## Methodology

### Data Preprocessing

- Survival status is categorized as 1 (survived) and 0 (did not survive).
- Gender is encoded as 0 (female) and 1 (male).
- Passenger class (Pclass) is categorized into three classes: 1 (high class), 2 (middle class), and 3 (low class).
- Age is represented as a continuous variable and grouped into categories (child, teen, adult, senior) for certain analyses.
- Fare is used to distinguish between "rich" and "poor" passengers.

### Statistical Methods

- **Chi-Squared Tests**: Used to test the independence of survival from categorical variables (gender, age group, ticket class).
- **Kaplan-Meier Survival Curves**: Used to visualize survival probabilities across different groups.
- **Logistic Regression**: Used to model the probability of survival based on key variables.

### Visualizations

- Bar graphs for survival rates by gender, age group, and ticket class.
- Scatter plots for survival status by age and fare.
- Kaplan-Meier survival curves for gender vs. age and rich vs. poor.

## Results

### Key Findings

- **Gender**: Females had a higher survival rate compared to males.
- **Age**: Younger passengers, particularly children, had higher survival rates.
- **Socio-Economic Status**: Higher class passengers had better survival rates, indicating a socio-economic divide.
- **Fare**: Higher fare correlated with better survival chances.

### Statistical Analysis

- Chi-squared tests showed significant associations between survival and the variables gender, age group, and ticket class.
- Logistic regression identified gender, age, and socio-economic status as key predictors of survival.

## Conclusion

The analysis reveals that survival on the Titanic was significantly influenced by gender, age, and socio-economic status. Women, children, and passengers from higher classes had better survival chances, reflecting the 'women and children first' policy and the socio-economic disparities of the time. These findings highlight the importance of equitable treatment and access to resources in emergency situations.

## Repository Structure

- `Titanic_analysis.ipynb`: Jupyter notebook containing the analysis.
- `data/`: Directory containing the Titanic dataset.
- `results/`: Directory containing the analysis results and visualizations.

## References

- Heptapod. (2017). Titanic Dataset [Data set]. Kaggle. [Link](https://www.kaggle.com/datasets/heptapod/titanic)
- "Titanic Timeline and Facts." Britannica. [Link](https://www.britannica.com/story/titanic-timeline-and-facts)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
