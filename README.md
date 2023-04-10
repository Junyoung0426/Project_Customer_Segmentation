# Customer_Segmentation

## Title of the project: Customer Segmentation

## Significance: 
  “Here’s a great deal I picked for you.” I all have experienced receiving this kind
of notification from any kind of market places’ notifications. How come they know what other
groups of ages need? From this, our group has realized that most of the market places use customer
segmentation to improve customer service, find new opportunities to support effectively, and
interact with segments of customers using favored platforms. Thus, I think doing this project
itself is interesting for us since I can learn about customer segmentation by understanding the
particular issues experienced by each group as I develop user profiles and dividing the customers
based on similarities found in the profiles.

## Expected outcomes: 
  I will strive to learn about customers on a deeper level so I can satisfy
their unique needs and standards. In order to meet their criteria, the primary goal is to perform a
thorough EDA(Exploratory Data Analysis) on the dataset that consists of 2240 data points and 29
attributes. Then, I can further categorize these attributes in 4 segments, including Customer’s
Information, products, place, and promotion, so that I can observe clearer data. The ultimate goal
is to make a more convenient approach to marketing strategies and improve customer service and
customer support efforts. To do so, I will dive into analyzing several promotions outlined in the
dataset and understand the effect of these promotions on customers. Because the dataset includes
lots of features, I will need to perform several techniques that will be illustrated in the next
section.

## Lessons learned:
  Up to this point, I realized that there are some categorical features in our dataset
that show data types as object, for which I will need to encode them into numerical forms later
before performing the modeling process. Additionally, I will need to conduct feature engineering
in several attributes. For example, Marital_Status column displays a total of 8 categories, such as
Married, Together, Single, Divorced, Widow, Alone, Absurd, and YOLO. For the sake of simplicity,
I can create another column Live_With to extract the living situation of these sub-categories. I
learned that there are some other categorical features that need to be engineered so that I can more
clearly understand the dataset before taking further steps. Then, I will be able to make better
problem-solving decisions out of this dataset and make progress into market research.


## The project objectives
  The project aims to perform customer segmentation on the customer’s dataset of the firm by using unsupervised clustering of the data. Customer Segmentation is the practice of separating customers into groups of customers that reflect similarities relevant to attributes, such as age, gender, interest, and spending habits. Our group has realized that most of the marketplaces use customer segmentation to improve customer service, find new opportunities to support effectively, and interact with segments of customers using favored platforms. Thus, I think doing this project itself is interesting for us since I can learn about customer segmentation by understanding the particular issues experienced by each group as I develop user profiles and dividing the customers based on similarities found in the profiles. In this project, I will divide customers into several groups with different behavioral patterns in spending habits in terms of many attributes shown in the dataset. 
Through this project, I strived to learn about customers on a deeper level so I can satisfy their unique needs and standards. In order to meet their criteria, the primary goal is to perform a thorough analysis of the dataset that consists of 2240 data points and 29 attributes. Then, I can further categorize these attributes into four subsets, including Customer Information, products, place, and promotion, so I could observe clearer data. Because our main objective is to make a more convenient approach to marketing strategies and improve customer service and support efforts, I decided to dive into analyzing several promotions and campaigns outlined in the dataset and understand the effect of these promotions on customers by providing several recommendations to the marketing department. 

## Techniques and Tools
For this project, I utilize python for loading data, data cleaning, data processing, dimensional reduction, k-means clustering, and data profiling. In python, I used some modules, packages and, libraries such as numpy, seaborn, sklearn, matplotlib and, pandas.

### Data Loading, Cleaning, and Processing
After loading the customer segmentation data (marketing_campaign.csv), I remove the missing value (NA) and outlier, change the date formulas of data (ex. 12-07-2022) to the DateTime, add the new attributes, and change the categorical variable to numerical by using label encoding. To see the relationship betIen each variable, I made a scatter matrix with some features and a correlation matrix heat map by importing seaborn. After that, I focused on the campaign attributes (AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp3, AcceptedCmp5, AcceptedCmp6) and analyze the relation with other features.

