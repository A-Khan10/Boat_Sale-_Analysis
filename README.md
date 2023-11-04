# Boat Sale Analysis
## Introduction
Welcome to 'Navigating the Digital Waves: A Guide to Online Boat Sales and Purchases'.
In this presentation, we will explore the world of online boat sales and provide you with valuable tips and insights on how to successfully buy or sell a boat online. So, let's dive in!
 
## Objectives and Key Questions
 
A weekly newsletter for boat owners is being prepared by the marketing staff of a yacht and boat sales website.
The publication is intended to assist sailors in obtaining more views of their boats while also staying up-to-date on the latest market trends.
 
The marketing management wants to look at recent data and get some insights.
The key questions from the marketing teams are:
 
1. What are the characteristics of the most-viewed boats listed in the previous seven days?
2. What is the cost of the boats that garner the most attention?
3. Is there anything in common among the most-viewed boats?
4. Where are the most-watched boats located?

# TOOLS
Language: Python
Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scipy, Quandl, matplotlib.pyplot,
statsmodels.api, json, folium, from folium import plugins, 
sklearn, from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split 
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
from sklearn.cluster import KMeans 
from scikit-learn, import pylab
Software: Jupyter Notebooks and Tableau
# SKILLS DEMONSTRATED
Data Wrangling, Cleaning data: removed duplicates; found and resolved missing values; addressed mixed or incorrect data types.

Exploratory & Descriptive Analysis: explored basic descriptive statistics (max/min, quartiles, mean, standard deviation) for each variable as well as using histograms, scatterplots, and bar and line charts to explore the distributions of data.

Exploring Relationships, Data prep for Regression Analysis, Regression Analysis
Standadizing the data, The elbow technique, k-means clustering,
Subsetting of the Data
Time series analysis: Decomposition
Testing for stationarity ( Dicky-Fuller Test / Autocorelation Test )¶
Stationarizing the Data

Derived new variables, Used aggregated data to create flags.
Visualising data: Create histograms, line charts, and bar charts, Plotting a choropleth, Correlations Scatterplots Pair Plots Categorical Plots,


# DELIVERABLES
Reporting results: [Tableau presentation](https://public.tableau.com/app/profile/ayaz.khan7372/viz/BoatsSaleAnalsis/BoatSale) that explained the answers to questions from sales and marketing as well as documenting the data population flow, consistency checks, data wrangling, and column derivations.
[Final Tableau Report](https://public.tableau.com/app/profile/ayaz.khan7372/viz/BoatsSaleAnalsis/BoatSale): Include analysis findings, visualisation, conclusion and recommendations to Boat Sales Marketing Team.
 
## Data Source
The data for this dataset is sourced from [Kaggle.com](https://www.kaggle.com/datasets/karthikbhandary2/boat-sales) revolves around a boat sales website where individuals sell both new and used boats. This website serves as a platform for boat owners to list their boats for sale, providing a diverse and dynamic source of information related to boat sales. The data source is directly tied to the boat sales market, making it highly relevant for marketing and trend analysis in the boating industry.
## Data Collection
The data collection process for this dataset is continuous and ongoing, with updates expected on an annual basis. This regularity in updates ensures that the dataset remains current and reflective of changing market conditions. The marketing team uses this data to create a weekly newsletter for boat owners, helping them enhance the visibility of their listings and stay informed about market trends. The data collection process likely involves web scraping or API access to gather information from the boat sales website.
## Contents
This dataset comprises 10 columns of information, focusing primarily on boat popularity. Key attributes include details about the boat's year of manufacture, its type, price, and various other relevant features. The dataset appears to be rich in boat-specific information, providing a comprehensive overview of boats available for sale on the website. Such details are valuable for understanding market trends and assisting boat sellers in making informed decisions.
## Limitations and Ethics
While this dataset offers valuable insights into the boat sales market, it may have certain limitations. One potential limitation is the accuracy and completeness of the data, as it relies on user-generated content on the website. There could be errors or discrepancies in the listings, affecting the dataset's reliability. Additionally, ethical considerations such as data privacy and consent should be addressed, ensuring that the personal information of boat owners and sellers is handled responsibly and in compliance with relevant regulations.
## Data Relevancy
This data was provided in the CareerFoundry Project Brief. This data collection fits the project's requirements since it is open source, contains geographical objects such as country and city, and comprises 9888 rows and 10 columns. This dataset is highly relevant for my analysis, especially given my interest in the subject of sales.

## Data Requirements
The data set(s) you choose must:
- Be open-source.
- Come from an authentic/authoritative source.
- Include non-anonymized column names.
 - Be recent (ideally, no more than 3 years old. However, this factor is not essential - if you’ve found a perfect data set for your purposes, it could be older too, but not more than 10 years old).
- Contain at least 2-3 continuous variables (apart from index variables, ID variables, dates, years, etc).
- Contain at least 2-3 categorical variables (apart from index variables, ID variables, dates, years etc).
- Contain at least 1,500 rows.
- Include a geographical object of some kind: for instance, a column relating to a country,
continent, or something similar. If the information from the data set refers to the US, for example, there should be a column containing the names/abbreviations of the states. Note: there should be at least a couple of different values in this column. This is important for the geospatial analysis you’ll be conducting. Of course, you can also use data sets with latitude and longitude.
- In the course of the Achievement you will source a time series data set too, but this procedure will be explained explicitly in the corresponding Exercise.
