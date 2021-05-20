# Leonardo Patricelli Data Science Portfolio

## *Project 1: Movie recommendation engine system based on emotions*
*Final Capstone Project in collaboration with [MAGID]( https://magid.com/ )* 

*[Click here to read the PDF presenation (with censor)]( https://github.com/ianux22/RECOMMENDATION-ENGINE-SYSTEM-BASED-ON-EMOTIONS/blob/master/Capstone_Prezo.pdf )* 
*[Click here to go to the repository and read more details)]( https://github.com/ianux22/RECOMMENDATION-ENGINE-SYSTEM-BASED-ON-EMOTIONS/tree/master  )* 

As project leader of a team of 4, I led the development of new film genres and a movie recommendation app based on emotions. Using original survey data collected by MAGID on the emotional responses of respondents after watching a movie and other demographic data, we achieved over 80% of accuracy on the XGBoost model and various exciting insights.
The project steps were:

- Creating new metrics based on emotions using correlations and factor analysis;
-	Creation of new movie genres based on emotions rather than contents using clustering algorithms;
-	Inspect what the emotions that affect most the rating are, using correlations and feature importance from XGBoost;
-	Working with real survey data supplied by MAGID on perceived emotional responses by the users and demographic data (age, income, etc.)
-	Customer segmentation looking at customer habits;
-	Using Python programming for clustering and building a model to predict good and bad ratings;

## *Project 2: Application of statistical machine learning algorithms in football matches*
*Master’s degree thesis at University of Turin, in collaboration with [OPTA Sport](https://www.optasports.com/)*

I created a model to predict the outcome of a match using metrics related to a team’s network and playstyle with 85% of accuracy. OPTA sport provided high-quality data about games of the Italian championship season 2012/2013. The project involved:

- Data extraction from XML files and data cleaning; 
- Building adjacency matrices for each team and metrics related to network and playstyle implemented in several papers of statistics and sport;
- Developing and tuning several machine learning algorithms in the R programming language to predict the outcome of a match. The best one was a SVM model.

## *Project 3: Insights on ALS and other rare diseases through open data*
*Project for Hackathon 2021 at Seneca College, in collaboration with [Orphadata](http://www.orphadata.org/cgi-bin/index.php)*

*[Click here to read the PDF presenation)]( https://github.com/ianux22/Hackathon_Seneca_2021/blob/main/Obtaining%20insights%20on%20ALS%20and%20other%20rare%20diseases%20through%20Open%20data.pdf )* 
*[Click here to go to the repository and read more details)]( https://github.com/ianux22/Hackathon_Seneca_2021  )* 

Orphadata provides the scientific community with data about rare diseases. In this challenge, we had to retrieve data about rare diseases to gain insights and develop an application to assist doctors and researchers with diagnosing rare diseases. The challenge involved:

- Massive data Cleaning and extraction from XML file; 
- Data Analysis using Python programming language; 
- Creation of an application to run the analysis.

## *Project 4: Predictive models for Torino’s museums subscription churn rate*
*Project done for the business analytics course during my master’s degree at the University of Turin*

*[Click here to read the PDF Report for more details)]( https://github.com/ianux22/Torino_museums_subscriptions/blob/main/Patricelli_Previous_Work.pdf )* 
*[Click here to go to the repository and see the R code)]( https://github.com/ianux22/Torino_museums_subscriptions  )* 

This project was about predicting and analyzing the customers who renew the subscription of Piemonte’s museums (and who doesn’t), using the 2014 data to predict the 2015 renewals using the R programming language. In the end, I created a Random Forest model able to predict correctly almost 75% of the renewals. The project included: 
-	Data extraction, cleaning and exploratory analysis with R; 
-	Data visualization using ggplot2 package for analytics and to create a map of the region that shows the distribution of renewals on the territory;
-	Market basket analysis via association rules to analyze the patterns of the visitors and the most popular museums;
-	Customer segmentation via self-organizing maps;
-	Logistic regression to analyze the features with the highest impact on the probability to churn;
-	Creation and comparison of several models to predict renewals and expected profit. At the end a Random Forest model was chosen.

## *Project 5: Report on Toronto bicycles' thefts*
*Report done for the blog [The Pizza Statistician](https://ianux22.wixsite.com/thepizzastatistician) with data from the [city of Toronto open data portal](https://open.toronto.ca/dataset/bicycle-thefts/)*

*[Click here to read the Report for more details)]( https://ianux22.wixsite.com/thepizzastatistician/post/study-on-toronto-s-bicycle-thefts )* 
*[Click here to go to the repository and see the R code)]( https://github.com/ianux22/Toronto_Bike_Thefts  )* 

This project analyzes all bicycle theft occurrences reported to the Toronto Police Service from 2014 to 2019 using the R programming language. As expected, most of thefts happen to be in the evening of summer months. The project involved: 
-	Data cleaning and extraction from the Toronto open data repository using the R programming language;
-	Data visualization using the Ggplot2 package to plot analytics;
-	Data Visualization using shapefile objects to plot Toronto’s neighborhoods (140 in total);
-	 Use of clustering to group the neighborhoods according to the number of thefts happened in them (4 groups in total);
-	Thefts’ prediction for summer 2019 using an XGBoost algorithm.

## *Project 6: Customer segmentation and classification with unbalanced data*
*Report done in college for the course **business, web and social media metrics and analysis**, based on the case study from the book **Data mining for business analytics: concepts, Techniques and Applications in Python***

*[Click here to read the PDF presentation)]( https://github.com/ianux22/Case_Study_GeorgeBrown/blob/main/03_CaseStudy_Logit_with_Unbalanced_Data/CaseStudy03_Presentation.pdf )* 
*[Click here to go to the repository for more details)]( https://github.com/ianux22/Case_Study_GeorgeBrown/tree/main/03_CaseStudy_Logit_with_Unbalanced_Data  )* 

In this case study my group was asked to run a customer segmentation on transaction data and then retrieve the cluster containing people who stick with their favorite brand and don’t churn.
I was responsible for the whole code and analysis. In the end, We managed to build 7 clusters using different metrics and a logit model able to reach 86% of precision using unbalanced data. The project involved: 
-	Data cleaning and feature engineering to create new useful metrics;
-	Division of the variable into groups in order to create clusters (purchase behaviour, basis for purchase and a third one which is the union of the previous 2);
-	Clustering using K-means and elbow method;
-	Find the cluster containing “loyal” customers, then creation, optimization and comparison of a Logit model and a Tree classifier to predict those customers using an unbalanced dataset (with ratio 88:12); in the end, the logit model outclass the tree classifier;

## *Project 7: Market Basket Analysis using Association Rules*
*Report done in college for the course **business, web and social media metrics and analysis**, based on the case study from the book **Data mining for business analytics: concepts, Techniques and Applications in Python***

*[Click here to read the PDF presentation)]( https://github.com/ianux22/Case_Study_GeorgeBrown/blob/main/02_CaseStudy_MarketBasketAnalysis/CaseStudy02_Presentation.pdf )* 
*[Click here to go to the repository for more details)]( https://github.com/ianux22/Case_Study_GeorgeBrown/tree/main/02_CaseStudy_MarketBasketAnalysis  )* 

In this project my group was asked to run a market basket analysis via association rules on transaction data to analyze the sellings and to introduce a cross-selling strategy to improve the revenue. The steps involved were: 
-	Data cleaning and data exploration;
-	Association rules using the python library mlxtend
-	Analyze the rules obtained looking at metrics like confidence, lift and support;

