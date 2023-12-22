# ada-2023-project-milestone-p2-thedachshunddetectives
ada-2023-project-thedachshunddetectives created by GitHub Classroom
# ADA-Project

## Lights, Camera, ADA! Barbenheimer in Action

## Github Website:
Before diving into the rest of our README and Notebook, here is our a link to our website: [mbonnassies.github.io ](https://mbonnassies.github.io/) 

## Abstract: 
Hi Barbie!
<p align="justify"> Welcome to our dazzling datastory. For this project, we will take you back in time... not too far: Summer 2023. We’re hoping you’ll enjoy the ride! Picture this: Here in Movie-land, you just landed an internship where you work on a task as big as the Manhattan Project, while your friend Ken's job is just, well, BEACH! Seems familiar? Both movies Barbie and Oppenheimer came out the same day during the summer of 2023, and there was a great deal of importance put on both movies. We have selected the wonderful ‘Movie Dataset’ to help us answer one question: could we have predicted Barbie’s blockbuster success over Oppenheimer’s this summer in theaters? We’ll look at this through different lenses. First, how have movie genres performed overall, and how could we relate that analysis to Barbenheimer’s success? Is there a general sentiment behind movie plots, and how does it relate to their revenue? Second, do movie fanatics express a certain affinity with movie characters' personalities, and does that contribute to movie popularity? The analysis will then all be reassessed through a causality analysis. Don't leave on a cliffhanger! Stick around with us for an explosive conclusion, which may or may not inspire you for your next holiday cozy night. </p>



## Research Questions: 
* Would we have expected Barbie to have a bigger success than Oppenheimer if they had come out in 2012?
* Could we analyze genres of various to predict Barbenheimer's success? 
* If we analyze nuances in the datasets, can we observe any relation to Barbie's positive nuances vs Oppenheimer's darker/negative nuances?
* How do movie characters' personalities impact the success of a movie, and could we relate that to Barbenheimer?
* How do different factors influence a movie's success through causal analysis?


## Additional datasets (if any): 

| Additional Data  | Process |
| ------------- | ------------- |
| Barbie & Oppenheimer Dataset  | manually extract data needed from IMDb and website for personality trait gathering|
| MBTI Personality Traits  | Personality traits of the characters present in the movie datasets https://www.kaggle.com/datasets/subinium/movie-character-mbti-dataset/data|
| IMDB Ratings | Ratings used for analysis obtained from https://developer.imdb.com/non-commercial-datasets/#titleratingstsvgz|

## Methods
1. Genre Analysis: Trained an LDA model on the plots of English movies to assess the topical repartition of Barbie and Oppenheimer plots across the genres of Comedy, Adventure, war, drama, action, and fantasy. Used this data to confirm in which genres to categorize Barbie. Used VADER for sentiment analysis and decided to compare Barbie-like genres to Oppenheimer-like genres in terms of positive, negative, and compound values of plots of all movies. Decided to confirm the statistical significance of differences using t-tests. Repeated this process while binning the data across years assuming historical events may affect the differences themselves. Used the compound scores and release year to make a naive analysis of success using ratings, revenue, and number of votes as a metric combined with t-tests to assess statistical significance

2. Character analysis (MBTI): We merge the movie dataset with the online MBTI dataset and look at the prevalence of different character types over the years and through different genres. We also look at Barbie and Oppenheimer datasets of the character MBTI types (found on https://www.personality-database.com/profile?pid=2&cid=3&sub_cat_id=26090 and https://www.personality-database.com/profile?pid=2&cid=3&sub_cat_id=27064e) and then generate conclusions and plots.
  
3. Feature/Causal Analysis: It is trying to answer the question «Could we have predicted Barbie's success over Oppenheimer? ». We are checking the influence of different parameters over what we defined as « success » which can be either grossing or ratings. Most of the first correlations found at the beginning are rather weak but we can say that ratings/revenues are a mix of these factors. Measuring more precisely the influence of extroverts vs introverts might be the key difference between Barbie and Oppenheimer (the first part is more about why are they both successful, and the second is a comparison). To account for covariates, pair matching is performed over many parameters that we think/showed influenced success. Since categorical data is not always available, propensity score matching is conducted. The regression on the balanced dataset is then tested.


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


