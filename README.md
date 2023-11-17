# ada-2023-project-milestone-p2-thedachshunddetectives
ada-2023-project-thedachshunddetectives created by GitHub Classroom
# ADA-Project

## Lights, Camera, ADA! Barbenheimer in Action

## Abstract: 

For this project, we will take you back in time... not too far: summer 2023. Picture this: you just landed an internship where you work on a task as big as the Manhattan Project, while your friend Ken's job is just, well, BEACH! Seems familiar? Both movies Barbie and Oppenheimer came out the same day during the summer of 2023, and there was a great deal of importance put on both movies. Somehow, Barbie seemed to have grossed higher than Oppenheimer... Is that a historical trend? Would Barbie still prevail in the previous years ?


## Research Questions: 
* Would we have expected Barbie to gross more than Oppenheimer if they had come out in 2012?
* What would Barbenheimer have looked like if it had come out in 2000, 2005, 2012, etc.? When would they have performed their best? Could we have predicted their success? Who would have been the cast (director, actors)?
* If we analyze nuances in the datasets, can we observe any relation to Barbie's positive nuances vs Oppenheimer's darker/negative nuances?
* Can we observe the genres and subgenres that stand out in both movies and compare them to how well those subgenres have done in other movies? What would happen if Barbie and Oppenheimer integrated a new subgenre in their respective movies? How relevant are the combinations of genres and subgenres for the success of a movie?


## Proposed additional datasets (if any): 

| Additional Data  | Process |
| ------------- | ------------- |
| Barbie & Oppenheimer  | manually extract data needed from IMDb |
| IMDB ratings  | Getting ratings of 42000 movies to determine if movies are well-liked or not and how many people saw them  |
| Get extended plots from IMDb using API  | Obtain more plots if necessary to enhance dataset, taking the largest plot size from either IMDb or CMU dataset |

## Methods
Our limitation: We do not consider inflation and the value of money throughout the years.
1. Genre Analysis: Obtain genres and subgenres from the Barbie and Oppenheimer dataset & then see which one of these genres has done better throughout the years in terms of grossing and ratings
2. Actor Analysis: Observe which actor played a type of character more often (archetypes/typical characters) and relate it to the 2 movies. We can extend the analysis and look at the mean grossing of the movies containing these actors in general. Also, look at the frequency of apparitions of these characters. This can also be done by clustering and creating a distance threshold to check which characters are closer to the Barbenheimer ones, then looking at the mean grossing.
3. Sentiment Analysis: Look at plots, summaries, and keywords to create positive vs negative trends, then observe how well the movies have done, and then predict if Barbie was set to do better. This can be done in general or a yearly analysis.
4. Popularity Analysis: use plot summary embeddings to see which movies are similar to Barbie and Oppenheimer and observe the popularity of each mean grossing over the years(includes 1 and 2 potentially). This can also be done by clustering movies and observing the distance between Barbenheimer.

## Proposed timeline: 
Each chapter will begin on Wednesday (ADA course day), as our group is free to meet on that day. We will host weekly meetings on Wednesdays at noon to discuss the advancement of the project. Starting November 3rd, there are 8 weeks left to work on the project.

Here are the exact milestones:

| Milestones | Explanation |
| ------------- | ------------- |
| November 15th  | finish P2 assignment, load extra datasets  |
| November 29th | work on notebook (75% done) |
| December 13th| notebook 100% done + git website (50% done) |
| December 19th| finished assignment (90%)|
| December 21st| finished assignment (100%)|


## Organization within the team: 

| Person | Tasks |
| ------------- | ------------- |
| Emi  | Website, content visualization and comments |
| Sophie | Character analysis |
| Marin|  Clustering |
| Andrew|  Raw data rocessing, Sentiment analysis, Genre analysis|
| Thomas|  Mediator, data visualization |

## Ethical Concerns
1. Privacy
2. Data Manipulation
