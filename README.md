# Oscar-s-night-analysis-
Analysing tweet's trend during the Oscar's night 2021 

This is a final project for the *Data Visualization & Data Management* course from my Master in Data Science that I made with my colleAgue Claudio Fadda. 

The Academy Awards, known as the Oscars, are awards for artistic and technical merit in the film industry. They are regarded as the most prestigious and significant awards in the entertainment industry worldwide. It took place at the Dolby Theatre in Los Angeles, California for the 19th consecutive year. The awards are an international recognition of excellence in cinematic achievements, as assessed by the Academy's voting membership. 

In this project we use different tools to analyse the correspondence betweet tweet's trend during the Oscar's night and other factors as the Category Awards, the TMDB rating and the TMDB popularity. We have done Data Streaming using the API keys provided by Twitter, also we've used Kafka and NiFi Apache. Once all the tweet have been dowladed we moved on to do Data Preparation, Data Cleaning, Data integration and Datawarehouse. In the Data Preparation phase we have merged different datasets obtaining two final datatsets "Complete Actors" that contains tweet that have mentioned the actors/ actress  and "Complete Movies" that contains tweet that have mentioned the movies during the event.  In the Data Cleaning phase we have deleted some parts of the tweet to facilitate the next analysis. In the Data Integration phase we have integrated the dataset with other datasets as TMDB and IMDB to integrate different interesting informations as "rating TMDB" about the movie and the "Popularity" about actors/actress. Finally we have stored the datasets obtained in a cluster of MongoDB  through atlas. 

After these phases, that we have done with **Python**, we have done different visualizations with **Tableau** to analyze the correspondence between the tweet trend during the evening and the awards won, the rating and the popularity of the TMDB site. 
![INFOGRAFICA1](https://user-images.githubusercontent.com/70097258/133938141-c6ab74f7-5757-4975-b7c5-a21b08ac62cb.png)

![photo1631116691](https://user-images.githubusercontent.com/70097258/133938144-91176ec8-5d72-4440-92a8-d187db1d00c1.jpeg)
