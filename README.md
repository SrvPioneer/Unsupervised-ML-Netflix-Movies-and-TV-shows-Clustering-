# Project Title : Netflix-Movies-and-TV-shows-Clustering-Unsupervised-Machine-Learning

# Problem Description:
In 2018, Flixable released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

In this project,we have done:

Exploratory Data Analysis

Understanding what type content is available in different countries.
![image9](https://user-images.githubusercontent.com/93809665/229981079-c1a1f9ed-b3eb-4963-9d7b-08815d911fbd.PNG)

Is Netflix has increasingly focusing on TV rather than movies in recent years.
![image10](https://user-images.githubusercontent.com/93809665/229981285-767a5078-4d83-4009-a58b-a3f471598e49.PNG)


Clustering similar content by matching text-based features
![image11](https://user-images.githubusercontent.com/93809665/229981325-b6f524b4-cc8f-4dd4-8cb3-55a965ce516d.PNG)


# Steps Involved
* Exploratory Data Analysis
* Data Preparation:
  1. Text Pre-processing
    a.) Removing Punctuations
    b.) Removing Stopwords
    c.) Stemming
    d.) Creating New Variables for Text Length
  2. Rescaling the data
* Clustering:
1. Implementing K- Means Clustering
2. Implementing Hierarchical Clustering


# Conclusion :
After pre-processing the data, I started with EDA to understand the trends and features of the provided dataset. Major findings from EDA are as follows:

* There is 69% movie content and 31% TV show content in the dataset.

* The United States account for the majority of the content created on Netflix, numbering 3051 titles. India is the second largest with 923 titles.

* All the top 10 countries producing highest amount of content have higher proportion of movies than TV shows except Japan, South Korea and United Kingdom.
Netflix is increasingly focusing on TV Shows now, which is clear from the graph, from 2019 to 2020, there was a decreasing trend of Movies.The TV shows from 2019 to 2020 remains constant.

* TV-MA, TV-14 and TV-PG are the top content rating to which highest number of content belongs.
Among the top 10 countries with highest content volume, United States and India has highest volume of content appropriate for teens and most other countries have highest volume of content appropriate for adults.

* Content onboarding on Netflix started increasing from 2015 and reached to its peak in 2019, there is a drastic downfall in 2021. The downfall can be attributed to Covid pandemic.

* International movies is the highest content genre in movies and International TV Shows is the highest one in TV shows.
TV shows with one season are highest in number.

* Findings after applying k- means and Hierarchical clustering:

* K-means clustering is used to form the clusters of clusters of the content. To find out the optimal value of k, Elbow and Silhouette method was used.K=6 was   appropriate value and can be visualized after clustering the content using k-means clustering.

* Hierarchical clustering implementation gives perfect score of silhouette at 7 clusters,same as visualised using dendrogram.

# Next Step :
The next would be utilising the clusters made of movies to recommend the users, further we can make arecommendation engine out of it.
