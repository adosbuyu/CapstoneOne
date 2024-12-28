**Analysis of Cereal Ratings Based on Nutritional Content**

**Introduction**

Cereal is a staple breakfast choice for people worldwide, with ratings influenced by nutritional content, marketing strategies, and brand reputation. This project analyzes the relationships between nutritional attributes (e.g., sugar, fiber, protein, calories) and cereal ratings using a dataset sourced from CMU's StatLib Archive.

This study explores five key hypotheses:

1. Healthier cereals (low in sugar and high in fiber) receive higher ratings.

2. Cereals marketed to children have higher sugar content and lower ratings.

3. Cereals with higher protein content receive higher ratings.

4. Cereals with high calorie counts are less popular.

5. Brand/manufacturer correlates with the nutritional content of cereals.

**Dataset**
The dataset includes nutritional and rating information for various cereals. Key columns include:

name, mfr (manufacturer), type

Nutritional attributes: calories, protein, fat, sodium, fiber, carbohydrates, sugars, potassium, vitamins

Additional attributes: shelf (store shelf placement), weight, cups

Target variable: rating

The full dataset can be found here.

**Project Objectives**

Analyze how nutritional attributes affect cereal ratings.

Test and validate the hypotheses listed above.

Generate actionable insights for manufacturers to optimize product formulations.

**Technologies Used**

Programming Languages: Python, R


**Libraries:**

Python: Pandas, NumPy, Matplotlib, Seaborn

R: ggplot2, dplyr

Visualization Tools: Matplotlib, Seaborn, ggplot2

Data Source: 1993 Expo Dataset

**Methodology**
1. Data Collection and Cleaning
Data was sourced from CMU’s StatLib archive.
Missing and inconsistent data were handled to ensure reliability.

2. Hypothesis Testing
Each hypothesis was tested using statistical methods and data visualizations:
Scatterplots, box plots, and histograms.
Correlation analysis for trends between nutritional attributes and ratings.

3. Visualization and Insights
Created visualizations to represent relationships between variables (e.g., sugar vs. rating).
Generated dashboards for easy interpretation of findings.

**Key Findings**

Hypothesis 1: Healthier cereals (low sugar, high fiber) have higher ratings.

Finding: Low-sugar cereals with high fiber content received significantly higher ratings. However, a balance of moderate fiber and low sugar often resulted in the highest ratings.

Hypothesis 2: Cereals marketed to children have higher sugar content and lower ratings.

Finding: Children’s cereals had a median sugar content of ~8g and lower median ratings (~40), compared to healthier cereals with a median sugar content of ~1g and ratings around 60.

Hypothesis 3: Higher protein content correlates with higher ratings.

Finding: Cereals with 4-6g of protein had ratings consistently above 60, supporting a strong positive correlation.

Hypothesis 4: High calorie counts result in lower ratings.

Finding: No strong correlation was found between calorie counts and ratings, as ratings were evenly distributed across all calorie levels.

Hypothesis 5: Brand correlates with nutritional content.

Finding: Clear differences in nutritional content were observed across manufacturers, supporting a correlation between brand positioning and product formulations.

**Visualizations**

The project includes visualizations such as:

Scatterplots: Relationships between sugar, fiber, protein, and ratings.

Box Plots: Sugar content and ratings by cereal type (children's vs. healthy).

Heatmaps: Correlations between all nutritional attributes and ratings.

Sample visualizations are available in the project repository.

**Conclusion**

The analysis confirms that:

Healthier cereals receive higher ratings.

Children's cereals are typically higher in sugar and receive lower ratings.

Higher protein content is associated with better ratings.

Calorie count has no significant impact on ratings.

Nutritional content varies by manufacturer, reflecting brand strategies.

**Future Work**

Analyze trends in cereal ratings over time.

Study the impact of additional nutritional factors (e.g., vitamins, minerals).

Investigate how demographics influence cereal preferences and ratings.
