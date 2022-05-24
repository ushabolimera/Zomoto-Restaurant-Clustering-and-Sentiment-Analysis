# Zomoto-Restaurant-Clustering-and-Sentiment-Analysis
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analysing the Zomato restaurant data for each city in India.
# Problem Statement
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.

This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis

Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.
# Data Description
Zomato Restaurant names and Metadata

Name Name of Restaurants
Links URL Links of Restaurants
Cost Per person estimated Cost of dining
Collection Tagging of Restaurants w r t Zomato categories
Cuisines Cuisines served by Restaurants
Timings Restaurant Timings
Zomato Restaurant Reviews

Restaurant : Name of the Restaurant
Reviewer : Name of the Reviewer
Review : Review Text
Rating : Rating Provided by Reviewer
MetaData : Reviewer Metadata No. of Reviews and followers
Time : Date and Time of Review
Pictures : No. of pictures posted with review
# Data Pipeline
# Data Processing
Understanding and cleaning the data

# Data Exploration
Analyse the data through visualization

# Model Performed
Multinomial Naive Bayes

Random Forest Classifier

XGB Classifier

Support Vector Classifier

K-Means clustering

Principal Component analysis

# Conclusion
The most popular cuisines are the cuisines which most of the restaurants are willing to provide The most popular cuisines in Hyderabad are North Indian, Chinese, Continental, and Hyderabadi

The cheapest is the food joint called Mohammedia Shawarma and the costliest restaurant is Collage Hyatt Hyderabad Gachibowli

Sentiment Analysis was done on the reviews and a model was trained in order to identify negative and positive sentiments

SVM and XGB both performed well and we can choose any one them

SVM and XGB are having 0 921 and 0 981 of testing accuracy respectively

We got best cluster as 5 in K Means and Principal Component Analysis(PCA)
