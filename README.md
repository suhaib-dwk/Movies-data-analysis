# Movies-data-analysis
Data analysis on the "imdb_top_1000" dataset involves examining and interpreting the information contained within it to gain insights and draw conclusions.


Analysis Report: IMDb Dataset - Top 1000 Movies and TV Shows

Introduction

In this analysis, we explored the IMDb dataset of the top 1000 movies and TV shows. The dataset contains information such as the genre, IMDb rating, director, and more. Our goal was to gain insights into the most popular genre of movies and TV shows and identify the director with the most top-rated movies/TV shows.

Data Preprocessing

Before diving into the analysis, we performed some data preprocessing steps. We loaded the dataset into a pandas DataFrame using the read_csv() function. Then, we removed unnecessary columns such as Poster_Link, Series_Title, Released_Year, Certificate, Runtime, Overview, Meta_score, Star1, Star2, Star3, Star4, No_of_Votes, and Gross. These columns were not directly relevant to our analysis of genre or director.

Most Popular Genre

To determine the most popular genre of movies and TV shows, we analyzed the remaining columns. We used pandas to explore the data and calculate the count of movies/TV shows in each genre. By examining the genre distribution, we found that the genre "Drama" was the most popular among the top-rated movies and TV shows.

Genre Distribution

To visualize the genre distribution, we created a bar chart using the matplotlib library. The x-axis represented the different genres, and the y-axis represented the count of movies/TV shows. The bar chart clearly displayed that the "Drama" genre had the highest count, indicating its popularity among the top-rated movies and TV shows.

Director with the Most Top-rated Movies/TV Shows
We further investigated the directors in the dataset to identify the director with the most top-rated movies/TV shows. Using pandas, we created a new DataFrame containing the count of movies/TV shows directed by each director. By analyzing this DataFrame, we found that director "Christopher Nolan" had the highest count of top-rated movies/TV shows.


Director Distribution
To visualize the director distribution, we created a bar chart using matplotlib. The x-axis represented the directors, and the y-axis represented the count of their top-rated movies/TV shows. The bar chart clearly displayed that "Christopher Nolan" had the highest count, indicating his prominence in directing top-rated movies/TV shows.


Conclusion
Based on our analysis of the IMDb dataset, we discovered that the most popular genre among the top 1000 movies and TV shows was "Drama." Additionally, director "Christopher Nolan" stood out with the highest count of top-rated movies/TV shows. These findings provide valuable insights into the preferences of viewers and the influence of directors in the entertainment industry.

It's important to note that this analysis was based on a specific dataset and may not represent the entire IMDb database or the overall trends in the movie and TV show industry. Further analysis and exploration can be done to delve deeper into the relationships between genre, ratings, and directors.

Overall, this analysis gives us a glimpse into the top-rated movies and TV shows and provides valuable information for movie enthusiasts, researchers, and industry professionals.
