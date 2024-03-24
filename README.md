# PROJECT:
microsoft sees all big companies creating original video content and they want to get in on the fun.They have decide to create a new movie studio but they dont know anything about creating movies. you are
charged with exploring what types of films are currently doing the best at the box office.you must then translate those findings into actionable insights that the head of microsoft's new movie studio can use to help
decide what type of films to create.
# Introduction:
 I am Esther Njagi, a training data scientist, i was given the task above. the first thing was to get the data files given, figure out what the question was about and pick three files i would use. 

# Data:
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

# Methodology:
  # question one:
After that i formulated the first question and its was about calculating the reviews of each publisher ,then created a data frame showing release_date, ratings and publisher.
from there i used data visualization by using a scatter graph to show the relationship between release date and rating. the last question was counting the number of ratings.
  -from the above question , i was able to draw conclusion like , how release dates affect ratings.
  # question two:
from the second question, i used movies_csv_df to answer the following questions: movie with the highest popularity,its title and genre. The second question was about printing the column vote_count and title.
to check the movie with the highest vote_count. from there i created a bar graph to show the title with the highest count and another graph showing which title had the highest popularity.the last bit was 
using genre_ids after genre mapping to show which genre has most movies. 
-from the above question i was able to answer which titles had a big popularity microsoft would consider while choosin a title.
  # question three:
the last question i used movie_budgetcsv_df to calculate the profit margin using worldwide_gross - production_budget .from there i listed 25movies with high profit margin. I  then drew a scatter graph 
to show the relationship between budget and profit and used a red line to show correlation. finally i finalised with a bar graph showing the relationship between profit and release date.

# Results:
from the results, i was able to identify factors that had a major impact on the movie sales,they included:the popularity of the title, the publisher given the mandate and release date.
I also identified that the more you spend on budgeting the higher the likelihood of a big  profit margin.
The genre_ids did not yield ,a big impact as expected because they were in interger form and once i converted them using genre mapping some belonged to more than one genre,majority actually, making classification 
a challenging task.

# Usage:
 Using Visual studio code i wrote my codes to analyze data using python.The codes should be run from the begining. I have also used the comments to explain my codes in a more elaborate and easy to understand way.

# Directory Structure:
The files used in the data analysis have been arranged from file question one to three.

# recommendations to microsoft:
- Release movies during the last three months of the year.
- Hire publishers with the high rating for the movies,
- Choose a movie title that will be popular and get a high vote_count
- Allocate a budget that is good enough to yeild high profits
- Read reviews from other movies so that to get a path way of consumer demands.

# Future Work:
For future analysis, data collection should be more elaborate, there should be no mixing of data types from intergers to strings. the genres of the movies too need to be specifically indentified, not one movie
having more than one genre,it makes it difficult in categorization. Also constant factors affecting the movie industry should be considered like: taxation, talent fees and  inflation, this helps in getting more 
accurate results.

# Conclusion:
it was a great exprience,analyzing data for microsoft. i learnt alot. Thank you!

