# Netflix-Clustering
This Project was of unsupervised type and was aimed at clustering, NLP, and EDA of the Netflix Data set, to come up with various insights and conclusions & recommendations to maximize the customer base and the number of active users watching movies or TV shows.

At first, we found the missing values in the dataset, and then after replacing the null values and cleaning the dataset, we performed EDA on it and found out below observations,

# Our Findings:-
• The ratio of TV shows vs Movies is 31: 69, thus the total number of movies is more than double the number of TV shows & web series.

• Most of the Tv shows/web series have max 3 seasons, this refers that the forthcoming Tv shows can be introduced in similar 2-3 series max else it loses their TRP (viewership).

• The Movie’s duration is 90 min – 110 mins for most movies, which can be inferred that people are comfortable watching movies within this time duration.

• Maximum number of Movies, as well as TV shows, are Rated under the TV-MA category and then followed by TV-14.

• There is a trend that most movies and TV shows are added during the October to January months of the year.

• The number of movies and TV shows added has constantly risen from 2015 to 2019 but we have found out that more movies were added during this tenure as compared to TV shows but between 2019- 2020 yes there have been more TV shows added than Movies. 
• Then we tabulated the top 15 countries which have released the most movies and TV shows and found that the US is on top in both. In shows the US is followed by the UK and in movies the US is followed by India. • We also have actors who were part of most shows and movies which gave us that Takahiro Sakurai has worked in most shows and Anupam Kher has worked in most movies.

• We also found out that Genre wise International movies & Tv shows are the most in number followed by Drama & Comedy categories and this order is the same for Movies and Tv shows. • Also Using NLP we have found out the top 10 recommended movies and Tv shows by implementing Cosine similarity which has the most similarity with the other content present on Netflix, using this features the suggested TV shows and Movies can be recommended to a particular user based upon his past preferences.

Results of different clustering Algorithms:- • Using K –Modes, in the elbow plot we can see that the elbow is formed at 3, so the number of clusters formed as per K-Modes is 3.

• Using DB Scan, As shown by the color codes of the DB Scan graph, it can be seen that the algorithm is clustering the data into 3 main clusters.

• Using Agglomerative hierarchical clustering, In our case we got 2 vertical lines, which symbolizes that the given data can be best divided into 2 clusters.

• Using Spectral Clustering we got 2 clusters.

• Using K-Means Clustering Silhouette score closest to 1 is considered as best and its respective value shows the optimal no. of clusters for the given dataset data. Here 2 No. of clusters is the optimal number of clusters because its respective silhouette score of 0.6 was the highest amongst all.

• Spectral Clustering • K –Modes • DB Scan • K- Means • Hierarchical agglomerative

# Conclusion:-
For NetFlix Movies, International Movies with genres such as Drama, Comedy & thriller, etc. having a duration of 90-110 mins are the most preferred ones and are the safe bet for good viewership and for attracting more new subscriptions, also people like to watch actors like Anupam Kher, Shahrukh Khan, Akshay Kumar, Kareena Kapoor, Boman Irani, Paresh Rawal etc. For NetFlix TV shows, we recommend introducing international TV shows, followed by Drama, Comedy, and Crime related series between October to January period with actors like Takahiro Sakurai, Junichi Suwabe, Yuki Kaji, etc, this would be a safe & profitable bet as there will be more chance of the show getting hit. As far as Clustering is concerned in the given dataset, Some algorithms are forming 3 clusters, and the majority of them 2, so we can conclude as the total clusters formed on our dataset in most of the cases are between 2 clusters.
