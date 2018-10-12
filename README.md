Capstone Project： Which feature affect wine points the most?
===

@EllenMengqiXu
---

Abstract
---
You can always hear prejudices such as higher price leads to better wine; the best winery is in France and so on. Why wine is so popular among drinks? One of the main reasons is that a favorite wine can be associated with a particular time, place, or memory. That’s the thing with great food and great wine — it is woven into our life experiences. When it comes to wine, the taste, the bouquet, or simply the wine-drinking experience itself can elicit a memory of a time or place. 
In addition, wine makes food taste better, wine tells a story about where it comes from, wine is tradition and history, it enhances special occasions, wine improves health and so on. Based on these appealing points, I decided to implement the analysis of wine popularity and try to figure out suggestions to wine buyers when they select wine. In this project, I will do it in that pattern, which is commonly used for solving this type of problems: data wrangling, data visualization, feature engineer, model training and feature exaction.

Brief Description:
---

This project goal is to find out why wine is so popular in the world through data analytics perspective. In other words, I want to figure out which feature or features influence(s) wine rating points most. I collected dataset from Kaggle, which is the world's largest community of data scientists and machine learners. The dataset is made up of 13 features (2 numerical features and 11 categorical features) and 129,970 records. After loading this dataset as csv file, I did data wrangling by using Pandas, Numpy and missingno library to deal with duplicated recording removal, missing value removal and null object column removal. 
The next step is to experiment data visualization by importing library such as pyplot, seaborn, squarify and so on. These library helps me to figure out how these variables affect each other and how their trends look like. In the third step, I did feature engineer by analyzing every single feature and had ageneral idea on which several features have influenced wine review. In the fourth step, from SKlearn importing Decision Tree Classifier, Random Forest Classifier, KNeighbors Classifier, Gradient Boosting Classifier and Cat Boost Classifier, I trained these models and calculated the accuracy. By comparing these accuracy, we went to the fifth step, which is to extract features affect wine popularity most. After finish coding project, I summarized suggestion how customers should pay more attention while selecting wine.
