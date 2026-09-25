# 📊 Social-Media-Engagement-Analysis
Analyzed a 5,000-record social media engagement dataset using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly. Performed data cleaning, EDA, statistical analysis, and visualization to identify insights across content performance, user trends, behavioral patterns, and sentiment analysis.

## 📌 Project Overview
This project analyzes a Social Media Engagement dataset containing 5,000 records using Python. The analysis focuses on understanding social media performance, user behavior, engagement patterns, and sentiment.
The project covers the complete data analysis process, including data import, data cleaning, exploratory data analysis, statistical analysis, feature engineering, and data visualization.
## 🎯 Objectives
-	Import and understand the social media dataset.
-	Clean missing and duplicate data.
-	Correct data types and inconsistent values.
-	Perform exploratory data analysis using Pandas.
-	Create new features such as engagement score and hashtag count.
-	Perform statistical analysis of important engagement metrics.
-	Create visualizations using Matplotlib and Seaborn.
-	Create interactive visualizations using Plotly.
-	Extract meaningful insights from the dataset.
## 🛠️ Technologies Used
-	Python
-	Pandas
-	NumPy
-	Matplotlib
-	Seaborn
-	Plotly
-	Jupyter Notebook
## 📂 Dataset
Dataset: social_media_engagement_5000.csv
The dataset contains social media engagement information such as:
-	Likes
-	Comments
-	Shares
-	Impressions
-	Watch Time
-	Engagement Rate
-	Followers
-	Age
-	Gender
-	Country
-	Post Type
-	Category
-	Device
-	Sentiment
-	Verification Status
-	Hashtags
-	Date/Time
## 🔄 Project Workflow
### 1. Data Import & Setup
The CSV file was imported using Pandas.
The following operations were performed:
-	Loaded the dataset using pd.read_csv().
-	Examined the first and last records.
-	Checked dataset shape and columns.
-	Checked data types using dtypes and info().
-	Converted date columns into datetime format.
### 2. Data Cleaning
The dataset was cleaned before performing analysis.
1.	Missing Values
-	Identified missing values using isnull() and isna().
-	Numerical missing values were handled using median.
-	Categorical missing values were handled using mode.
-	Appropriate fill methods were considered for missing data.
2.	Duplicate Records
-	Identified duplicate records.
-	Removed duplicate rows using drop_duplicates().
3.	Data Formatting
-	Corrected inappropriate data types.
-	Standardized categorical values.
-	Cleaned sentiment labels.
-	Checked unrealistic values in likes, comments, and shares.
4.	Feature Cleaning
-	Extracted hashtag counts.
-	Created an engagement score using likes, comments, and shares.
## 🔎 3. Exploratory Data Analysis
The dataset was explored using Pandas.
The following methods were used:
-	head()
-	tail()
-	shape
-	columns
-	info()
-	dtypes
-	describe()
-	value_counts()
-	unique()
-	nunique()
-	groupby()
Correlation analysis was also performed on numerical variables to understand relationships between engagement metrics.
## 🔧 4. Data Wrangling & Feature Engineering
New features were created to support deeper analysis.
1.	Engagement Score
An engagement score was created using:
Engagement Score = Likes + Comments + Shares
2.	Hashtag Count
The number of hashtags associated with each post was extracted.
3.	Date Features
Date-related features such as day, month, year, and day name were extracted where applicable.
4.	GroupBy Analysis
Data was grouped by:
-	Post Type
-	Country
-	Category
-	Sentiment
-	Device
-	Age Group
This helped compare engagement and performance across different groups.
## 📊 5. Statistical Analysis
Descriptive statistics were calculated for the following variables:
-	Likes
-	Comments
-	Shares
-	Watch Time
-	Engagement Rate
-	Followers
The following statistical measures were calculated:
-	Mean
-	Median
-	Mode
-	Standard Deviation
-	Variance
-	Percentiles
-	Skewness
-	Kurtosis
These measures helped understand the distribution and variation of social media engagement metrics.
## 📈 6. Data Visualization
Multiple visualizations were created using Matplotlib, Seaborn, and Plotly.
### 1.	Matplotlib
-	Scatter Plot – Likes vs Impressions
-	Line Chart – Daily Engagement Trend
-	Bar Chart – Posts by Category
-	Pie Chart – Gender Distribution
-	Histogram – Age Distribution
-	Box Plot – Engagement Rate
### 2.	Seaborn
-	Count Plot – Post Type
-	Bar Plot – Average Likes by Category
-	Violin Plot – Followers vs Sentiment
-	Pair Plot – Numeric Features
-	Heatmap – Correlation Matrix
-	Swarm Plot – Engagement vs Device
### 3.	Plotly
-	Interactive Line Chart
-	Interactive Bar Chart
-	Interactive Scatter/Bubble Chart
## 🔍 7. Key Analysis
### 📱 Content Performance Analysis
Analyzed the performance of different post types and content categories using:
-	Likes
-	Comments
-	Shares
-	Impressions
-	Engagement Rate
-	Engagement Score
The analysis helps identify differences in engagement across content types, categories, and countries.
### 👥 User Trends Analysis
Analyzed how user characteristics relate to engagement.
Factors included:
-	Age
-	Gender
-	Followers
-	Verified/Non-verified accounts
Age groups were created to compare engagement rates across different user age ranges.
### ⏰ Behavioral Insights
Analyzed:
-	Impressions by time of day
-	Watch time by device
-	Engagement by device type
-	Daily engagement trends
This analysis helps understand patterns in user activity and content consumption.
### 💬 Sentiment Analysis
Compared social media performance across:
-	Positive sentiment
-	Neutral sentiment
-	Negative sentiment
The analysis included:
-	Average likes
-	Average comments
-	Average shares
-	Average impressions
-	Average engagement rate
Negative and neutral sentiment posts were also compared to understand differences in audience behavior.
##💡 Insights
 ### 📊 Reporting & Insights
