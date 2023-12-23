# Blood-Transfusion
In this analysis of a blood transfusion dataset from a mobile blood donation vehicle in Taiwan, we performed the following steps:

1. **Data Inspection:**
   - Explored the dataset structure and information.
   - Checked for null values (none found).
   - Renamed the target column for clarity.

2. **Target Incidence Analysis:**
   - Examined the distribution of the target variable.
   - Found that the dataset is imbalanced, with 76% of instances having a target value of 0 and 23% having a target value of 1.

3. **Statistical Information:**
   - Computed descriptive statistics for each feature, including count, mean, standard deviation, minimum, 25th percentile, median, 75th percentile, and maximum.

4. **Skewness Analysis:**
   - Investigated skewness for each feature.
   - Identified positive skewness in several features, indicating non-normal distributions.

5. **Distribution Visualization:**
   - Plotted Probability Density Function (PDF) and Quantile-Quantile (QQ) plots for each feature to visualize their distributions.
   - Generated histograms for an overall view of feature distributions.

6. **Data Splitting and Scaling:**
   - Split the data into training and testing sets, maintaining the target incidence ratio.
   - Applied Standard Scaling to normalize the features.

7. **Model Selection using TPOT:**
   - Utilized TPOT, an automated machine learning tool, to identify an optimal classification model.
   - Achieved an accuracy score of 0.81 on the test set.

8. **Decision Tree Model:**
   - Implemented a Decision Tree Classifier with specified parameters.
   - Evaluated the model's performance using classification reports and accuracy scores on both training and testing sets.

9. **Conclusion:**
   - Recognized the significance of accurate blood supply forecasts for timely intervention and saving lives.
   - Highlighted the benefits of using interpretable models like Decision Trees for analysis.

In summary, the analysis provided insights into the dataset, addressed imbalanced target incidence, explored statistical characteristics, and employed automated and manual model selection techniques. The Decision Tree model demonstrated reasonable accuracy and interpretability, contributing to the understanding of blood donation patterns.
