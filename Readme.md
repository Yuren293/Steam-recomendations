### Task description
As data for the recommendation system, information about the amount of playing time of users from the Steam gaming platform with game descriptions is taken.

The file steam-200k.csv contains information about users and the games they have purchased and are playing, as well as the amount of playing time in them.    
The file steam.csv is a description of the games, including the name, release date, genre of games, developers, and so on.   
The file steam_description_data.csv contains a text advertising description of the games.     

Source data:   
https://www.kaggle.com/nikdavis/steam-store-games   
https://www.kaggle.com/tamber/steam-video-games

Mean average precision@k is used as a classification quality metric.

This work consists of the following parts:

1) Data preprocessing   
2) Splitting data into train/test  
3) Recommendation quality metric   
4) Popular base approach   
5) FM   
6) Content base approach   
6.1) Preparation of vector representations   
6.2) Word2Vec   
6.3) TF-IDF   
7. LightFM + text   
8. Comparison of recommendations   