### 1. Summary of Key Findings
The social media engagement dataset was analyzed to understand content performance, user behavior, engagement patterns, and sentiment. The analysis used metrics such as likes, comments, shares, impressions, watch time, followers, and engagement rate.
The analysis showed that engagement varies across different post types, content categories, countries, user age groups, devices, account verification status, and sentiment categories.
### 2. Trends and Patterns
### 📱 Content Performance
Different post types and content categories show different levels of audience engagement. Average likes, comments, shares, and engagement rates were compared to identify variations in content performance.
The relationship between impressions and likes was also analyzed to understand whether greater content reach is associated with higher audience interaction.
### 👥 User Trends
Age groups were compared based on their average engagement rate to identify differences in user engagement.
Verified and non-verified accounts were also compared using metrics such as likes, followers, shares, and engagement rate. This helps identify differences in observed performance between the two account groups.
### ⏰ Behavioral Insights
Engagement and impressions were analyzed across different times of the day to identify variations in audience activity.
Watch time was also compared across device types. This helps understand how device usage is associated with the amount of time users spend viewing content.
### 💬 Sentiment Analysis
Positive, neutral, and negative posts were compared using likes, comments, shares, impressions, and engagement rate.
This analysis helps identify differences in audience interaction across sentiment categories and provides a clearer understanding of how sentiment is associated with social media performance.
### 3. Linking Metrics to Meaningful Insights
The analysis connects individual metrics to broader social media performance:
-	Likes indicate direct audience appreciation or interaction.
-	Comments provide an indication of deeper audience participation.
-	Shares help measure how frequently content is redistributed.
-	Impressions measure content visibility and reach.
-	Engagement Rate helps compare audience interaction relative to the reach or audience size.
-	Watch Time indicates how long users interact with video content.
-	Followers provide context for understanding account reach.
-	Engagement Score combines likes, comments, and shares to provide an overall interaction measure.
By comparing these metrics across content, users, behavior, and sentiment, the analysis transforms raw social media data into meaningful insights.
### 4. Overall Insight
The project demonstrates how data cleaning, exploratory data analysis, statistical analysis, feature engineering, and visualization can be combined to understand social media engagement.
The findings can be used to identify patterns in content performance, audience behavior, posting activity, device usage, and sentiment. These insights provide a data-driven understanding of factors associated with social media engagement and can support future content performance analysis.
## 📁 Project Structure
Social-Media-Engagement-Analysis/
│
├── social_media_engagement_5000.csv
│
├── Social_Media_Engagement_Analysis.ipynb
│
├── README.md
│
└── images/
    ├── engagement_trend.png
    ├── category_analysis.png
    ├── sentiment_analysis.png
    └── correlation_heatmap.png
## ✅ Conclusion
This project demonstrates an end-to-end Python Data Analysis workflow using a social media engagement dataset.
The project covers:
Data Import → Data Cleaning → EDA → Data Wrangling → Statistical Analysis → Visualization → Insights
The analysis provides a practical understanding of social media engagement patterns across content, users, behavior, devices, countries, and sentiment.
## 👩‍💻 Skills Demonstrated
Python | Pandas | NumPy | Matplotlib | Seaborn | Plotly | Data Cleaning | Exploratory Data Analysis | Statistical Analysis | Data Visualization | Feature Engineering | Data Wrangling | Business Insights
You can upload these 3 files together to GitHub:
1.	Social_Media_Engagement_Analysis.ipynb
2.	social_media_engagement_5000.csv
3.	README.md
## 👩‍💻 Author
Sugantha B
-	Aspiring Data Analyst | Python | SQL | Power BI | Excel


