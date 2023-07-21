# Bollywood-movies-project
This contains the bollywood movies dataset and some questions are answered in the code.
The data set contains box office collection and social media promotion information about movies released in the 2013-2015 period, Following are the columns and their description:

S/No-Release Date, 
MovieName-Name of the movie, 
ReleaseTime-Mentions special time of release. LW(Long Weekend), FS(Festive season), HS(Holiday Season), N(Normal), 
Genre-Genre of the film such as Romance, Thriller, Action, Comedy etc, 
Budget-Movie creation budget, 
BoxOfficeCollection, 
YoutubeViews-Number of views of the youtube trailers, 
YoutubeLikes-Number of likes of the youtube trailers, 
YoutubeDislikes-Number of dislikes of the youtube trailers.

Questions:
1. How many records are present in the dataset? Print the metadata information of the dataset.
2. How many movies got released in each genre? which genre had highest number of releases? sort the number of releases in each genre in descending order. 
3. How many movies in each genre got released in different release times like long weekend, festive season, etc.
4. Which month of the year, maximum number movie releases are seen?(Extract a new column called month from ReleaseDate column)
5. Which month of the year typically sees most releases of high budgeted movies, that is, movies with budget of 25 crores and more?
6. Which are the top 10 movies with maximum number return on investment(ROI)? Calculate ROI as (BoxOfficeCollection - Budget)/ Budget.
7. Do the movies have higher ROI if they get released on festive seasons or long weekend? Calculate the average ROI for different releases times.
8. Draw a histogram and a distribution plot to find out the distribution of the movie budgets.Interpret the plot to conclude if the most movies are high or low budgeted movies
9. compare the distribution of ROIs between movies with comedy genre and drama. which genre typically sees higher ROIs?
10. Is there a correlation between box office collection and youtube likes? is the correlation positive or negative?
11. which genre of movies typically sees more Youtube likes? draw boxplots for each genre of movies to compare.
12. which of the variables among Budget, BoxofficeCollection, YoutubeView, YoutubeLikes, YoutubeDislikes are highly correlated? Draw a pairplot or heatmap.
