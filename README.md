# project
in this  project,i analyse data for microsoft company, they would like to join the big companies in making movie contents.
# DATA PROVIDED:
As a data scientist i had been provided different files of data to use to come up with data analysis
the data includes:
                 [bom.movie_gross.csv.gz](https://github.com/emukami2/project/files/14719322/bom.movie_gross.csv.gz)
                 [rt.movie_info.tsv.gz](https://github.com/emukami2/project/files/14719324/rt.movie_info.tsv.gz)
                 [tmdb.movies.csv.gz](https://github.com/emukami2/project/files/14719325/tmdb.movies.csv.gz)
                 [tn.movie_budgets.csv.gz](https://github.com/emukami2/project/files/14719330/tn.movie_budgets.csv.gz)
                 [rt.reviews.tsv.gz](https://github.com/emukami2/project/files/14719335/rt.reviews.tsv.gz)
I chose rt.reviews.tsv, tmdb.movies.csv and the movie_budgets.csv
Using pandas i read the file path of the above files,and converted them to dataframes and printed the output. 
From there ,there was need to conduct data cleaning to remove duplicates, removing incorrect formatted  data and also incomplete data within a dataset.
from there i printed the first five rows using df.head() of all the dataframes.
# question one:
After that i formulated the first question,through it, i calculated the reviews of each publisher ,then created a data frame showing release_date, ratings and publisher.
from there i used data visualization by using a scatter graph to show the relationship between release date and rating . the last question was counting the number of ratings.
  -from the above question , i was able to draw conclusion like for example, the month and year of movie release affects rating.
  # question two:
from the second question, i used movies_csv_df to answer the following questions, movie with the highest popularity,its title and genre. the second question was about printing the column vote_count , title.
to check the movie with the highest vote_count. from there i created a bar graph to show the title with the highest count and another graph showing which title had the highest popularity.the last bit i  was 
using genre_ids after genre mapping to show which genre has most movies. 
-from the above question i was able to answer which titles had a high popularity and recommended  microsoft to  use  similar titles.
# question three:
the last question i used movie_budgetcsv_df to calculate the profit margin using worldwide_gross - production_budget .from there i listed 25movies with high profit margin. i then drew a scatter graph 
to show the relationship between budget and profit and used a red line to show correlation. finally i finalised with a bar graph showing the relationship betweenn profit and release date.
# three  recommendations to microsoft:
-  Release movies during the last three months of the year.
-  Hire publishers with the high rating for the movies,
-  Choose a movie title that will be popular and get a high vote_count
-  Allocate a budget that is good enough to yeild high profits
-  Read reviews from other movies so that to get a path way of consumer demands.
