# Restaurant-Recommendation-System
This repository contains a Pune Restaurants Recommendation System implemented using TF-IDF vectorization technique. The recommendation system utilizes a dataset of Pune restaurants.
# Dataset
The "Pune Restaurants Dataset" is a comprehensive collection of restaurant data in Pune, India, obtained from the Zomato API. The dataset is available on Kaggle and provides valuable information about various restaurants located in Pune.

The dataset consists of several features that offer insights into the restaurants' attributes, such as their names, locations, cuisines, average costs for two people, user ratings, and more. It is a valuable resource for data analysts, researchers, and enthusiasts who are interested in exploring the restaurant scene in Pune or studying the dining preferences of its residents.

The features of the dataset are:

1.Restaurant_Name

2.Category	

3.Pricing_for_2

4.Locality	

5.Dining_Rating	

6.Dining_Review_Count	

7.Delivery_Rating	

8.Delivery_Rating_Count	

9.Website	

10.Address	

11.Phone_No	

12.Latitude	

13.Longitude	

14.Known_for1

15.Known_for2

# Methodology
The recommendation system is built using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique. The TF-IDF vectors are calculated for the restaurant descriptions present in the dataset. The cosine similarity measure is then used to find the similarity between different restaurant descriptions.

The recommendation system works as follows:
 1.Preprocess the restaurant descriptions by removing stop words, punctuation, and performing text normalization.
 
 2.Vectorize the preprocessed restaurant descriptions using TF-IDF vectorization.
 
 3.Calculate the cosine similarity between the TF-IDF vectors to find similar restaurants.
 
 4.Given a restaurant, retrieve the top N most similar restaurants based on cosine similarity scores.
 

# Results
The recommendation system provides a list of top N similar restaurants based on the selected restaurant. Users can adjust the value of N to customize the number of recommendations they want to receive. The recommendations are based on the similarity of restaurant descriptions.
Another feature is also present which is a recommendation system based on Type of food. It recommends restaurants based on the food category.





