# WineReview
Capstone Project： Which feature affect wine points the most?
Project Proposal
Title:
Analysis of wine popularity and suggestion to customers for wine selection
Student:
Mengqi Xu
Abstract:
You can always hear prejudices such as higher price leads to better wine; the best winery is in France and so on. In this project, I am going to do three steps to analyze how wine become popular. The first step is to find the relationship between wine prices and points (The number of points rated the wine). The second step is to visualize how those wineries locate on a world map. The last one is to determine how variety, location and production year affect price. At last, I will give customers suggestions how to choose the best wine.
Brief Description:
The data was collected from kaggle during the week of June 8th, 2018. After feature selection (deducting feature such as description, taster_name, taster_twitter_handle and keeping feature such as country, points, price, title, variety, winery and so on), I will use Python, SQL, tableau and other tools to analyze this dataset. In the first step, I plan to use logistic regression model to find the relationship between prices and points (also try other regression models to find the best way to present the relationship); in the second step, use tableau to map those winery locations (also import folium to do data visualization and compare which way looks more vivid); in the last step, use decision tree algorithm to analyze the proportion in variety (pinot noir, chardonnay, red blend and so on), location (US, France, Italy and so on) and production year (2003, 2008, 2011 and so on) and use SVM to find out the key role in these three features who affected price most.
