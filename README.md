# Movie-Recommendation-System
This is a content based recommendation system which will take a movie name as an input and recommends 5 movies.
Model is trained and deployed in heroku platform, link: https://movie-recmndation-gowtham.herokuapp.com/

Dataset link:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv

You can find my blog on this project here https://pub.towardsai.net/how-to-build-a-content-based-recommendation-system-f7d881a53e9a


# What is a recommendation system?
Whenever we visit a shopping mall to buy a new pair of shoes or clothes, we find a dedicated person who helps us with the kind of products we should buy based on our preferences and makes our job simpler. In simple words, he is a recommendation system. But in this modern world, everything is online, and there is so much content on the internet, there are crores of videos on Youtube, and crores of products on Amazon, which makes it difficult for the user to choose. There comes the recommendation system which makes the user's life simple by recommending the next video to watch or a similar product to buy.

A recommendation system is a piece of code that is intelligent enough to understand the user’s preferences and recommend things based on his/her interest, the goal is to increase profitability. For Eg, Youtube and NetFlix want you to spend more time on their platform, so, they recommend the videos based on the user’s preferences. Amazon wants you to buy products from their website so, that they can make more profit.

# Types of Recommendation system:

## Popularity-based: 
Recommending the top products from their website to every user. This method will not consider the user’s interest. Eg, the Trending section on Youtube, IMDB top 250 movies.

## Content-based:
This is based on the similarity between the products. Eg, If a user had watched a movie and liked it, he may like to watch similar movies in the future. This can be based on the genre, actor, actress, or director.

## Collaborative filtering:
This is based on the similarity of users. Eg, If person A and B had watched and liked the movie M, next if person A watches the movie Z and likes it, we can recommend the movie Z to person B, since A and B are similar users.

## Hybrid filtering: 
This makes use of all or some of the above-mentioned methods to form a hybrid model.

Below are some of the recommendations taken from the model.

![image](https://user-images.githubusercontent.com/94861619/185381806-4eb7e604-d844-4af5-bb83-fec89f37d38d.png)
![image](https://user-images.githubusercontent.com/94861619/185381910-228f72da-65ad-4d83-985d-73b7e8f1e0b9.png)
![image](https://user-images.githubusercontent.com/94861619/185381996-c2eef979-3f16-4c23-9c4f-18f1475d24e7.png)
![image](https://user-images.githubusercontent.com/94861619/185382076-7895c1ef-54e2-455e-9b6e-2f683f584e45.png)


