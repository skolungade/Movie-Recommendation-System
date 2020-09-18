# Movie-Recommendation-System

There are many feature extraction techniques. We created a bag of words from the movie description or the words collected for the user preference. Then we use the TF-IDF method to recompute the values in this vector. It reduces the importance of a word that frequently occurs in movie descriptions. We then compared the similarity of the corresponding vector of a movie and a user preference for recommendations. For example, we can use the cosine similarity to match a user to different movies.

Using flask, we created a web application, wherein the user enters a movie name, and the system recommends the top 10 similar movies.
