# Recommendations with IBM
The project analyses the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles. The analysis consists of 4 parts:

- I. Exploratory Data Analysis: basic exploration of the data we are working throughout the rest of the notebook. 

- II. Rank Based Recommendations: finding the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we recommend to new users (or anyone depending on what we know about them).

- III. User-User Based Collaborative Filtering: in order to build better recommendations for the users of IBM's platform, we look at users that are similar in terms of the items they have interacted with. These items can be recommended to the similar users. 

- IV. Matrix Factorization: here we complete the machine learning approach and build the recommendations. Using the user-item interactions, we build out a matrix decomposition. Using the decomposition, we can predict new articles to an individual. However the model is not strong enough. We discuss which methods we might use to move forward and how we might test our model.



# Project Components

## Most relevant file
- `Recommendations_with_IBM.ipynb` - the Jupyter notebook contains the entire data analysis, the recommandation system built in the project and comments.
- `Recommendations_with_IBM.pdf` - the PDF preview version of the notebook

## Libraries
- numpy
- pandas
- matplotlib
- pickle

# Licensing, Authors, and Acknowledgements
Data comes from IBM. Thanks to [Udacity](https://www.udacity.com/courses/all) for creating a beautiful learning experience. 