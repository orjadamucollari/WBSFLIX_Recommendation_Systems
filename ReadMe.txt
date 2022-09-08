#movie-recommender-webapp

A store, called WBSFLIX, operates in a small town near Berlin and is still alive thanks to a loyal customer base that appreciates the local atmosphere and, more than anything, the personal recommendations of the owner, Ursula.
The task is to create recommender systems that give users from WBSFLIX relevant content to watch.

## What is a Recommendation System?
When a company  lets you know that ‘customers who bought this product also bought…’, that’s a recommendation system. It recommends products or services for you.
The purpose of  a recommender is to reduce the user’s search effort and increase customer satisfaction by showing the most beneficial products. Because of this reduction in the options available to customers, you will see that many recommenders’ titles include the term filtering. 


### Algorithms for Recommendation Systems
* Popularity rankings
* Item-based
* User-based

Popularity rankings
The most simple recommendations are non-personalized: they rank the “most sold” items, the “most watched” movies, etc. Top 10 lists used to tell a lot of people what was hot and what was not. It’s how people found out what was popular, the top 10 books, top 10 songs, top 10 movies.

Item-based
Item-based collaborative filtering methods use item similarity rather than user similarity to make predictions. This is very similar to content-based filtering that we looked at above, however, content-based filtering uses the metadata of products to perceive differences, item-based collaborative filtering uses user preferences.

User-based
By comparing users’ evaluations of the same item, algorithms determine how similar the users are. We can calculate similarity in a variety of ways: cosine similarity, Pearson correlation, or Jaccard similarity. We can then make recommendations for one user, based on the patterns of similar users. For example, if User A and User B watched and enjoyed all the same Disney movies, we could say that they have similar tastes. Therefore, when User B watches and enjoys The Simpsons movie, this could be recommended to User A as something they might also enjoy.


