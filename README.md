# Netflix-Data-Analysis
## About NETFLIX

Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.
## Business Problem

Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries.

Dataset_link (https://github.com/lordchan/Netflix-Data-Analysis/blob/main/Netflix%20-%20Python.csv)

The dataset provided consists of a list of all the TV shows/movies available on Netflix:

Show_id: Unique ID for every Movie / Tv Show
Type: Identifier - A Movie or TV Show
Title: Title of the Movie / Tv Show
Director: Director of the Movie
Cast: Actors involved in the movie/show
Country: Country where the movie/show was produced
Date_added: Date it was added on Netflix
Release_year: Actual Release year of the movie/show
Rating: TV Rating of the movie/show
Duration: Total Duration - in minutes or number of seasons
Listed_in: Genre
Description: The summary description

## Process: 
1. Cleaning the data which includes - filling null values with estimates, dropping bad quality data, Unnesting and stacking multiple comma separated data points.
2. Exploratory Data analysis - Understanding the basic metrics of the data, range of values, key features, segregating numerical and categorical columns.
3. Non-Graphical Analysis: Value counts and unique attributes.
4. Visual Analysis - Univariate, Bivariate after pre-processing of the data
4.1 For continuous variable(s): Distplot, countplot, histogram for univariate analysis
4.2 For categorical variable(s): Boxplot
4.3 For correlation: Heatmaps, Pairplots
5. Missing Value & Outlier check (Treatment optional)

## Insights Generated from the analysis:
1. Country: There are 113 countries but most of the movies/shows come from these top 5 countries - US, India, UK, Canada and France.
2. Successfull directors: Marcus Raboy, Martin Campbell, Toshiya Shinohara
3. We see that 70% of the content on netflix is Movies and 30% is TV Shows.
4. 4. Successfull Actors: Anupam Kher and Shah rukh khan have been featured in the most number of movies. And the top actors list is dominated my India.
5. Top Genre: The top 3 Genres are 'International Movies', 'Drama' and 'Comedy'.
6. Duration: The median duration for Movies and TV shows are 1h 40mins and 1 season respectively.
7. Genre: Anime and Classical Movie genre are becoming popular recently.
8. Genre duration: We observe median duration of 'classical movies' is the highest and the genre of 'Movies' is the least.
9. Favourite genre in the biggest markets: Popular genre in US is 'Drama' and in India it is 'International Movies'.
10. Director - Cast combo: We see that the which Actor/Director combination have been featured the most.
11. In Japan and South Korea, TV shows are more popular than movies. Rest of the remaining top countries, movies are more popular than TV shows.

## Recommendations for Netflix to increase viewership on the platform
1. Country: There are 113 countries but not all of them give the most return. We should focus the content more on important countries which - US, India, UK, Canada and France.
2. Successful directors: Since certain director's movie/show are featured more than others, Netflix can make original movies/show by hiring the top directors. For example: Marcus Raboy, Martin Campbell, Toshiya Shinohara.
3. Successful Actors: If Netflix has the budget to pay for star - studded cast, it can hire popular actors/actress to attract more people into the platform. For example: Anupam Kher, Shah Rukh Khan, Takahiro Sakurai etc,.
4. Director - Cast combo: If Netflix has budget constraint, it can hire successful yet lesser know Director- Cast combination. The best combination is mentioned in the table above.
5. Targeting the right genre for specific countries: Netflix can recommend popular genre to the audience of that country. For example: US - Drama, comedy, India - International Movies, UK - 'British TV Shows', Japan - Anime etc,.
6. Duration: Netflix can give more preference to movies whose duration is around 1h 40mins, and shows with 1 or 2 seasons. Since data suggests, this is the ideal duration.
7. Netflix can produce or sponsor more towards specific genres of movies/show. From the data it is visible that specific genre like 'Anime' and 'classical movies' are getting popular recently throughout the world.
8. In countries like Japan and South Korea, Netflix should recommend more TV shows rather than wasting resources on Movies.
9. Should put more content on the platform overall: Because after 2019, the no. of movies/shows added have decreased. People expect latest content.
10 Rating: If Netflix does produce its original content it should prefer TV-Y, TV-G rating category. Since they are more popular recently.
## The final report is here - Netflix - [Netflix - Jupyter Notebook.pdf](https://github.com/lordchan/Netflix-Data-Analysis/blob/main/Netflix%20-%20Jupyter%20Notebook.pdf)

## Along with the jupyter notebook code - [Netflix (1).ipynb](https://github.com/lordchan/Netflix-Data-Analysis/blob/bd4890bfd08646dd95d18a4d75a2ce5dd7dc657d/Netflix%20(1).ipynb)
