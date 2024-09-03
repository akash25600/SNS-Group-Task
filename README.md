# SNS-Group-Task

**part_1**

**1. Data Visualization**
**Importance:**

Simplifies complex data.
Helps identify patterns and trends.
Facilitates quicker insights and better decision-making.
Key Principles:

Clarity: Ensure the visualization is easy to understand.
Simplicity: Avoid clutter.
Accuracy: Represent data correctly.
Consistency: Use uniform visual elements.
Audience: Tailor visuals to the target viewers.
Storytelling: Convey a clear message.
2. Tableau Basics
Main Components:

Data Connection
Worksheet
Dashboard
Story
Filters/Parameters/Actions
Marks
Creating a Basic Dashboard:

Connect to Data.
Prepare Data.
Create Worksheets.
Build a Dashboard.
Add Interactivity.
Format and Finalize.
Publish.
3. Power BI Fundamentals
Main Features:

Data Integration
Data Modeling
Power Query
Visualization
DAX (Data Analysis Expressions)
Reports and Dashboards
Collaboration and Sharing
Comparison with Tableau:

Tableau excels in complex visualizations; Power BI integrates well with Microsoft products.
Tableau has a more interactive interface; Power BI is structured like other Microsoft tools.
Tableau is often used in data science; Power BI is common in business settings.
Power BI is generally more affordable, especially for Microsoft 365 users.

**part_2**

**task_4**

![image](https://github.com/user-attachments/assets/08b4e174-0997-489c-b1a1-22c7bd0fc901)

**task_5** 

![image](https://github.com/user-attachments/assets/d325853d-19a8-4142-8a69-ef47e30803ab)


**task_6**

![customer feedback dashboard 1](https://github.com/user-attachments/assets/1324c1ed-68d0-4069-9acc-87157f5896da)


**part_3**

**task_7**

**Summary of Findings**


**1. Correlation Analysis**

**Correlation Matrix:**

There are strong positive correlations between:
'sepal_length' and 'petal_length'
'petal_length' and 'petal_width'
No significant correlation was found between 'sepal_width' and other features.

**2. Hypothesis Testing**

**T-test Results:**

Comparison: Mean sepal lengths of 'setosa' vs. 'versicolor'
T-statistic: -10.52
p-value: 0.0000
Since the p-value is less than 0.05, the null hypothesis is rejected, indicating a significant difference in sepal lengths between these species.

**3. Visualizations**

**Correlation Matrix:**

Visualized using a heatmap to showcase the strength of relationships between features.
Distribution of 'sepal_length':
Displayed to highlight distinct patterns across different species.


**part_4**

**Identifying Key Customer Segments and Their Behaviors**

**Overview**

In this task, we aim to identify key customer segments and their behaviors from a large dataset of customer transactions. Below is a step-by-step approach to tackle this problem using various tools and techniques.

**Approach**

Data Exploration & Cleaning

Objective: Understand the structure of the dataset and prepare it for analysis.
Tools: Python (Pandas, NumPy), Jupyter Notebook.
Steps:
Load the dataset and inspect the first few rows.
Check for missing values and outliers.
Clean and preprocess the data (e.g., handle missing values, normalize data).
Feature Engineering

Objective: Create meaningful features that can help in identifying customer segments.
Tools: Python (Pandas, scikit-learn).
Steps:
Extract relevant features (e.g., total spend, frequency of transactions).
Create new features if necessary (e.g., recency, frequency, monetary value – RFM analysis).
Segmentation Techniques

Objective: Identify distinct customer segments using clustering algorithms.
Tools: Python (scikit-learn, KMeans, DBSCAN, Hierarchical Clustering).
Steps:
Normalize the data to ensure fair clustering.
Choose appropriate clustering algorithms (e.g., KMeans for distinct clusters, DBSCAN for arbitrary shapes).
Determine the optimal number of clusters (e.g., using the Elbow method for KMeans).
Analysis & Interpretation

Objective: Analyze the clusters to understand customer behaviors and characteristics.
Tools: Python (Matplotlib, Seaborn), Excel (for additional analysis).
Steps:
Visualize clusters to interpret results (e.g., scatter plots, heatmaps).
Summarize key characteristics of each segment (e.g., average spend, frequency).
Reporting

Objective: Present findings in a clear and concise manner.
Tools: Jupyter Notebook (for interactive reports), PowerPoint or Google Slides (for presentations).
Steps:
Document the segmentation process, insights, and recommendations.
Prepare visualizations and charts to illustrate key findings.

**Tools Summary**

Python Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
Software: Jupyter Notebook, Excel, PowerPoint/Google Slides

**Conclusion**

By following the above steps, you can effectively identify and analyze key customer segments, leading to actionable insights and improved business strategies.