### Dimensional Reduction               
The primary goal is to perform a thorough EDA(Exploratory Data Analysis) on the dataset that consists of 2240 data points and 29 attributes and categorize these attributes into segments. Since there are 29 attributes in our data, it will be hard to analyze the visualization with 29 dimensions that cause some problems such as *curses of dimension and overfitting. Therefore, I performed dimensional reduction techniques by using PCA(Principal component analysis) from the scikit-learn library in Python, which transforms data in high-dimensional space into low-dimensional space while preserving the distribution of original data as much as possible. The first main component PC0 preserves the distribution of original data the most, and the second main component PC1 preserves the distribution of original data the most. To choose the number of dimensions, I drew the scree plot. In the scree plot, the point at which the graph becomes rapidly gentle is determined as the number of principal components, which is three in our case. As a result, I reduced the attributes to three dimensions by using sklearn. 
### K-Means Clustering for Segmentation
  Using the data after the pca, I performed the clustering via K-means clustering. I grouped the samples into clusters such that the within-group sum of square deviation is minimized by from sklearn.cluster import KMeans. Using the Elbow method, I can find the optimal number of clusters from yellowbrick.cluster import KElbowVisualizer. With Elbow method, the point at which the graph becomes rapidly gentle is determined as the number of clusters, which is four in our case. Therefore, with our data, the optimal number of clusters is four, so make four segmentations. 

## Observations 
  After performing K-Means clustering, 4 different groups Ire created in terms of Income and Spent. Because the average income of the customer is 52,248.25, I decided to divide into high and low income groups. Group zero represents very low spending and very low income; Group one represents very high spending and very high income; Group two represents high spending and high income; Group three represents low spending and low income. Based on these four groups, I discovered that Group zero took up the least in possessing the promotion, whereas Group one took up the most in possessing the promotion. In terms of the number of deals purchased, I found out that Group 1 took up the least in having a discount promotion. Moreover, the average acceptance rate for campaign two is around 1.4 %, which is the loIst, and the acceptance rate for campaign four is about 7.5%, which is the highest. Additionally, I performed data profiling of the clustering based on the demographics, then I found out that the majority of customers are relatively young parents with a family size of one to three with one or zero children. Customers in Group one are not definitely parents with family sizes ranging from one to two and categorized as a high income group. Customers in Group two are definitely parents of two to four family sizes with at least one child in the family. Customers in Group three are also a parent of two to five family sizes with one to three children in the family. They are relatively older than other groups in age and categorized as loIr-income groups. Based on the data profiling that I performed, I could give several recommendations to the marketing department and CEO of the firm and believe that this can be used in planning better marketing strategies for the future.

## Conclusion 
  I have accomplished the main objective, which was executing customer segmentation on the customer dataset by applying the company’s unsupervised clustering. Moreover, I conducted a thorough analysis of the dataset that was configured to meet the needs and criteria of the customer and understood the impact of several promotions summarized in the dataset on the customer. Through these processes, I could come up with a conclusion of which customers spent the highest and loIst amount on buying, their income, their segmentation, and much more. Since there are so many data points, I used the Elbow method to find the optimal number of clusters. As a result, four different groups Ire formed through clustering, which was also divided into high-income and low-income groups, indicating the presence of children, their approximate age, and whether they are parents or not. Based on those outcomes, I recommend the marketing department to pay close attention to factors like the customer’s yearly income, the number of children living in each household, and the amount spent on wine because products made of meat and wines are doing Ill in terms of sales growth. Since sales of items that include meat and wine are expanding, it is important for the CEO to look at a set of consumers’ profiles in order to keep these clients and boost sales of other products at the same time. Despite the fact that the majority of customers do not pursue receiving promotions, group 0 had significantly low income and spending. Thus, the department should concentrate more on group 0 by providing more individualized benefits in order to encourage them to pursue receiving more promotions. 


#### #Reference 
Karnikakapoor. (2021, October 8). Customer segmentation: Clustering . Kaggle. Retrieved December 6, 2022
Baker, K. (2022, November 25). Customer segmentation: How to effectively segment users & clients. HubSpot Blog. Retrieved December 6, 2022
Mumuni, S. (2022, June 18). A beginner's guide to customer segmentation with python. Medium. Retrieved December 6, 2022




