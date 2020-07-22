# Movie-Recommender

With us we have two datasets one is a large dataset and the other one is small.

In the large dataset we have 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.

In the small dataset we have 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.

In credits.csv we have the cast,crew and id and in each cast we have cast_id,character,credit_id,gender,id,name,order,profile_path and in each crew we have credit_id,department,gender,id,job,name,profile_path

In keywords.csv we have id and keywords. In each keyword we have id,keywords_of_the_movie_description.

In links.csv we have movie_id,imdb_id(internet_movie_database),tmdb_id

In links_small.csv we have movie_id,imdb_id and tmdb_id of small subset of movies over 9000

In movies_matadata.csv we have adult,posters,budjet,genres,homepage,id,idmb_id,original_language,original_title,overwiew,popularity,poster_path,production_companies,production_countries,release_date,revenue,runtime,spoken_languages,status,tagline,title,video,vote_average,vote_count

In ratings.csv we have user_id,movie_id,rating,timestamp

In ratings_small.csv we have 100000 ratings from 700 users on 9000 movies

With these we apply collaborative filtering based on users personal taste and movie ratings and popularity

We take inputs the user_id and the movie he searched and give the recommendations accordingly.

The output will be like this:
![image](https://user-images.githubusercontent.com/55240071/88199107-10dcf980-cc62-11ea-83f2-a5c0bf881528.png)
