# Customer Segmentation Project

## Table of Contents
1. [Project Title: Customer Segmentation](#project-title-customer-segmentation)
2. [Significance](#significance)
3. [Expected Outcomes](#expected-outcomes)
4. [Lessons Learned](#lessons-learned)
5. [Project Objectives](#project-objectives)
6. [Techniques and Tools](#techniques-and-tools)
    1. [Data Loading, Cleaning, and Processing](#data-loading-cleaning-and-processing)
    2. [Dimensional Reduction](#dimensional-reduction)
    3. [K-Means Clustering for Segmentation](#k-means-clustering-for-segmentation)
7. [Observations](#observations)
8. [Conclusion](#conclusion)

### 1. Project Title: Customer Segmentation

### 2. Significance
- Customer segmentation is a vital marketing strategy.
- It enhances customer service, identifies new opportunities, and engages with various customer groups effectively.
- This project explores customer segmentation, understands unique customer needs, and divides them into groups based on similarities found in their profiles.

### 3. Expected Outcomes
- Gain a deeper understanding of customers.
- Cater to individual needs and improve marketing strategies and customer support.
- Conduct in-depth Exploratory Data Analysis (EDA) on a dataset with 2240 data points and 29 attributes.
- Categorize attributes into four segments: Customer Information, Products, Place, and Promotion.

### 4. Lessons Learned
- Encode categorical features into numerical formats.
- Conduct feature engineering, such as creating a "Live_With" column.
- Understand the dataset better for informed decisions in market research.

### 5. Project Objectives
- Perform customer segmentation using unsupervised clustering on the firm's customer dataset.
- Divide customers into groups based on age, gender, interests, and spending habits.
- Create user profiles and divide customers into segments reflecting their behavior and attributes.

### 6. Techniques and Tools
- Python for data loading, cleaning, processing, dimensional reduction, K-means clustering, and data profiling.
- Python libraries: numpy, seaborn, scikit-learn, matplotlib, and pandas.

#### 6.1. Data Loading, Cleaning, and Processing
- Handle missing values and outliers.
- Convert date formats to DateTime.
- Add new attributes.
- Label encode categorical variables.
- Conduct Exploratory Data Analysis (EDA) to visualize relationships between variables.

#### 6.2. Dimensional Reduction
- Use Principal Component Analysis (PCA) to reduce dataset dimensionality.
- Preserve the original data's distribution while simplifying the analysis.

#### 6.3. K-Means Clustering for Segmentation
- Apply K-means clustering to the data after PCA.
- Determine the optimal number of clusters using the Elbow method.
- Create four clusters, dividing customers based on income and spending habits.

### 7. Observations
- Four customer groups identified based on income and spending.
- Groups categorized as very low spending and income, very high spending and income, high spending and income, and low spending and income.
- Differences in promotions accepted, deals purchased, and campaign acceptance rates among these groups.
- Majority of customers are relatively young parents with small to medium-sized families.

### 8. Conclusion
- Project successfully achieves customer segmentation objectives.
- Provides insights into customer spending behavior, income, and demographics.
- Recommendations made for the marketing department and CEO to tailor promotions and focus on specific customer segments.
