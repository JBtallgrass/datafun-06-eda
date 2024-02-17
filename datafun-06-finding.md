# Wine Quality Analysis

## Introduction

Hello! My name is Jason Ballard, and I'm passionate about data science and oenology—the science of wine and winemaking. Today, I will be sharing insights from an exploratory data analysis of a dataset that includes physicochemical properties and quality ratings of red and white variants of the Portuguese "Vinho Verde" wine. The project objective is to uncover patterns and relationships that might influence wine quality resulting in determining marketability.

## Dataset Overview

The dataset consists of several physicochemical properties of wines, such as acidity, sugar content, alcohol level, and a quality rating from 0 to 10. The project aims to present how these properties correlate with the wine's quality and what factors are most indicative of a high-quality wine.

![Dataset preview](https://github.com/JBtallgrass/datafun-06-eda/blob/main/figures/dataset.png)

## Subsection 1: Distribution of Wine Quality

### Goal

The first exploration seeks to understand the distribution of wine quality scores across the dataset.

### Chart: Distribution of Wine Quality

![Distribution of Wine Quality](https://github.com/JBtallgrass/datafun-06-eda/blob/main/figures/Distribution%20of%20Wine%20Quality%20Scores.png)

### Story 

The histogram reveals that the majority of wines have a quality score around 5 to 6, indicating a moderate quality. There are fewer wines with very high or very low quality scores, suggesting that extreme qualities are less common in this dataset.

## Subsection 2: Relationship Between Alcohol Content and Wine Quality

### Goal

Investigate if there's a noticeable relationship between the alcohol content of the wine and its quality score.

### Chart: Alcohol Content and Wine Quality

![Alcohol and Wine Quality](https://github.com/JBtallgrass/datafun-06-eda/blob/main/figures/Alcohol%20Content%20vs.%20Wine%20Quality.png)

### Story

The scatter plot suggests a positive correlation between alcohol content and wine quality. Higher-quality wines tend to have higher alcohol percentages. This trend might indicate that a certain level of alcohol content contributes positively to the perceived quality of wine.

## Subsection 3: Average Sulphates Content Across Different Quality Categories

### Goal

Compare the average sulphates content across wines of different quality categories to see if sulphates play a role in quality differentiation.

### Chart: Sulphates impacts on Wine quality

![Sulphates between Wine quality](https://github.com/JBtallgrass/datafun-06-eda/blob/main/figures/Average%20Sulphates%20Content%20by%20Wine%20Quality%20Category.png)

### Story

The bar chart indicates that higher quality wines tend to have a slightly higher average sulphates content. Sulphates, which are used as preservatives, might not only contribute to the longevity of wine but also to its taste and, consequently, its quality rating.

## Subsection 4: Impact of Acidity on Wine Quality

### Goal

Explore how different levels of acidity (fixed acidity, volatile acidity, and citric acid) impact wine quality.

### Chart: Impact of Acidity on Wine Quality

![Impact of Acidity on Wine Quality](https://github.com/JBtallgrass/datafun-06-eda/blob/main/figures/Impact_of_Acidity_on_Wine_Quality.png)

### Story

The pair plot shows varied relationships between the types of acidity and wine quality. While some acidity types seem to have a more direct correlation with quality, others do not show a clear trend. This complexity underscores the nuanced role that acidity plays in wine taste and quality perception.

## Conclusion

Through our exploratory analysis, we've discovered several key factors that correlate with wine quality, including alcohol content, sulphates, and acidity levels. These findings suggest that a delicate balance of physicochemical properties contributes to the overall quality of wine, highlighting the art and science behind winemaking.

Thank you for joining me on this data-driven journey into the world of wine. Cheers to uncovering more insights in the future!v
