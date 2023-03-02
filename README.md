# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
 
Attribute Information
show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Releaseyear of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description


Conclusion

The trend of TV shows increasing rapidly from 2017, Even in 2021 Netflix has more TV shows than movies. Mostly TV shows are of 2-3 seasons. In both TV series and movies, TV-MA has the highest  number of ratings i.e for mature audience. There is no any TV shows under rating PG, PG_13 and R. In TV-Y and TV-Y7 rating there are more TV shows available than movies. In India, France and Germany drama and comedies  content are most popular.Children movie and kid's tv shows are most popular in Canada, whereas british tv shows are most popular in UK. Anime series and feature are most popular in japan. Romantic and Korean tv series are most popular in south Korea. The months of October, November, December and January had the largest number of films and TV-shows released. In Asian countries mostly movies rating are under TV-MA and TV-14. In Nato countries(European countries, America e.t.c) mostly movies rating are under TV-MA and R rating. Very few indian actor work on any Tv shows and series, this means famous indian actor prefer movies more than tv series Out of top 10 country content present in netflix only in Japan and south Korea TV Shows are more popular than movies. K means clustering perform better than hierarchical clustering. average Silhouette score for KNN is 0.0063 where as average Silhouette score for hierarchical clustering is -0.0009.from elbow method , for knn optimal of 16 clusters formed. We cut vertical lines with a horizontal line to obtain the number of clusters in Agglomerative Clustering. There  were five clusters, with an average silhouette score of  -0.0009. LDA has sorted much more similar title.
