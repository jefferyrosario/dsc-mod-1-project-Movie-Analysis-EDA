# Module 1 Project Movie Analysis - EDA

## Introduction

Want to understand better understand which movies you may want to invest in? This repo contains just that information at an analytical level. This repo contains an analysis on a few datasets combined from 3 websites: IMDB.com, TheMovieDB.com and RottenTomatoes.com.

## Contents

- student.ipynb - This is a jupyter notebook that contains all of the code involved in performing the data analysis

- what kind of movie should you invest in.ppt - A powerpoint presentation

- zippedData - .csv files that contain a collective of datasets from IMDB.com, TheMovieDB.com and RottenTomatoes.com

## Summary

Gross profit margin and gross profit shows the amount of money you can make based on the genre of the movie. The values were calculated using the gross profit margin formula. Values used were the means of each genre.

![alt text](https://github.com/jefferyrosario/dsc-mod-1-project-v2-1-onl01-dtsc-pt-012120/blob/master/images/genre_profit_margin.png)
https://github.com/jefferyrosario/dsc-mod-1-project-Movie-Analysis-EDA/blob/master/images/genre_gross_profit.png

Gross profit margin indicates that most genres except for History, War, Western and TV Movie have at least a 60% profit margin. The worldwide vs domestic gross profit margin margin to investments in a wordlwide audience, not a domestic audience. 


Let's now take a look at the gross profit. The gross profit is another metric to gauge the overall health of the investments into each genre. 
The values were calculated useing the gross profit average formula. Values used for analysis were the means of each genre.

![alt text](https://github.com/jefferyrosario/dsc-mod-1-project-Movie-Analysis-EDA/blob/master/images/genre_gross_profit.png)

What is clear is that again capturing a worldwide audience as opposed to a domestic audience yeilds right profits. Here we have Animation, Adventure, Science Fiction, Fantasy, and Family movies that have at least 150 million dollars in gross profits. 

Let's take a look at another metric. Let's see how the the producton budget, worldwide gross, and domestic gross do depending on the month it is released. The values were taken from the average of all movies during the month they were released.

![alt text](https://github.com/jefferyrosario/dsc-mod-1-project-v2-1-onl01-dtsc-pt-012120/blob/master/images/release_date_by_month.png)

What we can gather from the graph is the month is important to the overall return on investment. During May-July and November-December, the worldwide gross hovered between 100-200 million dollars with a production budget between 40-60 million dollars. This suggests that movies released during this time should have a higher producton budget. Movies with smaller production budgets should be released from January-April or August-October. 

## Conclusion

Our findings suggest that if you want to maintain a profit margin over 60%, invest in movie genres that are not Western, Documentary, TV Movies, or History. If you want the genre with the highest gross profit and gross profit margin, create an Animation movie. You can still remain creative and release movies of other genres, but depending on your production budget you may want to relase movies with production budgets under 25 million dollars during January-April or August-October. Movies with a higher production budget, should be released May-July or November-December.

## Further Explorations

Some factors I would like to account for are the importance of the actors in the film. Many actors increase the popularity of the film being produced. The director also has some importance. Movies with directors like Martin Scorcese brin he attention of many people. 


