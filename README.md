# Book-Recommendation-System
This project is based on Recommender System. Used various Candidate Generation Model to get the recommendations such as Content based and Collaborative Based filtering. We have also implemented Popularity Based Filtering.

**Conclusion**

1. After our analysis, we got to know that the Top-10 most rated books were essentially novels. Books like The Lovely Bone and Wild Animus were very well perceived
2. The majority of the readers were of the age bracket 20-40 and most of them came from North American and European countries namely the USA, Canada, the UK, Germany, and Spain.
3. While looking at the rating distribution, we got to know that most of the books have high ratings with the maximum books being rated 8. Ratings below 5 are few in number.
4. The Top authors with the most books were Agatha Christie, William Shakespeare, and Stephen King.
5. For modeling, it was observed that for model-based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE).

**Challenges**-

    • Handling of sparsity was a major challenge as well since the user interactions were not present for the majority of the books.
    • Since the data consisted of text data, data cleaning was a major challenge in features like Location, etc.
    • Decision-making on missing value imputations and outlier treatment was quite challenging as well.
    • Creation of evaluation matrix to judge which model performs Better
