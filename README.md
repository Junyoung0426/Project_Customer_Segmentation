# Customer Segmentation Project

## Project Title: Customer Segmentation

### Significance
- Customer segmentation is a vital marketing strategy.
- It enhances customer service, identifies new opportunities, and engages with various customer groups effectively.
- This project explores customer segmentation, understands unique customer needs, and divides them into groups based on similarities found in their profiles.

### Expected Outcomes
- Gain a deeper understanding of customers.
- Cater to individual needs and improve marketing strategies and customer support.
- Conduct in-depth Exploratory Data Analysis (EDA) on a dataset with 2240 data points and 29 attributes.
- Categorize attributes into four segments: Customer Information, Products, Place, and Promotion.

### Lessons Learned
- Encode categorical features into numerical formats.
- Conduct feature engineering, such as creating a "Live_With" column.
- Understand the dataset better for informed decisions in market research.

### Project Objectives
- Perform customer segmentation using unsupervised clustering on the firm's customer dataset.
- Divide customers into groups based on age, gender, interests, and spending habits.
- Create user profiles and divide customers into segments reflecting their behavior and attributes.

### Techniques and Tools
- Python for data loading, cleaning, processing, dimensional reduction, K-means clustering, and data profiling.
- Python libraries: numpy, seaborn, scikit-learn, matplotlib, and pandas.

#### Data Loading, Cleaning, and Processing
- Handle missing values and outliers.
- Convert date formats to DateTime.
- Add new attributes.
- Label encode categorical variables.
- Conduct Exploratory Data Analysis (EDA) to visualize relationships between variables.

#### Dimensional Reduction
- Use Principal Component Analysis (PCA) to reduce dataset dimensionality.
- Preserve the original data's distribution while simplifying the analysis.

#### K-Means Clustering for Segmentation
- Apply K-means clustering to the data after PCA.
- Determine the optimal number of clusters using the Elbow method.
- Create four clusters, dividing customers based on income and spending habits.

### Observations
- Four customer groups identified based on income and spending.
- Groups categorized as very low spending and income, very high spending and income, high spending and income, and low spending and income.
- Differences in promotions accepted, deals purchased, and campaign acceptance rates among these groups.
- Majority of customers are relatively young parents with small to medium-sized families.

### Conclusion
- Project successfully achieves customer segmentation objectives.
- Provides insights into customer spending behavior, income, and demographics.
- Recommendations made for the marketing department and CEO to tailor promotions and focus on specific customer segments.
