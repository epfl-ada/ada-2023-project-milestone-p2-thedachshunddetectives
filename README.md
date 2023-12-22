# ada-2023-project-milestone-p2-thedachshunddetectives
ada-2023-project-thedachshunddetectives created by GitHub Classroom
# ADA-Project

## Lights, Camera, ADA! Barbenheimer in Action

## Abstract: 

For this project, we will take you back in time... not too far: summer 2023. Picture this: you just landed an internship where you work on a task as big as the Manhattan Project, while your friend Ken's job is just, well, BEACH! Seems familiar? Both movies Barbie and Oppenheimer came out the same day during the summer of 2023, and there was a great deal of importance put on both movies. Somehow, Barbie seemed to have grossed higher than Oppenheimer... Is that a historical trend? Would Barbie still prevail in the previous years? That's what we'll be having a look at in this data story.


## Research Questions: 
* Would we have expected Barbie to have a bigger success than Oppenheimer if they had come out in 2012?
* Could we analyze genres of various to predict Barbenheimer's success? 
* If we analyze nuances in the datasets, can we observe any relation to Barbie's positive nuances vs Oppenheimer's darker/negative nuances?
* How do movie characters' personalities impact the success of a movie, and could we relate that to Barbenheimer?
* How do different factors influence a movie's success through causal analysis?


## Additional datasets (if any): 

| Additional Data  | Process |
| ------------- | ------------- |
| Barbie & Oppenheimer Dataset  | manually extract data needed from IMDb |
| MBTI Personality Traits  | Personality traits of the characters present in the movie datasets|
| IMDB Ratings | Personality traits of the characters present in the movie datasets|

## Methods
1. Genre Analysis: Obtain genres and subgenres from the Barbie and Oppenheimer dataset. Since there exists more than 200 genres, we will try to cluster movies by genres using Kmeans, kmodes or another clustering method to find how often they overlap and then using KNN on the general sentiment of a plot to decide which subgenres fall together. Using this data we will compare the average ratings of genres throughout the years and in general to determined if there was a link betwenn genre and success throughout the years.
2. Genre Analysis: Observe which actor played a type of character more often (archetypes/typical characters) and relate it to the 2 movies. We will extend the analysis and look at the mean grossing of the movies containing these actors in general and attempt to correct for this factor. This can also be done by clustering and creating a distance threshold to check which characters are closer to the Barbenheimer ones, then looking at the mean grossing.
3. Sentiment Analysis: Look at plots, summaries, and keywords to create positive vs negative trends. This will be conducted using the VADER module from the natural language toolkit library. We then observe how well the movies have done, and then predict if Barbie was set to do better.
5. Character analysis (MBTI): We merge the movie dataset with the online MBTI dataset found on https://www.kaggle.com/datasets/subinium/movie-character-mbti-dataset/data and look at the prevalence of different character types over the years and through different genres. We also look at Barbie and Oppenheimer datasets of the character MBTI types (found on https://www.personality-database.com/profile?pid=2&cid=3&sub_cat_id=26090 and https://www.personality-database.com/profile?pid=2&cid=3&sub_cat_id=27064e) and then generate conclusions and plots.
6. Feature/Causal Analysis


## Organization within the team: 

| Person | Tasks |
| ------------- | ------------- |
| Emi  | Website & Datastory, Character Analysis: data processing and plot generation |
| Sophie | Website & Datastory, Character analysis: data processing and plot visualization |
| Marin|  Website Making, Data processing, Clustering, Plot Making, Final Notebook merge, commenting code |
| Andrew|  Genre Analysis: Raw data processing, Sentiment analysis, processing, Plot generation|
| Thomas|  Website Making & Data Visualization, Causal Analysis: Data Processing, Plot Generation,  |

## Ethical Concerns
1. Privacy
2. Data Manipulation
3. Presentation of Data
4. Stakeholders


