# Final Project Report STAT 201 Group 4
## Gender Proportion Inference of Suicide Attempts Across Primary Education Level in Shandong, China

## Introduction
In recent years, suicide has become a worldwide public health concern, with significant consequences for individuals and communities. Understanding the factors influencing suicide attempts is crucial for effective prevention. In this project, we investigate the effect of gender on suicide risk among individuals with primary education in Shandong, China.

## Research Question
Is there a difference between the proportions of suicide rates of women and men with primary education level?

## Dataset
We utilized the "Suicide Attempts in Shandong, China" dataset from Kaggle, which records information on suicide victims from 2009 to 2011. The dataset contains 2571 rows and 12 columns, including variables such as sex, education level, and method of suicide.

### Methods and Results
#### Reading Our Dataset
We imported necessary libraries and read the dataset into R.

#### Cleaning and Wrangling Data
We identified and handled missing values and filtered the dataset to include only relevant columns and primary education level.

#### Visualizing the Data
We visualized the number of suicide attempts across different education levels and genders.

#### Computing Estimates
We calculated the proportions of suicide attempts for males and females with primary education.

#### Hypothesis Testing
- We performed a two-sample z-test and obtained a p-value of 0.00658, indicating a significant difference in suicide rates.
- Bootstrapping analysis also supported this finding with a p-value of 0.011.

#### Confidence Intervals
- We computed a 95% confidence interval using asymptotic and simulation-based methods, both yielding similar results.

#### Discussion
- We discussed the implications of our findings, limitations of the study, and future research questions.
- Our results suggest a significant difference in suicide rates between genders with primary education in Shandong, China.

## References
- Heather Saunders and Nirmita Panchal. (2023). [A look at the latest suicide data and change over the last decade](https://www.kff.org/mental-health/issue-brief/a-look-at-the-latest-suicide-data-and-change-over-the-last-decade/).
- Phillips, J. A., & Hempstead, K. (2017). [Differences in U.S. suicide rates by educational attainment, 2000–2014](https://doi.org/10.1016/j.amepre.2017.04.010).
- Scholaro Database. (2023). [Education system in China](https://www.scholaro.com/db/Countries/China/Education-System).
- Singh, U. (2023). [Suicide attempts in Shandong, China](https://www.kaggle.com/datasets/utkarshx27/suicide-attempts-in-shandong-china).

---
*This project was conducted as part of a collaborative effort by Group 4.*
