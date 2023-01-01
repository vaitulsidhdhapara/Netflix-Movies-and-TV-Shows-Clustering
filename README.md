# Netflix-Movies-and-TV-Shows-Clustering
The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

![image](https://user-images.githubusercontent.com/112092937/210173084-bc04841f-f034-4ccd-9c14-9d01720a2668.png)



***Introdution***


Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.




***Problem Discription:***


This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

In this project, required to do:

  * Exploratory Data Analysis
   
  * Understanding what type content is available in different countries
    
  * Is Netflix has increasingly focusing on TV rather than movies in recent years.
    
  * Clustering similar content by matching text-based features
    
  
  
 ***Data Description:***
  
 This dataset consist of 7787 rows and 12 columns.
  
 * show_id : Unique ID for every Movie / Tv Show

 * type : Identifier - A Movie or TV Show

 * title : Title of the Movie / Tv Show

 * director : Director of the Movie

 * cast : Actors involved in the movie / show

 * country : Country where the movie / show was produced

 * date_added : Date it was added on Netflix

 * release_year : Actual Releaseyear of the movie / show

 * rating : TV Rating of the movie / show

 * duration : Total Duration - in minutes or number of seasons

 * listed_in : Genere

 * description: The Summary description
  
  
  ***Algorithms Used:***
  
  
  (1)  K-Mean Clustering
  
  (2)  Hierarchical Clustering (Agglomerative Clustering)
  
  (3)  Silhouette Score for Clustering
  
  
  ***Conclusion:***
  
  
  * From elbow,sillhoute score and Dendrogram , discovered that Optimal number of clusters are six.
  * Netflix has 5377 movies and 2410 TV shows, there are more number movies on Netflix than TV shows.
  * Highest number of movies released in 2020 The number of movies on Netflix is growing significantly faster than the number of TV shows. We saw a huge increase in the number of movies and television episodes after 2015. there is a significant drop in the number of movies and television episodes produced after 2020. It appears that Netflix has focused more attention on increasing Movie content than TV Shows. Movies have increased much more dramatically than TV shows.
  * The most content is added to Netflix from october to january.
  * International Movies are the top most genre in netflix, followed by  Dramas, comedies and international movies.
  * Most of the movies have duration of between 70 to 150.
  * Unitated states has the highest number of content on the netflix ,followed by india.
  * TV-MA has the highest number of ratings for tv shows. It means that Majority of Content is for Adults.
  * Using the given data a simple recommender system was created using cosine_similarity and recommendations for Movies and Tv Shows were obtained.
