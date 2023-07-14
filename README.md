# Phase-4-Project-
Movie Recommendation System 
In the highly competitive movie industry, a recommendation system is crucial for movie companies to improve user engagement and increase revenue. By analyzing user preferences, watching patterns, and demographic information, a recommendation system can provide personalized movie recommendations to individual users. This enhances user satisfaction, leading to increased viewership, longer user engagement, and improved customer retention. Additionally, a recommendation system helps movie companies optimize content distribution strategies, targeting the right audience with the right movies. It enables them to cross-promote similar films, increase ticket sales, boost video-on-demand (VOD) purchases, and leverage user-generated content for marketing campaigns. Ultimately, a recommendation system enhances the movie company's competitive edge and contributes to its overall success.
## Data
The dataset contains 100,836 ratings and 3,683 tag applications for a total of 9,742 movies. It was created by 610 users over a period spanning from March 29, 1996, to September 24, 2018. The dataset was generated on September 26, 2018.

## Read and Clean Data
The provided movie data includes information on movie ratings and tags. The data is merged and cleaned to create a consolidated data frame.

## Genre Separation
The movies are described in multiple genres. To analyze the genres more efficiently, a table is created to indicate which genres each movie belongs to. The genres are separated and encoded with binary values (1 for inclusion, 0 for exclusion).

## Visualizing Top Genres
The top genres based on the count and average rating are visualized using bar plots.

![adsf c](https://github.com/justinlapidus25/Phase-4-Project-/assets/130884190/4ace0922-7c0c-4338-b0e6-5493e057f572)


## Creation of Pivot Table
A pivot table is created to organize the movie ratings, user ids, and movie ids. The table is filled with ratings and zeros as placeholders for movies with no reviews.

<img width="684" alt="Screen Shot 2023-07-14 at 1 11 10 PM" src="https://github.com/justinlapidus25/Phase-4-Project-/assets/130884190/dab9d53a-8ae7-42be-9f0e-36899e66176a">


## Visualizing the Number of Ratings
The number of ratings provided by each user and the average number of ratings are visualized using scatter plots.

![HAJSDHFJHASD](https://github.com/justinlapidus25/Phase-4-Project-/assets/130884190/6c86a503-4e82-4dba-ab24-3b2ec5dfa066)


## Creation of Recommendation System
A recommendation system is built using the Surprise library, implementing Funk's Singular Value Decomposition (SVD) algorithm. Cross-validation and model fitting are performed to evaluate and optimize the recommender system.

## Generating Movie Recommendations
The recommendation system generates top movie recommendations based on user preferences and movie similarities. Nearest Neighbors algorithm and cosine similarity are used to find similar movies.

